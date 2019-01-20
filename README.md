# Openshift & Gitlab Installation Template

1. Genetate an install.txt

```
export DOMAIN=<your domain>
export USER=<user name>
export HTTP_PROXY=<http proxy (only if required)>

envsubst < install-template.txt > install.txt
```

2. Follow the install.txt to install, enjoy ;)
