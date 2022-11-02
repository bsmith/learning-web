# Learning the Web

MDN:

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)

Link types:

* [`<link>` types](https://developer.mozilla.org/en-US/docs/Web/HTML/Link_types) (MDN)

Interesting elements:

* [`<details>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details) (MDN)
* [`<aside>` element](https://html.spec.whatwg.org/multipage/sections.html#the-aside-element) (whatwg spec)
* [hierarchically correct main element](https://html.spec.whatwg.org/multipage/grouping-content.html#hierarchically-correct-main-element) (whatwg spec)

Other tools:

* [Unicode's Emoji List](https://unicode.org/emoji/charts/full-emoji-list.html)

Interesting articles:

* [There Is No Document Outline Algorithm](https://adrianroselli.com/2016/08/there-is-no-document-outline-algorithm.html)
	* [The Truth about “The Truth About Multiple H1 Tags”](https://adrianroselli.com/2013/12/the-truth-about-truth-about-multiple-h1.html)
	* In summary: only use one `<h1>` tag, and use your other headers strictly in order, not skipping any.  Remember CSS can style and hide them.
	* NB. This had its last update in 2022!
* [Why You Should Choose HTML5 article Over section](https://www.smashingmagazine.com/2020/01/html5-article-section/)
	* WatchOS reads web pages! [Designing Web Content for watchOS](https://developer.apple.com/videos/play/wwdc2018/239/?time=349) (video)

## Guides and Games for Flex and Grid and Media Queries

Flex:

* https://css-tricks.com/snippets/css/a-guide-to-flexbox/
* https://juliansci.github.io/css-flexbox-simulator/
* https://flexboxfroggy.com/

Grid:

* https://cssgridgarden.com/
* https://css-tricks.com/snippets/css/complete-guide-grid/

Media Queries:

* https://css-tricks.com/a-complete-guide-to-css-media-queries/
* https://css-tricks.com/snippets/css/media-queries-for-standard-devices/
* http://cssmediaqueries.com/overview.html
* https://ui.dev/rwd/articles/why-you-dont-need-device-specific-breakpoints

## Accessibility

* [contrast ratio](https://contrast-ratio.com/)
* [Contrast Checker](https://contrastchecker.com/)
* [Web Accessibility Guidelines v1.0 — Contrast & Color](http://web-accessibility.carnegiemuseums.org/design/color/) — has some colour examples

## "Advanced" topics

Dialogs [sic]:

* [`<dialog>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog)
* [HTMLDialogElement.showModal()](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDialogElement/showModal)
* [::backdrop pseudo-element for dialogs](https://developer.mozilla.org/en-US/docs/Web/CSS/::backdrop)
* [Can I use showModel](https://caniuse.com/?search=showModal)

## Questions

### Should I use literate unicode characters or entities?

In Summary: enter them directly.

* [HTML5: which is better - using a character entity vs using a character directly?](https://stackoverflow.com/questions/9808098/html5-which-is-better-using-a-character-entity-vs-using-a-character-directly)
* [Google HTML Style Guide](https://google.github.io/styleguide/htmlcssguide.html#Entity_References)
* [The q element](https://html.spec.whatwg.org/multipage/text-level-semantics.html#the-q-element) (whatwg spec)

Some lists of entities:

* [Common HTML entities used for typography](https://www.w3.org/wiki/Common_HTML_entities_used_for_typography) (w3c)
* [HTML codes and HTML special characters: The complete list](https://psdtowp.net/html-codes-special-characters.html) — very comprehensive list, especially covering languages

### How does margin collapsing work?

And how to avoid it?

* [CSS margin terror; Margin adds space outside parent element](https://stackoverflow.com/questions/13573653/css-margin-terror-margin-adds-space-outside-parent-element/42069793)
* [Everything You Need To Know About CSS Margins](https://www.smashingmagazine.com/2019/07/margins-in-css/) (Smashing magazine)

### How do I consistently style form input elements?

* [Advanced form styling](https://developer.mozilla.org/en-US/docs/Learn/Forms/Advanced_form_styling)

### What is BEM, and why?

* https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/
* https://www.smashingmagazine.com/2014/07/bem-methodology-for-small-projects/

### What order should CSS rules be in?

* https://9elements.com/css-rule-order/
* http://web.simmons.edu/~grabiner/comm244/weekfour/css-concepts.html
* https://css-tricks.com/precedence-css-order-css-matters/

