# sitemap-generator

Sitemap Generator is a python script which will generate an xml Sitemap for your web site.

## Overview

The **sitemap_gen.py** script analyzes your web server and generates one or more Sitemap files. These files are XML listings of content you make available on your web server. The files can be directly submitted to search engines as hints for the search engine web crawlers as they index your web site. This can result in better coverage of your web content in search engine indices, and less of your bandwidth spent doing it.

The **sitemap_gen.py** script is written in *Python 2.2* and released to the open source community for continuous improvements.

## How to use it ?

```python
"""A simple script to automatically produce sitemaps for a webserver, in the Google Sitemap Protocol (GSP).

Usage: python sitemap_gen.py --config=config.xml [--help] [--testing]
            --config=config.xml, specifies config file location
            --help, displays usage message
            --testing, specified when user is experimenting
"""
```

## Example

Generate your site map file from your website config file.

```bash
$ python sitemap_gen.py --config=/var/www/yourwebsite.com/sitemap_config.xml
```

## Note

This project is a fork of [Google Sitemap Generator](http://goog-sitemapgen.sourceforge.net/).
It has been forked and moved to Github to that it can continue to evolve.

## License ([BSD](https://github.com/rimiti/keldoc-js-sdk/blob/master/LICENSE))

- [Dimitri DO BAIRRO](https://github.com/rimiti)
- [Google](opensource@google.com)

