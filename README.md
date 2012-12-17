# CORS Component

The CORS is a componente that allows cross-domain communication from the browser. The modern browsers like Chrome, Firefox, Opera, Safari and Internet Explorer 10 use the XmlHttpRequest2 object. IE8+ uses the similar XDomainRequest object, which works in the same way as its XmlHttpRequest.

It's cross-broswer compatible:
- Chrome 3+
- Firefox 3.5+
- Opera 12+
- Safari 4+
- Internet Explorer 8+

See the complete list of supported browsers at http://caniuse.com/cors

## Installation

	$ component install pazguille/CORS

See: [https://github.com/component/component](https://github.com/component/component)

## How-to
```js
cors.get({
	'url': 'http://api.site.com/search?query=ps3',
	'credentials': true,
	'success': function (data) {
		// Code here!
	},
	'error': function () {
		// Code here!
	}
});

// or

cors.get('http://api.site.com/search?query=ps3', function (data) {
	// Code here!
});
```

## API
- WIP

### Events
- WIP

## Contact
- Guille Paz (Frontend developer - JavaScript developer | Web standards lover)
- E-mail: [guille87paz@gmail.com](mailto:guille87paz@gmail.com)
- Twitter: [@pazguille](http://twitter.com/pazguille)
- Web: [http://pazguille.me](http://pazguille.me)

## License
### The MIT License
Copyright (c) 2012 [@pazguille](http://twitter.com/pazguille)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
