# Browser Compatibility

[https://caniuse.com](https://caniuse.com) <!-- .element: class="fragment" -->

[Flexbugs Repo](https://github.com/philipwalton/flexbugs) <!-- .element: class="fragment" -->

IE10: flex-shrink default is 0, rather than 1 <!-- .element: class="fragment" -->

certain elements like button or fieldset cannot be made flex containers <!-- .element: class="fragment" -->

<p>use [autoprefixer](https://github.com/postcss/autoprefixer) for your css</p> <!-- .element: class="fragment" -->

Note:
- Can I use is great for showing compatibility for web features
- There are several small edge case issues for browsers, listed on the Flexbugs repo
- Flexbugs offers work arounds for issues
- When supporting older browsers, it's best to be explicit with values