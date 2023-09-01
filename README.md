# QR-CODE-GENERATOR

HTML Structure
<!DOCTYPE html>: Declares the document type and version of HTML being used.

<html lang="en">: The opening tag for the HTML document, specifying the language as English.

<head>: Contains metadata and links to external resources.

<meta charset="UTF-8">: Sets the character encoding of the document to UTF-8.
<meta http-equiv="X-UA-Compatible" content="IE=edge">: Specifies compatibility settings for Internet Explorer.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport configuration for responsive design.
<title>Qr Code Generator</title>: Sets the title of the web page.
<link>: Loads the "Ubuntu" font from Google Fonts.
<link rel="stylesheet" href="./style.css">: Links an external CSS stylesheet named "style.css."
<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>: Imports the QR code generation library from a Content Delivery Network (CDN).
<body>: Contains the content of the web page.

<div class="header">: Defines a header section for the web page.

<div class="box">: A container for the content within the header.
<h1>QR Code Generator</h1>: A heading displaying the title of the page.
<hr />: A horizontal line element for visual separation.
<div class="sqrcode"></div>: An empty <div> element for displaying QR codes.
<div class="qrcode"></div>: Another empty <div> element for displaying QR codes.
<input type="text" placeholder="Paste an URL or enter text, then press enter" onchange="generateQr()">: An input field for entering text or a URL, with an onchange event handler that triggers the generateQr() function when the input value changes.
<script src="script.js"></script>: Imports an external JavaScript file named "script.js" for additional functionality.

CSS (style.css)
The CSS code defines styles for various HTML elements within the page.
It includes styling for the background, header, text, input field, buttons, and QR code containers.
JavaScript (script.js)
The JavaScript code initializes a QRCode object and attaches it to an element with the class "qrcode."
It generates a default QR code with the message "Why did you scanned me?" when the page loads.
The generateQr() function is defined to generate a QR code based on the input value provided by the user.






