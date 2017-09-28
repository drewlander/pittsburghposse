FROM nginx

EXPOSE 80
RUN apt-get update && apt-get install -y git 

RUN /usr/bin/git clone  https://github.com/drewlander/pittsburghposse.git  
#RUN cd pittsburghposse/_site
#RUN mv * /usr/share/nginx/html
