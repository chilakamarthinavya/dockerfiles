FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/chilakamarthinavya/ansible/refs/heads/main/01.helloworld.yaml
CMD ["nginx", "-g", "daemon off;"] 