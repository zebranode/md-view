# md-view

A simple [Express](https://expressjs.com/) app that parses and displays a markdown file from a URL, including [shared Dropbox URLs](https://help.dropbox.com/files-folders/share/view-only-access). When deployed, it can be used to modify a raw markdown URL to make it immediately viewable in the browser for sharing. 

Use at: [https://mdview.herokuapp.com](https://mdview.herokuapp.com)  
Example: [https://mdview.herokuapp.com/?url=https://raw.githubusercontent.com/microsoft/vscode/master/README.md](https://mdview.herokuapp.com/?url=https://raw.githubusercontent.com/microsoft/vscode/master/README.md)  

# about

Served using [Node.js](https://nodejs.org/), [Express](https://expressjs.com/), [express-handlebars](https://github.com/ericf/express-handlebars), and [Axios](https://github.com/axios/axios). 

Markdown converted to HTML with [Showdown](http://showdownjs.com/), and styled with [github-markdown-css](https://github.com/sindresorhus/github-markdown-css).

Code highlighting by [highlight.js](https://highlightjs.org/) and [showdown-highlight](https://github.com/Bloggify/showdown-highlight). 

Clipboard copy functionality by [clipboard.js](https://clipboardjs.com/).

Boilerplate generated with [Express application generator](https://expressjs.com/en/starter/generator.html).

----

![md-view](https://github.com/onecheesepizza/md-view/raw/master/public/images/md-view-sc-640-opt2.gif)

# run locally

GitHub: [https://github.com/onecheesepizza/md-view](https://github.com/onecheesepizza/md-view)


`git clone` the repo to your computer, `cd` to the repo directory, then:

```bash
npm install
npm start
```
and visit [http://localhost:3000](http://localhost:3000)