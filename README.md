# ๐คช Baylee's Open Source Template

This template allows you to build TypeScript React applications that compile to
gh-pages easily!

## ๐ซ Using this template

Clone the template

```
git clone git@github.com:mxbaylee/pages-template.git PROJECT_NAME
cd PROJECT_NAME
```

## ๐งถ Package.json

Update the port

```
npm run reroll-port
```

Update the "name" and "homepage" inside of `package.json`


### ๐ Push and Deploy

Update git

```
rm -rf .git
git init
git add --all
git commit -m '๐ฅณ Initial commit'
git remote add origin PROJECT_ORIGIN
git push
```

Initial deploy

```
npm install
npm run deploy
```


# ๐ป Logistically

๐ค To run

```
npm install
npm start
```

๐ฆ To deploy

```
npm run deploy
```
