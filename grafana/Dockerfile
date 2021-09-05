FROM grafana/grafana:7.1.5-ubuntu
ENV GF_AUTH_DISABLE_LOGIN_FORM "true"
ENV GF_AUTH_ANONYMOUS_ENABLED "true"
ENV GF_AUTH_ANONYMOUS_ORG_ROLE "Admin"
ADD datasource.yml /etc/grafana/provisioning
ADD grafana.ini /etc/grafana/grafana.ini
ADD dashboard.yml /etc/grafana/dashboards