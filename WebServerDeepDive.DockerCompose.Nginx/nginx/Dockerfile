FROM nginx:1.25.3-alpine
COPY nginx.conf /etc/nginx/conf.d/default.conf

#RUN useradd -ms /bin/bash nginx && \
#chown -R nginx:nginx /etc/nginx /var/cache/nginx /var/run /var/log/nginx && \
#chmod 755 /etc/nginx /var/cache/nginx /var/run /var/log/nginx
#
#USER nginx
#
#EXPOSE 80 443
#
#CMD ["nginx", "-g", "daemon off;"]