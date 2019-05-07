# npm cheatsheet
---

## Package management
### Install packages in package.json
```
npm i
```
or
```
npm install
```
### Install a specific package
```
npm install packagename
```
### Install a specific package and save as dependency
```
npm install --save-dev lodash
```

## Update
### Update production packages
```
npm update
```
### Update dev packages
```
npm update --dev
```
### Update global packages
```
npm update -g
```
### Update a specific package
```
npm update packagename
```
### Update all packages in package.json
```
npm i -g npm-check-updates
ncu -u
npm install
```


## Remove
### Remove node_modules
```
rm -rf node_modules
```
