FROM nginx

LABEL "Project"="Vprofile"
LABEL "Author"="Nasif"

RUN rm -rf /etc/nginx/conf.d/default.conf
#COPY nginx.conf /etc/nginx/conf.d
COPY nginxvproapp.conf /etc/nginx/conf.d/vproapp.conf
