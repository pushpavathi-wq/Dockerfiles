FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html 
# we are passing some sondition to user, to use our image, create your own index.html,cant use ours
CMD ["nginx" , "-g" , "daemon off;"]

#