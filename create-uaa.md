# Create UAA Service Instance

```shell
cf create-service xsuaa space openSAP-ex-uaa -c xs-security.json

cf create-service-key openSAP-ex-uaa default

cf service-key openSAP-ex-uaa default
```
