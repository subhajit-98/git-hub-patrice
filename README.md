# Deploy On GitHub

- set up git-hub with the react folder
- Install npm install --save-dev gh-pages
- Add bellow script in package.json file

`
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
`

`
"homepage": "https://gitname.github.io/react-gh-pages"
`

- After that `npm run deploy`

---


