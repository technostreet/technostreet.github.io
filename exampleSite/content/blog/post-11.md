---
title: Deploying a React App* to GitHub Pages
date: 2019-10-29T10:07:47.000+06:00
image: images/post/post-2.jpg
description: this is meta description
categories: []
tags:
- HTML
- New
type: post

---
[https://github.com/gitname/react-gh-pages](https://github.com/gitname/react-gh-pages "https://github.com/gitname/react-gh-pages")  
  
If you are facing such issue -   
"You are running \`create-react-app\` 4.0.3, which is behind the latest release (5.0.1).

We no longer support global installation of Create React App.

Please remove any global installs with one of the following commands:

\- npm uninstall -g create-react-app

\- yarn global remove create-react-app

The latest instructions for creating a new app can be found here:

[https://create-react-app.dev/docs/getting-started/](https://create-react-app.dev/docs/getting-started/ "https://create-react-app.dev/docs/getting-started/")

"  
  
Solution - run this command   
  
npx create-react-app@5.0.1 my-app