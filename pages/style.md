---
layout: page
permalink: /style
title: Style Demo
description: This is a demonstration of the elements in CSS.
categories: [Pages]
sitemap: false
---
<nav id="top">
  → <a href="#article">Article</a>
  → <a href="#aside">Aside</a>
  → <a href="#blockquote">Blockquote</a>
  → <a href="#code">Code</a>
  → <a href="#lists">Lists</a>
  → <a href="#media">Media</a>
  → <a href="#table">Table</a>
  → <a href="#section">Section</a>
  → <a href="#various">Various</a>
</nav>
<hr>

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
<p><b>Bold</b></p>
<p><i>Italic</i></p>
<p><small>Small</small></p>
<p><s>Strikethrough</s></p>
<p>Subscript: H<sub>2</sub>O</p>
<p>Superscript<sup>1</sup></p>
<p><u>Underlined</u></p>
<p><a href="">URL</a></p>
<p><abbr title="Uniform Resource Locator">URL</abbr> Abbreviated</p>
<p><mark>Highlighted</mark></p>
<p><mark>Highlighted <a href="">URL</a></mark></p>
<p><a href=""><button>Button</button></a></p>
<p><cite>Cite</cite></p>
<p><time>Time</time></p>
<p><code>Code</code></p>
<p><var>Variable</var></p>

<p>This is a paragraph showing <b>bold</b> and <i>italic</i> or <small>small</small> text. It also demonstrates what <s>strikethrough</s> and subscript like H<sub>2</sub>O or superscript<sup>1</sup> look like. Here is how <u>underlined</u> text and a <a href="">URL</a> or abbreviated <abbr title="Uniform Resource Locator">URL</abbr> appear. Finally, we have <mark>highlighted</mark> text or <mark>highlighted <a href="">URL</a></mark> and <code>code</code> or <var>variable</var> shown within the paragraph.</p>

<h3 id="article">Article <a class="anchor" href="#article">#</a></h3>

<article>
  <img src="media/sample.png">
  <p><a href=""><b>Post</b></a></p>
  <p>Description</p>
  <p><cite>Date</cite></p>
</article>
<article>
  <img src="media/sample.png">
  <p><a href=""><b>Project</b></a></p>
  <p>Description</p>
</article>

<h3 id="aside">Aside <a class="anchor" href="#aside">#</a></h3>

<h4>With Image</h4>
<aside>
  <img src="media/sample.jpg">
</aside>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
<h4>With Text</h4>
<aside>
  <p><b>Lorem ipsum</b></p>
  <p><small>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</small></p>
</aside>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

<h3 id="blockquote">Blockquote <a class="anchor" href="#blockquote">#</a></h3>

<blockquote>
  <p>Lorem ipsum dolor sit amet</p>
  <p><cite>~ Anonymous</cite></p>
</blockquote>

<p><q>This is a quote.</q></p>

<details>
  <summary>Summary</summary>
  <p>Details</p>
  <p><cite>Reference</cite></p>
</details>

<h3 id="code">Code Block <a class="anchor" href="#code">#</a></h3>

<pre>
body {
  background: var(--body);
  color: var(--text);
  font-size: 1rem;
  line-height: 1.5;
  margin: 0;
}
</pre>

<pre>
H   H  EEEEE  L     L      OOO     W   W   OOO   RRRR   L     DDDD   !!
H   H  E      L     L     O   O    W W W  O   O  R   R  L     D   D  !!
HHHHH  EEEEE  L     L     O   O    W W W  O   O  RRRR   L     D   D  !!
H   H  E      L     L     O   O     W W   O   O  R   R  L     D   D
H   H  EEEEE  LLLLL LLLLL  OOO      W W    OOO   R   R  LLLLL DDDD   !!
</pre>

<p>
<kbd>control</kbd> + <kbd>C</kbd>
</p>
<p>
<kbd>`</kbd> <kbd>1</kbd> <kbd>2</kbd> <kbd>3</kbd> <kbd>4</kbd> <kbd>5</kbd> <kbd>6</kbd> <kbd>7</kbd> <kbd>8</kbd> <kbd>9</kbd> <kbd>0</kbd> <kbd>-</kbd> <kbd>=</kbd> <kbd>delete</kbd>
</p>
<p>
<kbd>tab</kbd> <kbd>Q</kbd> <kbd>W</kbd> <kbd>E</kbd> <kbd>R</kbd> <kbd>T</kbd> <kbd>Y</kbd> <kbd>U</kbd> <kbd>I</kbd> <kbd>O</kbd> <kbd>P</kbd> <kbd>[</kbd> <kbd>]</kbd> <kbd>\</kbd>
</p>
<p>
<kbd>caps</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd> <kbd>F</kbd> <kbd>G</kbd> <kbd>H</kbd> <kbd>J</kbd> <kbd>K</kbd> <kbd>L</kbd> <kbd>;</kbd> <kbd>'</kbd> <kbd>return</kbd>
</p>
<p>
<kbd>shift</kbd> <kbd>Z</kbd> <kbd>X</kbd> <kbd>C</kbd> <kbd>V</kbd> <kbd>B</kbd> <kbd>N</kbd> <kbd>M</kbd> <kbd>,</kbd> <kbd>.</kbd> <kbd>/</kbd> <kbd>shift</kbd>
</p>

<h3 id="lists">Lists <a class="anchor" href="#lists">#</a></h3>

<p><u>Description</u></p>
<dl>
  <dt>Item</dt>
  <dd>Description</dd>
  <dt>Item</dt>
  <dd>Description</dd>
</dl>

<p><u>Ordered</u></p>
<ol>
  <li>Item</li>
  <li>Item
    <ol>
      <li>Item</li>
      <li>Item
        <ol>
          <li>Item</li>
          <li>Item</li>
        </ol>
      </li>
    </ol>
  </li>
</ol>

<p><u>Unordered</u></p>
<ul>
  <li>Item</li>
  <li>Item
    <ul>
      <li>Item</li>
      <li>Item
        <ul>
          <li>Item</li>
          <li>Item</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h3 id="media">Media <a class="anchor" href="#media">#</a></h3>

<audio controls src="media/sample.mp3"></audio>

<video controls loop src="media/sample.mp4"></video>

<figure>
  <img src="media/sample.jpg" alt="Illustration of two people in a boat on a lake with blue hues">
  <figcaption>Here is a caption for the photo.</figcaption>
</figure>

<iframe src="https://example.com"></iframe>

<object type="application/pdf" data="media/sample.pdf"></object>

<h3 id="table">Table <a class="anchor" href="#table">#</a></h3>

<figure>
  <table>
    <caption>Caption</caption>
	  <thead>
	    <tr>
		    <th>Heading 1</th>
			  <th>Heading 2</th>
			  <th>Heading 3</th>
			  <th>Heading 4</th>
			  <th>Heading 5</th>
		  </tr>
	  </thead>
	  <tbody>
	    <tr>
		    <td>Cell 1</td>
			  <td>Cell 2</td>
			  <td>Cell 3</td>
			  <td>Cell 4</td>
			  <td>Cell 5</td>
		  </tr>
	    <tr>
		    <td>Cell 6</td>
			  <td>Cell 7</td>
			  <td>Cell 8</td>
			  <td>Cell 9</td>
			  <td>Cell 10</td>
		  </tr>
	    <tr>
		    <td>Cell 11</td>
			  <td>Cell 12</td>
			  <td>Cell 13</td>
			  <td>Cell 14</td>
			  <td>Cell 15</td>
		  </tr>
	    <tr>
		    <td>Cell 16</td>
			  <td>Cell 17</td>
			  <td>Cell 18</td>
			  <td>Cell 19</td>
			  <td>Cell 20</td>
		  </tr>
	  </tbody>
  </table>
</figure>

<h3 id="section">Section <a class="anchor" href="#section">#</a></h3>

<section>
  <ul>
    <li>
      <span><time>01 Feb, 2025</time></span>
      <a href="">Post 3</a>
    </li>
    <li>
      <span><time>15 Jan, 2025</time></span>
      <a href="">Post 2</a>
    </li>
    <li>
      <span><time>01 Jan, 2025</time></span>
      <a href="">Post 1</a>
    </li>
  </ul>
</section>

<h3 id="various">Various <a class="anchor" href="#various">#</a></h3>

<nav class="tab">
  <a class="tab-current" href="">Tab 1</a>
  <a href="">Tab 2</a>
  <a href="">Tab 3</a>
</nav>

<div class="message">Message with <a href="">Link</a></div>

<div class="gallery">
  <img src="media/sample.jpg">
  <img src="media/sample.jpg">
  <img src="media/sample.jpg">
  <img src="media/sample.jpg">
  <img src="media/sample.jpg">
  <img src="media/sample.jpg">
</div>

<div class="testimonial">
<blockquote>
  <p>Lorem ipsum dolor sit amet</p>
  <p><cite>~ Anonymous</cite></p>
</blockquote>
<blockquote>
  <p>Lorem ipsum dolor sit amet</p>
  <p><cite>~ Anonymous</cite></p>
</blockquote>
</div>

<div class="timeline">
<ul>
  <li><h4>One time</h4><p>Once upon a time…</p></li>
  <li><h4>Another time</h4><p>Another point in time…</p></li>
</ul>
</div>

<p><a href="#top">Return to Top</a> ⤴</p>