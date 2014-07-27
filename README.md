#A Generic HTML5 Template
Basic boilerplate markup (blank HTML document template) for practical HTML5-capable web pages.

- `html5-template.html` contains copy-pasta starter markup to be placed in a blank HTML document
- `/commented-version` contains an HTML document with the same markup, but this version has explainer comments

## Documentation
You can read about this boilerplate in greater detail on Six Revisions: [A Generic HTML5 Template](http://sixrevisions.com/html5/html5-template/).

## How to Use
### Option 1
```
git clone https://github.com/sixrevisions/html5-template.git /your/local/directory
```

### Option 2
Copy and paste the following into a blank HTML document, fill in the blanks and modify as needed:
```
<!DOCTYPE html>
<html>
<head>
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta charset="utf-8">
<title></title>
<meta name="description" content="">
<meta name="author" content="">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="">
<!--[if lt IE 9]>
<script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.2/html5shiv.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/respond.js/1.4.2/respond.min.js"></script>
<![endif]-->
<link rel="shortcut icon" href="">
</head>
<body>

<!-- Place your content here -->
<a href="http://sixrevisions.com/html5/html5-template/">Read the tutorial</a>

<!-- SCRIPTS -->
<!-- Example: <script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script> -->
</body>
</html>
```

## Browser Support
- Mobile browsers are instructed to render the layout using `width=device-width` and `initial-scale=1`
- IE 9 and above are supported by the use of a conditional comment that loads [html5shiv](https://github.com/aFarkas/html5shiv) and [Respond.js](https://github.com/scottjehl/Respond) for support of new HTML5 elements and media queries

##Some Notes
- The conditional comments for IE 9 support, as well as the example script at the `<!-- SCRIPTS -->` section, uses a public CDN for open source libraries, [cdnjs.com](http://cdnjs.com/) that's sponsored by a reputable CDN provider, CloudFlare.
- At the `<!-- SCRIPTS -->` section, the example script is jQuery 2.x, which doesn't support IE 8 and below. This HTML5 template only accomodates IE 9 and above, so this is an appropriate choice over jQuery 1.x.

## License: Public Domain Dedication
The source code excluding the references to external scripts is in the public domain using the [CC0 1.0](https://github.com/sixrevisions/html5-template/blob/master/LICENSE.md).
