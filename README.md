# SACM UW Madison Website

## Dependencies

To hack on the website, you will need to have ruby installed (`sudo apt install ruby-dev`).

The install jekyll (locally, no sudo needed):

```console
> gem install --user-install bundler jekyll
> PATH=$PATH:~/.gem/ruby/2.5.0/bin/ bundle install --path ~/.gem/
```

## Build and serve

```console
> PATH=$PATH:~/.gem/ruby/2.5.0/bin/ bundle exec jekyll serve
```

This will start a server listening at some port on localhost, which will continually rebuild the website as long as you edit.
