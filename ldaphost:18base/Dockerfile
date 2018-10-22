# Version: 0.0.1
# @edt M06 2018-2019
#ldapserver base edt.org
#----------------------------
FROM fedora:27
LABEL autor="@edt ASIX M06 Curs 2018-2019"
LABEL descripction="ldap -----"
RUN dnf -y install procps openldap-clients 
RUN mkdir /opt/docker
COPY * /opt/docker/
RUN cp /opt/docker/ldap.conf /etc/openldap/ldap.conf 
WORKDIR /opt/docker
CMD ["/bin/bash"]

