# graph-viz-explore
See documentation of schema on similar pages at: http://www.graphviz.org/doc/info/shapes.html

This is just poking only with the `.dot` format

# Installation
https://graphviz.org/download/
## Mac
1. `brew install graphviz`

# VSCode Plugin
* Preview Graph `cmd + shift + v`
* Snippets:
  * `graph` Starts a fresh graph
  
# Rendering Output
[.dot Format Everything](http://www.graphviz.org/pdf/dotguide.pdf). Page 27 helps with output rendering.

## Render Commands
* to .bmp format: `dot -Tbmp manual.dot -o output.bmp`
  * the `-Tbmp` is for rendering to `.bmp`. 
* To .ps format: `dot -Tps manual.dot -o output.ps`