# install apache2 & run a html page on it:

FROM httpd:alpine3.15   
  # never try to use latest version over here
COPY "index.html" "/usr/local/apache2/htdocs/index.html"
EXPOSE 80
  # our container/application will require 80 port
