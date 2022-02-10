# Description

PoC IAM Keycloak Deployment

## Service customization

The vanilla keycloak service will be customized with these topics:
1. Custom login theme resources
2. Custom password policy implemented by bcrypt algorithm.
3. Custom keycloak configuration for: 
 - PoC Realm.
 - PoC clients.
 - Poc users and roles.
 - Custom Login theme.
 - Custom passwod policy.

 ## Custom login

 Keycloak will be customized with a particular login creating a login theme called poc inherited fron keycloak theme and configure it.

 ## Custom password policy

 Keycloak will be customized the password policy using the bcrypt algorithm and configure it in keycloak.
