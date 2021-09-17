# Nodejs Server

Server to request data from DNA assurance

## Getting Started

### Installing

* Run from base folder
'''
npm install
. /replace_tar.sh
'''

### Executing program

* go to catalog folder and push/deploy
```
cd catalog
maglev catalog push .
maglev package deploy server  
```

## Updating server

1. update version number in /nodeserver/catalog/Package.yaml
2. update version number in /nodeserver/catalog/myappstack/Appstack.yaml
3. update version number in /nodeserver/catalog/myappstack/ServiceBundle.yaml
4. go back to catalog folder
5. execute the following
```
maglev catalog push .
maglev package upgrade server  
```

## Maintaining

Contributors names and contact info

Cass Tao (castao@cisco.com)

