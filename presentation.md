
# Introduction

Note: this is a comment (hit s to view speaker view)

====

vertical lower slide here

----

# Image example


<figure>
<img src="media/logo.svg" style="width:15%"/>
 <figcaption>A real figure caption</figcaption> 
</figure>




----

# Code example

<pre><code class="hljs" data-trim contenteditable>
    function linkify( selector ) {
      if( supports3DTransforms ) {

        var nodes = document.querySelectorAll( selector );

        for( var i = 0, len = nodes.length; i &lt; len; i++ ) {
          var node = nodes[i];

          if( !node.className ) {
            node.className += ' roll';
          }
        }
      }
</code></pre>

----

# Fragment Example

### uncertainty and planning
* conditional planning <!-- .element: class="fragment" -->
    * making a whole policy tree in advance<!-- .element: class="fragment" -->
* replanning<!-- .element: class="fragment" -->
    * execute and monitor an optimistic plan, replan when it fails<!-- .element: class="fragment" -->
* (probabalistic) conformant planning <!-- .element: class="fragment" -->
    * find an open-loop plan that is guaranteed to achieve the goal (with high probability) <!-- .element: class="fragment" -->

----

# Math Example

* The belief of an object is a real valued interval on SE(2) described by:
\begin{equation}
b_i = Bel(x_c,y_c,w,h,\Theta)
\end{equation}

this descibes all object poses \\(x,y,\theta\\) with
\begin{equation}
x_c -w < x < x_c + w\\\\
y_c -h < y < y_c + h\\\\
-\Theta < \theta < \Theta
\end{equation}
* A **state** is a tuple of belief states on object poses $$x=(b_1, b_2, \ldots, b_m)$$

