StaticStrap
====


StaticStrap is a collection of tools designed to make getting started with a static site/dynamic front-end application quick and easy.

Features
---

* Uses [Sprockets](https://github.com/sstephenson/sprockets). Sprockets supports 'requiring' assets to bundle them into compiled javascript and css files, as well as supporting a number of precompilers ([LESS](http://lesscss.org) and [Coffeescript](http://coffeescript.org) are supported out of the box)
* Has cleanly organized assets - your application's files live in `assets/javascripts`, `assets/stylesheets`, etc., and any libraries you use live in `vendor/javascripts`, etc.
* Comes with Guard - already set up to watch asset directories for changes, and automatically compile stylesheets and javascripts.

Getting Started
---

1. Clone the repository, or [download a copy](https://github.com/joshmcarthur/staticstrap/downloads)
2. Install dependencies: `bundle install` (Requires Ruby)
3. Run Guard, and start changing assets!: `bundle exec guard`
4. Open `index.html` in your web browser!

Credits
---

Based on [Mobile Boilerplate](http://html5boilerplate.com/mobile/) - I cannot possibly take credit for all the awesome work the team there do making a great, performant and well-documented boilerplate. See the `docs/` folder for detailed information on Mobile Boilerplate features.

License
--- 

See **LICENSE.md** for license information - need to know quickly? Everything's [MIT](http://opensource.org/licenses/MIT).