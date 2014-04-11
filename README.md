mathml.css
==========

This is a CSS stylesheet to provide some fallback rendering to browsers without
MathML support. It *must not* be loaded in browsers that have native MathML
support, such as those based on Gecko or WebKit.

You can do some UA string sniffing or some MathML support tests to decide when
to load it, see
[this MDN page](https://developer.mozilla.org/en-US/docs/Web/MathML/Authoring#css-fallback)
for more information about it.

You can see an demo page using [UA string
sniffing](http://fred-wang.github.io/mathml.css/ua.html) or [MathML support
test](http://fred-wang.github.io/mathml.css/mspace.html) that gives an
overview of the basic constructions supported and show how more complex
constructions render.
