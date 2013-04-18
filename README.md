My project template with `coffee-script`, `sass`, `slim`.
---

This uses `guard` and `sprockets` for release a product automatically:

* `coffee-script` to `javascript`
* `sass` to `css`
* `slim` to `html`

It contains `twitter-bootstrap` and `jQuery` mainly because I use them. Remove them if you don't need.

# Setup

    bundle install
    guard

It  monitors `src` folder and generate files into `public` folder.

You can also generate files manually with `rake` command:

    bundle install
    rake

# Test Server

To start web server, `rack` is available:

    rackup

Or, with `-p` option for specifying the port:

    rackup -p <port>

Modify `config.ru` if needed.

# Goal

* Enable to use on Linux, OS X and Windows(Cygwin).
* Easy to change some template engines. (cf. Sass -> Compass)

