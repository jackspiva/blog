<h1 align="center">
  My Personal Blog
</h1>

<h4 align="center">
  A blog built using <a href="https://github.com/gatsbyjs/gatsby" target="_blank">Gatsby</a> based on the Gatsby starter <a href="https://github.com/alxshelepenok/gatsby-starter-lumen">Lumen</a>.
</h4>

## Table of contents

- [Introduction]
- [Features](http://github.com/jackspiva/blog#features)
- [To Develop](http://github.com/jackspiva/blog#accesslocally)
- [Folder Structure](http://github.com/jackspiva/blog#folder-structure)
- [Related](http://github.com/jackspiva/blog#related)
- [License](http://github.com/jackspiva/blog#license)

## Features

- [Lost Grid](http://lostgrid.org).
- [Modern font stack](https://bitsofco.de/the-new-system-font-stack).
- Beautiful typography inspired by [matejlatin/Gutenberg](https://github.com/matejlatin/Gutenberg).
- Syntax highlighting in code blocks using [PrismJS](http://prismjs.com).
- [Mobile-First](https://medium.com/@mrmrs_/mobile-first-css-48bc4cc3f60f) approach in development.
- Archive organized by tags and categories.
- Pagination support.
- [Netlify CMS](https://www.netlifycms.org) support.
- Google Analytics.
- Disqus Comments.
- [Flow](https://flow.org/) static type checking.

## To Develop

Navigate into your the blog's directory and start it up.

```sh
cd blog
gatsby develop
```

## Folder Structure

```
└── content
    ├── pages
    └── posts
└── static
    ├── admin
    └── media
└── src
    ├── assets
    │   └── scss
    │       ├── base
    │       └── mixins
    ├── cms
    │   └── preview-templates
    ├── components
    │   ├── Feed
    │   ├── Icon
    │   ├── Layout
    │   ├── Page
    │   ├── Pagination
    │   ├── Post
    │   │   ├── Author
    │   │   ├── Comments
    │   │   ├── Content
    │   │   ├── Meta
    │   │   └── Tags
    │   └── Sidebar
    │       ├── Author
    │       ├── Contacts
    │       ├── Copyright
    │       └── Menu
    ├── constants
    ├── templates
    └── utils

```

## Related

[Statinamic port](https://github.com/thangngoc89/statinamic-theme-lumen) by [Khoa Nguyen](https://github.com/thangngoc89)

## License

The MIT License (MIT)

Copyright (c) 2016-2019 Alexander Shelepenok

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
