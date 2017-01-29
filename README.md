# swiftpage-docs <sub><sup>| SwifPage Installation Guides</sup></sub>

This site is based on [Jekyll](http://jekyllrb.com/), with a dash of [Twitter Bootstrap](http://themes.getbootstrap.com/products/dashboard) added.

Requirements

Installing Jekyll is easy and straight-forward, but there are a few requirements you’ll need to make sure your system has before you start.

* [Ruby](https://www.ruby-lang.org/en/downloads/) (including development headers, v1.9.3 or above for Jekyll 2 and v2 or above for Jekyll 3)
* [RubyGems](https://rubygems.org/pages/download)
* Linux, Unix, or macOS
* [NodeJS](https://nodejs.org/), or another JavaScript runtime (Jekyll 2 and earlier, for CoffeeScript support).
* [Python 2.7](https://www.python.org/downloads/) (for Jekyll 2 and earlier)

The master branch is continuously deployed to production.

_Please_, feel free to make any contributions you feel will make Cloud Elements Documentation better.

**Submit all pull requests to the master branch**

## Installation

```bash
$ git clone git@github.com:cloud-elements/devportal.git
$ cd swiftpage-docs
$ sudo gem install jekyll redcarpet
```

## Usage

```bash
$ jekyll serve
```

Now browse to [http://127.0.0.1:4000/](http://127.0.0.1:4000/) and code away!

## Site Structure

Service Docs will be placed in their respective folder, e.g. Shopify.
The Service Docs are structured in the following way:

```bash
|-- root
  |-- docs
    |-- services
      |-- service folder (e.g. Shopify)
        |-- service specific docs (e.g. endpoint setup)
```
## Conventions

All documents are composed in markdown.  HTML can be used right in the markdown docs.

### Pages

You can write pages in markdown, HTML, or HAML. They all get converted to HTML when the site is generated.

The site uses the Redcarpet Markdown Syntax
[View Cheatsheet](https://caleorourke.gitbooks.io/redcarpet-syntax/content/cheatsheet/index.html)

Pages have a block of YAML at the top that sets a few options. They are pretty self explanatory; here's an example of an Element YAML:

```
---
heading: BigCommerce
title: Endpoint Setup
layout: docs
breadcrumbs: /index.html
parent: Back to Guides
order: 2
---
```

## License
(The MIT License)

Copyright © 2012-2017 Cloud Elements Inc [http://cloud-elements.com/](http://cloud-elements.com/).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
