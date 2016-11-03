# Set nginx base image
FROM nginx

# File Author / Maintainer
MAINTAINER Rai Butera

# Copy custom configuration file from the current directory
COPY uobi_uk.key /etc/nginx/ssl/uobi_uk/uobi_uk.key
COPY ssl-bundle.crt /etc/nginx/ssl/uobi_uk/ssl-bundle.crt
COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 443
