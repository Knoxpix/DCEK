FROM nginx:alpine

RUN apk add --no-cache bash

RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD ["/bin/bash", "-c", "nginx -g \"daemon off;\""]
