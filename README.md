# &lt;google-doc&gt;

A web component to import Google Doc content into a webpage.

See the [component page](http://gnestor.github.io/google-doc) for more information.

## Usage
`<google-doc key="1dOEs7hBddMhZsuOGJ7J8ku5FhYdD2Ox_iZo-v23j_Ho"></google-doc>`

## Properties
`<google-doc key="1dOEs7hBddMhZsuOGJ7J8ku5FhYdD2Ox_iZo-v23j_Ho" selector="img" styles></google-doc>`
#### key
The key of the Google Doc that can be found in the URL after "https://docs.google.com/document/d/" and before "/edit."

*Note that the Google Doc must be published. To publish a document, go to File > Publish to the web... > Publish.*

#### selector
A [selector or selectors](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_Started/Selectors) (uses [querySelectorAll](https://developer.mozilla.org/en-US/docs/Web/API/Element/querySelectorAll)) to select only specific elements from your document (e.g. images).

#### styles
Include to preserve styles from document (defaults to false).

## Demo
[http://gnestor.github.io/google-doc/components/google-doc/demo.html](http://gnestor.github.io/google-doc/components/google-doc/demo.html)

## Install

This web component requires [Polymer](http://www.polymer-project.org).

1. Install google-doc component `bower install google-doc`
2. Import Polymer script `<script src="/bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>` then google-doc component `<link rel="import" href="bower_components/google-doc/google-doc.html" />`
3. Use `<google-doc key="<GOOGLE_DOC_KEY>"></google-doc>` element
