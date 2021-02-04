# blog
Blog front end for DownFlux

## Setup

```bash
git clone git@github.com:downflux/blog.git
git submodule update --init --recursive
```

## Local Build

Sometimes we should install the environment locally to help debug development.

See
https://jekyllrb.com/docs/installation/,
https://jekyllrb.com/docs/ruby-101/

```bash
bundle exec jekyll serve
```

## Submodules

### Add

```bash
git submodule add ${REPO}
```

### Update

```bash
git submodule update --remote --recursive
```

### Remove

See https://stackoverflow.com/a/29850245.

```bash
git submodule deinit ${MODULE}
git rm ${MODULE}
```

## Caveat

Ensure the default branch is set correctly in `.gitmodules`.
