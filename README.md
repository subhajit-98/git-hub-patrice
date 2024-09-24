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

# GitHub Release/Tag

### Lightweight tag

1. First checkout develop branch
2. Make a new tag by `git tag v0.1.0`
3. Show tag `git tag`
4. Push that tag `git push origin v0.1.0`

- Delete tag (Optional)

1. Delete tag from local `git push origin -D v0.1.0`
2. Delete tag from remote `git push origin --delete v0.1.0`

### Annotated tag

1. First checkout develop branch
2. Make a new tag using of parameter -a `git tag -a v0.2.0 -m "Second release."`
3. Show tag `git tag`
4. Push that tag `git push origin v0.1.0`

---



