---
layout: doc
title: Buttons
categories: elements
permalink: /docs/elements/buttons/
---

<p>Buttons come in two basic flavors in Kissui. 
The standard <code>&lt;button&gt;</code> element is plain, whereas the <code>.button .primary</code> button is vibrant and prominent. Button styles are applied to a number of appropriate form elements, but can also be arbitrarily attached to anchors with a <code>.button</code> class.</p>

<div class="docs-example">
<div>
  <a class="button" href="#">Anchor button</a>
  <button>Button element</button>
  <input type="submit" value="submit input">
  <input type="button" value="button input">
</div>
<div>
  <a class="button primary" href="#">Anchor button</a>
  <button class="button primary">Button element</button>
  <input class="button primary" type="submit" value="submit input">
  <input class="button primary" type="button" value="button input">
</div>
</div>

<pre class="code-example">
<code class="language-html">&lt;!-- Standard buttons --&gt;
&lt;a class="button" href="#"&gt;Anchor button&lt;/a&gt;
&lt;button&gt;Button element&lt;/button&gt;
&lt;input type="submit" value="submit input"&gt;
&lt;input type="button" value="button input"&gt;

&lt;!-- Primary buttons --&gt;
&lt;a class="button primary" href="#"&gt;Anchor button&lt;/a&gt;
&lt;button class="button primary"&gt;Button element&lt;/button&gt;
&lt;input class="button primary" type="submit" value="submit input"&gt;
&lt;input class="button primary" type="button" value="button input"&gt;
</code>
</pre>
