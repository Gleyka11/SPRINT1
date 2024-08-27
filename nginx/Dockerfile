FROM nginx:latest

COPY default.conf /etc/nginx/conf.d

RUN mkdir /etc/nginx/ssl

COPY certificado.crt /etc/nginx/ssl

COPY certificado.key /etc/nginx/ssl

RUN chown -R root:root /etc/nginx/ssl

RUN chmod -R 600 /etc/nginx/ssl

 

