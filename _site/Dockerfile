FROM nginx

EXPOSE 80
RUN apt-get update && apt-get install -y git 

RUN rm -rf /pittsburghposse || true
RUN /usr/bin/git clone  https://github.com/drewlander/pittsburghposse.git  
RUN mv /pittsburghposse/_site/* /usr/share/nginx/html
