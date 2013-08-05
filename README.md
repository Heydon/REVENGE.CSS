## REVENGE.CSS

The premise of `revenge.css` is simple: A *CSS bookmarklet* that uses selectors to find bad markup, displaying ugly pink error messages in *comic sans serif* wherever you write bad HTML. If you activate the bookmarklet and the page gets lots of pink blotches, the author will have included at least one of the following:

* Misplaced &lt;div&gt;s
* Deprecated elements
* Malformed hyperlinks
* Inaccessible forms
* Empty elements
* Inaccessible images
* Missing ARIA landmarks
* Badly authored sectioning elements
* Erroneous lists
* Obsolete attributes

## Try the bookmarklet

The code to make the bookmarklet is below. When it is saved to bookmarks, you can simply click it while viewing any webpage you wish to test.

~~~
<a href="javascript:(function(){revenge=document.createElement('LINK');revenge.href='http://rawgithub.com/Heydon/REVENGE.CSS/master/revenge.css';revenge.rel='stylesheet';revenge.media='all';document.body.appendChild(revenge);})();" title="REVENGE.CSS">REVENGE.CSS</a>
~~~

