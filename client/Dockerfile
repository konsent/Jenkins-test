FROM nginx

WORKDIR /home/blog/client

RUN mkdir ./build

RUN rm /etc/nginx/conf.d/default.conf

COPY ./daso.conf /etc/nginx/conf.d

EXPOSE 80 

CMD ["nginx", "-g", "daemon off;"]
