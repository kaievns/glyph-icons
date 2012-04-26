# Glyph-Icons

This little package provides the [glyphicons](http://glyphicons.com) drop in styles.

## Usage

Just hook up this package in any standard way on your page and it will automatically add icons
to your links with classes `add`, `edit`, `delete`, etc.

    :html
    <html>
      <head>
        <script src="http://cdn.lovely.io/core-1.1.0.js"></script>
        <script type="text/javascript">
          Lovely(['glyph-icons-1.0.0'], function() {})
        </script>
      </head>
      <body>
        <a href="..." class="new">Create new</a>
        <a href="..." class="edit">Edit</a>
        <a href="..." class="delete">Delete</a>
        <a href="..." class="search">Search</a>
      </body>
    </html>

See the live demo page for the complete list of supported classes


## NOTE!

[Glyphicons](http://glyphicons.com) is a commercial product. They allow you to use the icons
under the [creative commons license](http://creativecommons.org/licenses/by-nd/3.0/) for free,
but if you're using this package in a commercial application, please go to the glyphicons site
and give the author $25. He totally deserves it.


## Copyright And License

This project is released under the terms of the MIT license

Copyright (C) 2012 Nikolay Nemshilov