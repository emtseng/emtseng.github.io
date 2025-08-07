# Build repo for personal website

## Config

To set up on a new machine, install Jekyll via: https://jekyllrb.com/docs/installation/macos/. Then run:

```cli
bundle install
```

Once set up:

```cli
bundle exec jekyll serve --livereload # for development
bundle exec jekyll build # for one-time builds
```

Prepending bundle exec scopes to this Gemfile's dependencies vs. global Ruby.

## Updates

Styling is in `_sass/minima/_custom.scss`
