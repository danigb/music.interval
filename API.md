# API


<!-- START docme generated API please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN docme TO UPDATE -->

<div>
<div class="jsdoc-githubify">
<section>
<article>
<div class="container-overview">
<dl class="details">
</dl>
</div>
<dl>
<dt>
<h4 class="name" id="invert"><span class="type-signature"></span>invert<span class="type-signature"></span></h4>
</dt>
<dd>
<div class="description">
<p>Get the inversion of an interval. The inversion of an interval is always a
simple interval</p>
</div>
<dl class="details">
<dt class="tag-source">Source:</dt>
<dd class="tag-source"><ul class="dummy">
<li>
<a href="https://github.com/danigb/music.interval/blob/master/interval.js">interval.js</a>
<span>, </span>
<a href="https://github.com/danigb/music.interval/blob/master/interval.js#L47">lineno 47</a>
</li>
</ul></dd>
</dl>
<h5>Example</h5>
<pre class="prettyprint"><code>invert('3M') // => '6m'</code></pre>
</dd>
<dt>
<h4 class="name" id="semitones"><span class="type-signature"></span>semitones<span class="type-signature"></span></h4>
</dt>
<dd>
<div class="description">
<p>Get the semitones of a interval</p>
</div>
<dl class="details">
<dt class="tag-source">Source:</dt>
<dd class="tag-source"><ul class="dummy">
<li>
<a href="https://github.com/danigb/music.interval/blob/master/index.js">index.js</a>
<span>, </span>
<a href="https://github.com/danigb/music.interval/blob/master/index.js#L94">lineno 94</a>
</li>
</ul></dd>
</dl>
<h5>Example</h5>
<pre class="prettyprint"><code>semitones('5P') // => 7
semitones('-5P') // => -7</code></pre>
</dd>
<dt>
<h4 class="name" id="semitones"><span class="type-signature"></span>semitones<span class="type-signature"></span></h4>
</dt>
<dd>
<div class="description">
<p>Get the semitones of a interval</p>
</div>
<dl class="details">
<dt class="tag-source">Source:</dt>
<dd class="tag-source"><ul class="dummy">
<li>
<a href="https://github.com/danigb/music.interval/blob/master/interval.js">interval.js</a>
<span>, </span>
<a href="https://github.com/danigb/music.interval/blob/master/interval.js#L104">lineno 104</a>
</li>
</ul></dd>
</dl>
<h5>Example</h5>
<pre class="prettyprint"><code>semitones('5P') // => 7
semitones('-5P') // => -7</code></pre>
</dd>
<dt>
<h4 class="name" id="simplify"><span class="type-signature"></span>simplify<span class="type-signature"></span></h4>
</dt>
<dd>
<div class="description">
<p>Simplify an interval</p>
</div>
<dl class="details">
<dt class="tag-source">Source:</dt>
<dd class="tag-source"><ul class="dummy">
<li>
<a href="https://github.com/danigb/music.interval/blob/master/index.js">index.js</a>
<span>, </span>
<a href="https://github.com/danigb/music.interval/blob/master/index.js#L26">lineno 26</a>
</li>
</ul></dd>
</dl>
<h5>Example</h5>
<pre class="prettyprint"><code>simplify('9M') // => '2M'
simplify('-9M') // => '-2M'</code></pre>
</dd>
<dt>
<h4 class="name" id="simplify"><span class="type-signature"></span>simplify<span class="type-signature"></span></h4>
</dt>
<dd>
<div class="description">
<p>Simplify an interval</p>
</div>
<dl class="details">
<dt class="tag-source">Source:</dt>
<dd class="tag-source"><ul class="dummy">
<li>
<a href="https://github.com/danigb/music.interval/blob/master/interval.js">interval.js</a>
<span>, </span>
<a href="https://github.com/danigb/music.interval/blob/master/interval.js#L25">lineno 25</a>
</li>
</ul></dd>
</dl>
<h5>Example</h5>
<pre class="prettyprint"><code>simplify('9M') // => '2M'
simplify('-9M') // => '-2M'</code></pre>
</dd>
<dt>
<h4 class="name" id="type"><span class="type-signature"></span>type<span class="type-signature"></span></h4>
</dt>
<dd>
<div class="description">
<p>Get the type of an interval (<code>'P'</code> for <strong>perfetable</strong> and <code>'M'</code> for <strong>majorable</strong>)</p>
<p>It does NOT return the quality of the interval (@see interval/quality)</p>
</div>
<dl class="details">
<dt class="tag-source">Source:</dt>
<dd class="tag-source"><ul class="dummy">
<li>
<a href="https://github.com/danigb/music.interval/blob/master/index.js">index.js</a>
<span>, </span>
<a href="https://github.com/danigb/music.interval/blob/master/index.js#L70">lineno 70</a>
</li>
</ul></dd>
</dl>
<h5>Example</h5>
<pre class="prettyprint"><code>type('4P') // => 'P'
type('5A') // => 'P'
type('3m') // => 'M'
type('2d') // => 'M'</code></pre>
</dd>
<dt>
<h4 class="name" id="type"><span class="type-signature"></span>type<span class="type-signature"></span></h4>
</dt>
<dd>
<div class="description">
<p>Get the type of an interval (<code>'P'</code> for <strong>perfetable</strong> and <code>'M'</code> for <strong>majorable</strong>)</p>
<p>It does NOT return the quality of the interval (@see interval/quality)</p>
</div>
<dl class="details">
<dt class="tag-source">Source:</dt>
<dd class="tag-source"><ul class="dummy">
<li>
<a href="https://github.com/danigb/music.interval/blob/master/interval.js">interval.js</a>
<span>, </span>
<a href="https://github.com/danigb/music.interval/blob/master/interval.js#L68">lineno 68</a>
</li>
</ul></dd>
</dl>
<h5>Example</h5>
<pre class="prettyprint"><code>type('4P') // => 'P'
type('5A') // => 'P'
type('3m') // => 'M'
type('2d') // => 'M'</code></pre>
</dd>
</dl>
<dl>
<dt>
<h4 class="name" id="interval"><span class="type-signature"></span>interval<span class="signature">()</span><span class="type-signature"></span></h4>
</dt>
<dd>
<div class="description">
<p>Get an inversal string from source or null if not a valid interval</p>
</div>
<dl class="details">
<dt class="tag-source">Source:</dt>
<dd class="tag-source"><ul class="dummy">
<li>
<a href="https://github.com/danigb/music.interval/blob/master/interval.js">interval.js</a>
<span>, </span>
<a href="https://github.com/danigb/music.interval/blob/master/interval.js#L19">lineno 19</a>
</li>
</ul></dd>
</dl>
</dd>
<dt>
<h4 class="name" id="interval"><span class="type-signature"></span>interval<span class="signature">()</span><span class="type-signature"></span></h4>
</dt>
<dd>
<div class="description">
<p>Get an inversal string from source or null if not a valid interval</p>
</div>
<dl class="details">
<dt class="tag-source">Source:</dt>
<dd class="tag-source"><ul class="dummy">
<li>
<a href="https://github.com/danigb/music.interval/blob/master/index.js">index.js</a>
<span>, </span>
<a href="https://github.com/danigb/music.interval/blob/master/index.js#L20">lineno 20</a>
</li>
</ul></dd>
</dl>
</dd>
<dt>
<h4 class="name" id="invert"><span class="type-signature"></span>invert<span class="signature">(interval)</span><span class="type-signature"></span></h4>
</dt>
<dd>
<div class="description">
<p>Get the <a href="https://en.wikipedia.org/wiki/Interval_(music">inversion</a>#Inversion)
of an interval. All inverted intervals are simple.</p>
</div>
<h5>Parameters:</h5>
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name"><code>interval</code></td>
<td class="type">
<span class="param-type">String</span>
|
<span class="param-type">Array</span>
</td>
<td class="description last"><p>the interval to invert</p></td>
</tr>
</tbody>
</table>
<dl class="details">
<dt class="tag-source">Source:</dt>
<dd class="tag-source"><ul class="dummy">
<li>
<a href="https://github.com/danigb/music.interval/blob/master/index.js">index.js</a>
<span>, </span>
<a href="https://github.com/danigb/music.interval/blob/master/index.js#L60">lineno 60</a>
</li>
</ul></dd>
</dl>
<h5>Example</h5>
<pre class="prettyprint"><code>invert('9M') // => '2M'
invert('-10M') // => '-3M'
invert('-11P') // => '-4P'</code></pre>
</dd>
</dl>
</article>
</section>
</div>

*generated with [docme](https://github.com/thlorenz/docme)*
</div>
<!-- END docme generated API please keep comment here to allow auto update -->
