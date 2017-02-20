# Running reveal.js
<!-- markdownlint-disable MD012 -->
from .md

![pic](reveal.jpg)

Note:
* Speakers notes go here



## Goals

* Use reveal.js, because:
  * it is nice
* Content in .md, because:
  * direct github views
  * simpler than html



## Status

* "It works"


## Example: Fragments

<!-- .slide: data-background="#aa2222" -->

* Fragment 1 <!-- .element: class="fragment" data-fragment-index="1" -->


## Example: Background Image <!-- .element: class="transparent-black" -->
<!-- .slide: data-background-image="background.jpg" -->

AWESOME! <!-- .element: class="transparent-white" -->


## Highlighted words.

Highlighted Lorem Ipsum <!-- .element: class="highlight-red" -->

Not Highlighted


## Example: Code

```shell
echo "Hello world."
exit 0
```


## Example: Autoplay Video
<video data-autoplay class="stretch" src="breakout.mov"></video>

Original: <https://www.youtube.com/watch?v=efexDg5q7Dw>


## Example: Background Video <!-- .element: class="transparent-white" -->

<!-- .slide: data-background-video="breakout.mov" data-background-video-loop="true"-->
<!-- .slide: data-background="#000000" -->

Still need to use raw HTML to <!-- .element: class="transparent-white" -->
<span style="color: rgb(255, 0, 136);">
override color.
</span>


## I like

* Repo-centric workflow
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
  * Rendered presentation with GitHub pages?
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
