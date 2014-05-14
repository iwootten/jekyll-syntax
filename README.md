# Jekyll Syntax

This is a collection of stylesheets used for colouring pygments highlighted source code listing within jekyll posts. Copy any one of these into a /css folder in your jekyll source directory and link to it in your posts html.

You can create any one of these on your own machine using the syntax:

```bash
pygmentize -f html -S monokai -a .highlight > monokai.css
```

Where monokai is the colour palette we want to use.

I've created this repo so we don't have to remember this.

You can see a demo of each stylesheet here: http://pygments.org/demo/357593/.