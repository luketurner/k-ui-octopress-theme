[Octopress](http://octopress.org/) Theme based on [k-ui.jp](http://k-ui.jp/).

Install
----------------------------------------------------------------

```sh
$ cd octopress-home/.theme
$ git clone git://github.com/kui/k-ui-octopress-theme.git kui
$ cd ..
$ rake install["kui"]
$ rake generate
```

Optional Functions
----------------------------------------------------------------

extra functions to the original theme.

`_config.yml.example` may be of sume help.

### tunbr photos

you can add recent tumblr posts.

add "asides/tumblr_photos.html" to `default_asides` of `_config.yml` as belows 
and configurations about tumbr_post.html.

```yml
default_asides: [ asides/tumblr.html, ... ]
```

```yml
tumblr_user: daftbeats # your domain (daftbeats.tumblr.com -> daftbeats)
tumblr_post_num: 5
```

### github api v3

you can specify a item for sorting repository links, the sort direction and
a repository type to be listed.

add [list-user-repositories params](http://developer.github.com/v3/repos/#list-user-repositories)
to your `_config.yml`

```yml
# github api v3 params
# see http://developer.github.com/v3/repos/#list-user-repositories
github_type: all
github_sort: updated
github_direction: desc
```

Font Licensing
------------------

The Calluna Regular font is used in this template. It can be freely licensed for @font-face use for unlimited page-views. Following is information about the font license used on [luketurner.org](http://luketurner.org). Use of this font on your own site requires (I believe) you to acquire your own license.

	MyFonts Webfont Build ID 2622514, 2013-08-14T11:02:44-0400

	The fonts listed in this notice are subject to the End User License
	Agreement(s) entered into by the website owner. All other parties are 
	explicitly restricted from using the Licensed Webfonts(s).
	
	You may obtain a valid license at the URLs below.
	
	Webfont: Calluna Regular by exljbris
	URL: http://www.myfonts.com/fonts/exljbris/calluna/regular/
	Copyright: &#x00A9; 2009 exljbris Font Foundry. All rights reserved.
	Licensed pageviews: Unlimited
	
	
	License: http://www.myfonts.com/viewlicense?type=web&buildid=2622514
	
	© 2013 MyFonts Inc
