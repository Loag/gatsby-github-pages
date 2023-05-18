# build

## setup

``` bash
npm install -g gatsby-cli && npm install gh-pages --save-dev
```

``` bash
# create new gatsby project

gatsby new test-project

# start dev 
cd test-project/
gatsby develop

```

## update package json

``` json
{
  "scripts": {
    "deploy": "gatsby build && gh-pages -d public -b master"
  },
  "homepage": "https://loag.github.io/gatsby-github-pages/"
}
```

## deployment

``` bash
npm run deploy
```
