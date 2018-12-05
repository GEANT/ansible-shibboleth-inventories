# idp/conf directory - Where you put your custom files

This directory is useful to provide the custom version of:

- ```saml-nameid.properties```
- ```global.xml```
- ```idp.properties```
- ```ldap.properties```
- ```services.properties```
- ```services.xml```
- ```attribute-resolver.xml``` (that will be renamed into "attribute-resolver-v3-custom.xml" to maintain the original one)
- ```attribute-filter.xml```   (that will be renamed into "attribute-filter-custom.xml" to maintain the original one)
- ```authn/ldap-authn-config.xml```
- ```authn/password-authn-config.xml```
- ```c14n/subject-c14n.xml```
- ```logback.xml```
- ```attribute-filter-v3-coco.xml```
- ```attribute-filter-v3-rs.xml```
- ```audit.xml```
- ```mvc-beans.xml```

Leave this directory empty to keep the repository version.
