# SCSS 

Sassy CSS

%p
  SCSS is a css3 compliant markup that supports sass mixins and other functionality.  Check out [http://beta.sass-lang.com/docs/yardoc/file.SASS_CHANGELOG.html#scss_sassy_css](http://beta.sass-lang.com/docs/yardoc/file.SASS_CHANGELOG.html#scss_sassy_css)

<pre><code>

<span style='color:orange'>@mixin</span> nav_a {
  padding: 0.5px;
  color: #004080; }

#navigation {
  text-align: left;
  ul {
    list-style: none;
    li {
      display: inline;
      a {
        <span style='color:orange'>@include</span> nav_a; } } } }

</code></pre>
<pre><code>
#navigation {
  text-align: left; }
  #navigation ul {
    list-style: none; }
    #navigation ul li {
      display: inline; }
      #navigation ul li a {
        padding: 0.5px;
        color: #004080; }
</code></pre>
