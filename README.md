![github-wide](https://user-images.githubusercontent.com/98681/53048332-597afc80-3449-11e9-899d-e1897031e70e.png)


# Wide GitHub

Userstyle for making all of GitHub completely fluid.

### Why

Well, we just shipped split diffs—hell yeah!—and now only part of the site is fluid. This makes it all fluid with just a bunch of CSS.

### Disclaimer

I work at GitHub. This repo comes with absolutely no promise of an official full-width interface GitHub. No such project is under way, and as you'll find with this userstyle, it's not as simple as just adding more CSS. That said, enjoy!

### How to use

Install a userstyle manager for your favorite browser:

#### Stylus
Website: [stylus](http://add0n.com/stylus.html)
* Chrome: https://chrome.google.com/webstore/detail/clngdbkpkpeebahjckkjfobafhncgmne
* Firefox: https://addons.mozilla.org/firefox/addon/styl-us/
* Opera: https://addons.opera.com/extensions/details/stylus/


#### Stylish
> Due to privacy concerns (extension has permission to all your browser data) Stylus is recommended.

Website: [userstyles.org](http://userstyles.org)
* Chrome: *currently not available* (checked 2018-07-19)
* Firefox: https://addons.mozilla.org/firefox/addon/stylish/ (be sure to place the CSS inside the `@-moz-document domain("github.com")` block)
* Opera: *currently not available* (checked 2018-07-19)

#### Other
* Safari: http://code.grid.in.th/

Then, copy-pasta the styles from `github-wide.css` into a new userstyle. Be sure to specify that it apply to sites beginning with `https://github.com/*`.

In addition, you can apply styles from `gist-wide.css` to sites beginning with `https://gist.github.com/*`.

#### Userstyles.org

If you use the Stylus (or Stylish) addon you can find one-click installs including automatic updates via the packages below.

* [GitHub Wide](https://userstyles.org/styles/108591/github-wide)
* [GitHub Gist Wide](https://userstyles.org/styles/108592/github-gist-wide)

### Bug reports

Open an issue or submit a pull request, please.

### <3

Licensed under [MIT](LICENSE) and copyright [@mdo](https://twitter.com/mdo).
