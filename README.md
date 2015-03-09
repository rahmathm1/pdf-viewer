
# &lt;pdf-viewer&gt;

Implementation of PDF viewer web component using PDF.JS from Mozila. 

> Maintained by [Rahmathullah](https://github.com/rahmathm1).

## Demo

> [Check it live](http://rahmathm1.github.io/pdf-viewer).

## Usage

1. Import Web Components.js:

	```html
	<script src="/webcomponents.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/pdf-viewer.html">
	```

3. Start using it!

	```html
	<pdf-viewer id="my_pdf_viewer" path="path/to/your/pdf/here.pdf"></pdf-viewer>
	```

## Options

|   Attribute   | Options  |                      Description                      |
| ------------- | -------- | ----------------------------------------------------- |
| `path`    	| *string* | Path to the pdf to be rendered                        |

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)