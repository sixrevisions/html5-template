#A Generic HTML5 Template

Basic boilerplate markup (blank HTML document template) for practical HTML5-capable web pages.

- `html5-template.html` contains copy-pasta starter markup to be placed in a blank HTML document
- `/commented-version` contains an HTML document with the same markup, but this version has explainer comments

## How to Use
Copy and paste the following into a blank HTML document, fill in the blanks, and modify as needed:

```
&lt;!DOCTYPE html&gt;
&lt;head&gt;
&lt;title&gt;&lt;/title&gt;
&lt;meta charset=&quot;utf-8&quot;&gt;
&lt;meta name=&quot;description&quot; content=&quot;&quot;&gt;
&lt;meta name=&quot;author&quot; content=&quot;&quot;&gt;
&lt;meta http-equiv=&quot;X-UA-Compatible&quot; content=&quot;IE=edge&quot;&gt;
&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1&quot;&gt;
&lt;link rel=&quot;stylesheet&quot; href=&quot;&quot;&gt;
&lt;!--[if lt IE 9]&gt;
&lt;script src=&quot;//cdn.jsdelivr.net/html5shiv/3.7.2/html5shiv.min.js&quot;&gt;&lt;/script&gt;
&lt;script src=&quot;//cdnjs.cloudflare.com/ajax/libs/respond.js/1.4.2/respond.min.js&quot;&gt;&lt;/script&gt;
&lt;![endif]--&gt;
&lt;link rel=&quot;shortcut icon&quot; href=&quot;&quot;&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;!-- Place your content here --&gt;
&lt;!-- SCRIPTS --&gt;
&lt;!-- Example: &lt;script src=&quot;//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js&quot;&gt;&lt;/script&gt; --&gt;
&lt;/body&gt;
&lt;/html&gt;
```

## Browser Support
- IE 9 and older are supported by the use of a conditional comment that loads [html5shiv](https://github.com/aFarkas/html5shiv) and [Respond.js](https://github.com/scottjehl/Respond) for support of new HTML5 elements and media queries (served through jsDelivr and cdnjs.com public CDNs respectively)
- Mobile browsers are instructed to render the layout using `width=device-width` and `initial-scale=1`

You can read about this boilerplate in greater detail on Six Revisions: [A Generic HTML5 Template](http://sixrevisions.com/html5/html5-template/)

## License: Public Domain Dedication
The source code excluding the references to external scripts is in the public domain using the [CC0 1.0](https://github.com/sixrevisions/html5-template/blob/master/LICENSE.md).
