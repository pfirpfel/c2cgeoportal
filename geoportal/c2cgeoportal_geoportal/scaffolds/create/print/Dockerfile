FROM camptocamp/mapfish_print:3.10.3
LABEL maintainer Camptocamp "info@camptocamp.com"

RUN rm -rf webapps/ROOT/print-apps
ADD print-apps ${CATALINA_HOME}/webapps/ROOT/print-apps
