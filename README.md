Added the `padding` option which adds paddings directly to the image file.
The padding are sized based on the real row/column block size.

By default `padding: 3` is used.

See `index.html` for an example with a padded QR code!

```javascript
let qrcode = new QRCode(document.getElementById("qrcode"), {
	width: 256,
	height: 256,
	padding: 3
});
```
