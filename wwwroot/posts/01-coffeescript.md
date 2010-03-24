# CoffeeScript is fun

__CoffeeScript is a little language that compiles into JavaScript. Think of it as JavaScript's less ostentatious kid brother - the same genes, roughly the same height, but a different sense of style. __

[coffeescript.org](http://www.coffeescript.org)


## How to use it in ___Mercury___

<pre><code>
# nocream.coffee
<span style='color:green'>html_code:</span> <span style='color:orange'>'''
&lt;h1&gt;Hello From Coffee&lt;/h1&gt;
&lt;p&gt;Nothing like a hot cup of joe.&lt;/p&gt;
'''</span>

<span style='color:green'>$('#mydiv').html(</span><span style='color:yellow'>html_code</span><span style='color:green'>)</span>

# index.haml

= <span style='color:green'>coffee</span> <span style='color:orange'>:nocream</span>

<span style='color:yellow'>#mydiv</span>

  
</code></pre>
