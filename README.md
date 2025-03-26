# Minimalistic one-page theme for Hugo - [Demo](https://ctrl-alt-gg.hu/)

An ultra lightweight one-page theme for Hugo. Responsive elements are produced with bare HTML and CSS.

Forked from <https://github.com/17ms/yuan>

## Features

- Interactive design without JavaScript
- SVG icon pack for social links
- Mobile friendly scaling

## Usage

The easiest way to install the theme is to use git submodules:

```shell
$ git submodule add --depth=1 https://github.com/marcsello/yuan2.git themes/yuan2
# Required when recloning the repository (e.g. during automated deployment)
$ git submodule update --init --recursive
```

Use the `hugo.yaml` template below to configure the theme:

```yaml
# Note that due to performance reasons the custom webfont used in the site's
# titles is stripped to only contain unicode range U+0000-007F

baseURL: https://example.com/
title: Example
author: Example Author
language: en-GB
paginate: 10

theme: yuan2

params:
  assets:
    logo: "logo.svg"

```
