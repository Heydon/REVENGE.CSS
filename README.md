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

Just drag the following link to your bookmarks. Click the bookmarklet on any page you wish to test. 

<a style="font-size: 2em; padding: 1em; background: pink; font-family: 'comic sans ms', cursive; display: inline-block; color: #000;" href="javascript:(function(){revenge=document.createElement('LINK');revenge.href='http://www.heydonworks.com/css/revenge_buttons.css';revenge.rel='stylesheet';revenge.media='all';document.body.appendChild(revenge);})();" title="REVENGE.CSS">REVENGE.CSS <span style="display:block; margin-top: 0.25em; font-size: 0.7em">(drag me to bookmarks)</span></a>


