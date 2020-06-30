# WriterJS

WriterJS is a plugin that you can use to add an amazing writing effect to your website.

## Installation

### CSS

Include the CSS file in the `<head>` of your page before your main stylesheet.

```html
	<link rel="stylesheet" href="/src/writer.min.css">	
```

### JS

Include the JS file in the `<body>` of your page.

```html
	<script src="/src/writer.min.js"></script>
```

## Example

Add this tag in your body

```html
	<span class="writer-text" data-sentences="test one <(*)>test two <(*)>test three" data-wait-sentence="3000" data-wait-letter="100"></span>
```

`data-sentences`
Holds all sentences you want to add, seperated by this symbol <(*)>

`data-wait-sentence`
This refers to the amount of time in milliseconds until switching to the next sentence.

`data-wait-letter`
This refers to the speed of typing each letter in milliseconds.