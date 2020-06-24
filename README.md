# Dreptul la Oraș

This is the website of the group _Dreptul la Oraș_ from Timișoara, Romania.
Website hosted at:

- [https://dreptullaoras.com](https://dreptullaoras.com)
- [https://dreptullaorastimisoara.com](https://dreptullaorastimisoara.com)

Find us on [facebook](https://www.facebook.com/dreptullaorasTM)

## For devs

Here be dragons!

### SSL certificate

SSL certificates are currently allowed to be issued by the CAA DNS record are:

- [ssl.com](https://letsencrypt.org/)
- [letsencrypt.org](https://www.ssl.com/)

### On jekyll

Basic structure `.md` header page variables

The following variables will be used to either add (marked `a`) to existing meta properties, or override (marked `o`) them. Possible custom variables:

- `keywords` - `a` - prepends the list of keywords to the page's `meta name="keywords"` html tag
- `image` - `o` - if included then overrides the default image to display in the sharing thumbnails, all properties bellow need to be included to ensure that it displays correctly
  - `url` - the URL relative to the root of this project, prefixed with `/`
  - `width` - the width of this new image
  - `height` - the height of this new image
  - `type` - the type of this new image
