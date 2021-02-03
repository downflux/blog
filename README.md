# blog
Blog front end for DownFlux

## Setup

```bash
git clone git@github.com:downflux/blog.git
git submodule update --init --recursive
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
