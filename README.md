## What is Tumblyzer?

Tumblyzer is a test and validation harness for creating [Tumblr themes](http://www.tumblr.com/docs/custom_themes "Creating a custom HTML theme | Tumblr").

## Is Tumblyzer for me?

Tumblyzer is intended for website designers who want to produce Tumblr themes. It will help you makes themes that produce valid, semantically-meaningful HTML. You do _not_ need to know much, if anything, about programming. But you'll have to dork out a little: Tumblyzer works on the command line, not in one of those fancy-pants _windows_ with their shiny _buttons_.

## How do I get Tumblyzer?

If you're on Mac with OS X 10.5 or above, congrats &mdash; you have basically everything you need already installed. If you're on Windows or Unix, you'll need to install [Ruby](http://www.ruby-lang.org/en/ "Ruby Programming Language") and [RubyGems](http://rubygems.org/ "RubyGems -- your guide to packaging bliss"). Once you're done with that, ask yourself: "self, how well do you know Git?".

### "What's Git?"

1. Download the project as a
   [tarball](http://github.com/gcnovus/Tumblyzer/tarball/master "latest Tumblyzer Tarball from GitHub") or
   [ZIP archive](http://github.com/gcnovus/Tumblyzer/zipball/master "latest Tumblyzer ZIP archive from GitHub")
1. Unpack the archive to somewhere like
   `/Users/my_username/projects/tumblyzer` (a.k.a. `~/projects/tumblyzer`).
   We'll call this directory "`TUMBLYZER_ROOT`" from now on.
   
### "Not as well as [Scott Chacon](http://github.com/schacon "Scott Chacon on GitHub"), but fine"

## OK, I've got it. Now what?

* Check out the example themes in `TUMBLYZER_ROOT/themes/`
* Open a command prompt and navigate to `TUMBLYZER_ROOT`, then run `rake test`
  to watch all the tests run on all the themes
* Create your own template in `TUMBLYZER_ROOT/themes/` and run `rake test`
  again. Do the tests pass? If you're not as opinionated as us about the
  "right" way to write HTML, try `rake test:bare_minimum`.

## Can I use the themes included in the project?

YES! All themes are licensed under the [Creative Commons Attribution 3.0 license](http://creativecommons.org/licenses/by/3.0/ "Creative Commons &mdash; Attribution 3.0 Generic") license.

## Will you put my theme in the example themes folder?

We'd be glad to have it so long as you license it under the CC-BY license. Oh, and it has to pass _all_ the bare_minimum tests.

## Can I use the project code?

All code (everything that _isn't_ in the `themes/` folder) is licensed under the MIT license. Have at!