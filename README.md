# my-nuxt-project

> Nuxt.js project

## Build Setup

``` bash
# install dependencies
$ npm install # Or yarn install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).


## AWS Elastic Beanstalk

### Init
```
eb init -r us-west-2 -p node.js-16 --profile=terraform
```

### Create
```
eb create my-nuxt-project -s -i t2.small --profile=terraform
```

### Deploy
```
eb deploy my-nuxt-project --profile=terraform
```
