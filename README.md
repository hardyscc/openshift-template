# Openshift & Gitlab Installation Template

1. Genetate an install.txt or install-adv.txt

```
export DOMAIN=<your domain>
export USER=<user name>
export PROJECT=<project name>
export HTTP_PROXY=<http proxy (only if required)>
export DOLLAR='$'

envsubst < install-template.txt > install.txt
envsubst < install-template-adv.txt > install-adv.txt
```

2. Follow the install.txt or install-adv.txt to install, enjoy ;)
