# my-first-web-component

## Running the web component

1. There are no dependencies, these are native web components!

2. Open the `index.html` file in a [browser that supports web components](https://caniuse.com/#search=components), like Chrome

## Implementing the web component

1. Import the web component in the document `<head>` with:

    `<link rel="import" href="verification-input.html">`

2. Then use the web component anywhere in the page with:

   `<x-verification-input id="[ID]"></x-verification-input>`

   where `[ID]` is a unique ID, or leave off the `id` attribute entirely.

## Web component methods

* `getCode()` - returns the current value

   Example: `document.getElementById([ID]).getCode();`

* `setCode([NUMBER])` - customElements the current value

   Example: `document.getElementById([ID]).setCode(123456);`

* `clearCode()` - returns the current value

   Example: `document.getElementById([ID]).clearCode();`
