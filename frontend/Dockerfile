FROM nginx:alpine

RUN rm /etc/nginx/conf.d/default.conf

COPY ./html /usr/share/nginx/html
COPY ./nginx/nginx.conf /etc/nginx/conf.d/mstroy.conf
