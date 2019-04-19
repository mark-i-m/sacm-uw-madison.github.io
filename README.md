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

This will start a server listening at some port on localhost, which will continually rebuild the website as long as you edit. This server should only be used for testing.

## Deploying

Jekyll is a static site generator. You only need to build the website and then put it where a server (e.g. nginx or Apache) can find it. To build the website:

```console
> PATH=$PATH:~/.gem/ruby/2.5.0/bin/ bundle exec jekyll b -d ~sacm/public/html-www/
```

where `~sacm/public/html-www/` is the location to deploy the website too. You may also need to edit the `baseurl` setting in `_config.yml`.
