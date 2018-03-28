FROM osixia/openldap

# Leave config files for diagnostic purposes
ENV LDAP_REMOVE_CONFIG_AFTER_SETUP=false

ADD setup.ldif /container/service/slapd/assets/config/bootstrap/ldif/

