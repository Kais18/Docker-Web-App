FROM nginx:latest
LABEL "Project" = "Running application"
LABEL "Name" = "Kais"
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vroapp.conf