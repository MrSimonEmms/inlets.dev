## inlets.dev homepage

[![Netlify Status](https://api.netlify.com/api/v1/badges/fd9c25fb-865c-481e-adcf-90f6a0a7a0cc/deploy-status)](https://app.netlify.com/sites/inlets-dev/deploys)

## Adding a new blog post

* Create an issue and propose the topic. Wait for approval before contributing.

* Create a new YAML file in `blog/_posts` - see [this example](https://github.com/alexellis/inlets.dev/blob/master/blog/_posts/2020-10-29-preparing-docker-hub-rate-limits.md) for how to set the post title and description.

* Prefix it with the date.

* Add images to `/images/` - resize all images to < 200-300KB.

* Raise a Pull Request

If you use any copyrighted material such as text, code, or images, then you must credit the author.

## Usage

## Initial installation

You will need node.js in order to install yarn:

```bash
$ npm i -g yarn
```

You may need to run `brew install/upgrade ruby` if the `bundle` command is unavailable.

If it's still unavailable run:

```bash
$ gem install bundle
```

When you have the tools in place run:

```bash
$ bundle install
$ yarn install

$ yarn run tailwind init _includes/tailwind.config.js
```

### To start a preview, simply run:

```bash
bundle exec jekyll serve
```

Access the site at: http://127.0.0.1:4000/
