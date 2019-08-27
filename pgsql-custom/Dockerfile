FROM registry.access.redhat.com/rhscl/postgresql-96-rhel7 
RUN yum install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm    
RUN yum install -y https://download.postgresql.org/pub/repos/yum/reporpms/EL-7-x86_64/pgdg-redhat-repo-latest.noarch.rpm 
RUN yum install -y geos postgis
USER 26

ENTRYPOINT ["container-entrypoint"]
CMD ["run-postgresql"]
