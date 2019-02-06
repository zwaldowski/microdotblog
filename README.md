# A Custom Theme for Micro.blog

Live at [waldowski.me](https://waldowski.me). Follow [@zw on Micro.blog](https://micro.blog/zw).

## Features

- Fluid, mobile-first layout
- Fixed sidebar on landscape screens
- Contact links (see below)
- Compatibility with iPhone X and iPad Pro safe areas
- Intended for microblogging with mixed content

### Contact links

The theme contains a contact links section in its header, with:

- Twitter, GitHub, and Instagram links based on the [Apps](https://micro.blog/account/apps) settings on Micro.blog
- Email if you host microcasts with Micro.blog in iTunes
- RSS

Override `config.json` for the theme in Micro.blog to enable additional links for:

- Email (`"params.author.email"`)
- Mastodon (`"params.mastodon_username"`; use the format "`zw@mastodon.social`" without a `@` prefix)
- Facebook (`"params.facebook_username"`; also, ugh)
- LinkedIn (`"params.linkedin_username"`)

## Installation

Read about [Custom Templates](https://www.manton.org/2019/01/30/custom-templates-categories.html) or [watch the screencast](https://www.manton.org/2019/02/04/ive-posted-a.html).

## Credits

Directly forked from [Primrose](http://github.com/microdotblog/theme-primrose) for Micro.blog, itself a port of Garth Braithwaite and Tim Smith's [Microblog with Jekyll](https://github.com/smithtimmytim/jekyll-microblog).

Has some resemblance to my old [GitHub Pages site](http://github.com/zwaldowski/zwaldowski.github.io).
