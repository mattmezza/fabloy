FABRIC fabfile.py generator
=======

A minimalistic fabfile.py generator for simple ssh deploy

### Install

```bash
cd /usr/local/bin
curl -O https://raw.githubusercontent.com/mattmezza/fabloy/master/fabloy
chmod a+x fabloy
```

### Usage

```bash
fabloy "host.com" "matt" "/var/www" > fabfile.py
```

```bash
fab deploy_php
```
