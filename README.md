mathml.css
==========

This is a CSS stylesheet to provide some fallback rendering to browsers without
MathML support. It *must not* be loaded in browsers that have native MathML
support, such as those based on Gecko or WebKit. You can do some UA string
sniffing to decide when to load it, see

https://developer.mozilla.org/en-US/docs/Web/MathML/Authoring#css-fallback
