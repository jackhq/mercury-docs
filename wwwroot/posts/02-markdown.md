# Markdown 

Haml is awesome, but if you need to crank out some paragraphs or some quick content, you can't beat markdown.  

<pre><code>
#content.md

<span style='color:orange'># Welcome to markdown</span>

The quick brown fox jumps over the fence.
</code></pre>
<pre><code>
#index.haml
  
= <span style='color:green'>markdown</span> <span style='color:orange'>:content</span>