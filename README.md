# Running reveal.js
<!-- markdownlint-disable MD012 -->
from .md

![pic](reveal.jpg)



## Goals

* Use reveal.js, because:
  * it is nice
* Content in .md, because:
  * direct github views
  * simpler than html



## Status

* "It works"



## I like

* Repo-centric workflow.
* Matches other workflows
  * Atom with linting
  * Publish in Github



## I'm dubious about

* Copy-paste code in repo, css/js/lib
* Not shipped in this package, you need your own
  [reveal.js checkout](https://github.com/hakimel/reveal.js/)
  * for .md parsing to work locally, had to download:
   [head.min.js](https://cdnjs.cloudflare.com/ajax/libs/headjs/0.96/head.min.js)
   separately



## Further study

* Styling
* Publishing:
  * Rendered presentation with GitHub pages? (Most likely won't work)
  * -> Publish: .md file and PDF. Presentations locally.



## Standalone Setup

* Checkout / Fork this repo
* Go to the repo-dir
* Copy some reveal.js files
  * package.json & Gruntfile.js
  * js/ css/ plugin/ lib/
* Download:
```#!shell
curl https://cdnjs.cloudflare.com/ajax/libs/headjs/0.96/head.min.js >head.min.js
```



## Run locally

```#!shell
npm install
npm start
```

* Select [local.html](http://localhost:8000/local.html)
