FROM unicon/shibboleth-sp

ADD /shibboleth-sp/ /etc/shibboleth/
ADD /appfiles/ /var/www/html/
COPY /httpd.conf /etc/httpd/conf 
RUN chown -R shibd:shibd /etc/shibboleth/
RUN chown -R shibd:shibd /var/cache/shibboleth/