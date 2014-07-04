#A Generic HTML5 Template

Basic boilerplate markup (blank HTML document template) for practical HTML5-capable web pages.

- `html5-template.html` contains copy-pasta starter markup to be placed in a blank HTML document
- `/commented-version` contains an HTML document with the same markup, but this version has explainer comments

## Documentation
You can read about this boilerplate in greater detail on Six Revisions: [A Generic HTML5 Template](http://sixrevisions.com/html5/html5-template/)

## How to Use
Copy and paste the following into a blank HTML document, fill in the blanks, and modify as needed:

```
<!DOCTYPE html>
<head>
<title></title>
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta charset="utf-8">
<meta name="description" content="">
<meta name="author" content="">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="">
<!--[if lt IE 9]>
<script src="//cdn.jsdelivr.net/html5shiv/3.7.2/html5shiv.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/respond.js/1.4.2/respond.min.js"></script>
<![endif]-->
<link rel="shortcut icon" href="">
</head>
<body>
<!-- Place your content here -->
<!-- SCRIPTS -->
<!-- Example: <script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script> -->
</body>
</html>
```

## Browser Support
- IE 9 and older are supported by the use of a conditional comment that loads [html5shiv](https://github.com/aFarkas/html5shiv) and [Respond.js](https://github.com/scottjehl/Respond) for support of new HTML5 elements and media queries (served through jsDelivr and cdnjs.com public CDNs respectively)
- Mobile browsers are instructed to render the layout using `width=device-width` and `initial-scale=1`

## License: Public Domain Dedication
The source code excluding the references to external scripts is in the public domain using the [CC0 1.0](https://github.com/sixrevisions/html5-template/blob/master/LICENSE.md).
