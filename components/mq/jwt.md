```
curl -s https://keycloak-cp4i.apps.t9xdnubu.eastus.aroapp.io/realms/master/protocol/openid-connect/certs | jq ' .keys[0].x5c[0]'
```


