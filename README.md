
# opensocks-cloud
Deploy opensocks server to cloud

[![Travis](https://travis-ci.com/net-byte/opensocks-cloud.svg?branch=main)](https://github.com/net-byte/opensocks-cloud)
[![Go Report Card](https://goreportcard.com/badge/github.com/net-byte/opensocks-cloud)](https://goreportcard.com/report/github.com/net-byte/opensocks-cloud)
![image](https://img.shields.io/badge/License-MIT-orange)
![image](https://img.shields.io/badge/License-Anti--996-red)

## Deploy

[![Deploy to heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ilovecar/opensocks-cloud/tree/main)

[![Deploy to okteto](https://okteto.com/develop-okteto.svg)](https://cloud.okteto.com/deploy?repository=https://github.com/ilovecar/opensocks-cloud)

### client cmdline:

./opensocks-linux-amd64 -s=[you path?].herokuapp.com:80 -l=0.0.0.0:1088 -k=helloworld -scheme ws -obfs

## Config Vars
```
PORT = 8080
KEY = helloworld
OBFS = true
```

Note:

heroku can reset the env vars anytime, both create age or edit age later.

but okteto can only reset during image creating age.
