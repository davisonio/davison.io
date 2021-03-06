# davison.io

> Craig Davison's website @ [davison.io](https://davison.io)

Here's the source code of my website which you can find at [davison.io](https://davison.io).

Blog is powered by [Ghost](https://ghost.org) using the Casper theme. Static pages are generated by [Jekyll](https://jekyllrb.com) and are based on Casper.

Index page is powered by [Carrd](https://carrd.co) and is nginx proxied to be served from davison.io.

Blog theme has a few changes from the default Casper theme, including:
* Font Awesome icons
* RSS link in footer
* No floating header
* No related posts
* Simplified post cards
* Simplified author attribution
* 280 character post card exerpt
* No large post cards
* No larger font on `p:first-child`

## Install

Make sure ruby is installed (ideally using rvm) and then install Jekyll.

```
gem install jekyll
```

To use the blog theme, install in Ghost admin interface.

## Use

```
jekyll build
```

Then configure nginx to point to the `_site` generated directory.

## Credits

**[Craig Davison](https://davison.io)**

[![GitHub](https://img.shields.io/github/followers/davisonio.svg?style=social&label=Follow%20@davisonio)](https://github.com/davisonio) [![Twitter](https://img.shields.io/twitter/follow/davisonio.svg?style=social)](https://twitter.com/davisonio)

...and [contributors](https://github.com/davisonio/davison.io/graphs/contributors).

**[Contributions are welcome!](https://github.com/davisonio/davison.io/blob/master/contributing.md)**

## License

Unless otherwise stated:
- Copyright © 2015+ [Craig Davison](https://davison.io).

Casper theme for Ghost and static page themes based on Casper:
- Copyright © 2013-2019 [Ghost Foundation](https://ghost.org). Licensed under MIT.
