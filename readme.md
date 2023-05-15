# build

## setup

``` bash
npm install -g gatsby-cli && npm install gh-pages --save-dev
```

``` bash
# create new gatsby project

gatsby new PROJECT_NAME

# start dev 
cd PROJECT_NAME/
gatsby develop

```

## update package json

``` json
{
  "scripts": {
    "deploy": "gatsby build && gh-pages -d public -b main"
  },
  "homepage": "https://yourusername.github.io/yourrepository/"
}
```

## deployment

``` bash
npm run deploy
```