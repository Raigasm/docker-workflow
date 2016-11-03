# Set nginx base image
FROM nginx

# File Author / Maintainer
MAINTAINER Rai Butera

# Copy custom configuration file from the current directory
COPY nginx.conf /etc/nginx/nginx.conf
COPY .ssl/uobi_uk /etc/nginx/ssl/uobi_uk

EXPOSE 443
