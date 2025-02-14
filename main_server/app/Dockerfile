FROM nginx
RUN rm /etc/nginx/conf.d/default.conf
RUN apt update && apt install -y nano
COPY nginx.conf /etc/nginx/conf.d/default.conf