# Numpy.org

[![Netlify Status](https://api.netlify.com/api/v1/badges/efd504a5-56ff-4f46-8a51-b6d4bb338c59/deploy-status)](https://app.netlify.com/sites/numpy/deploys)

## Getting Started

To contribute to the website, you'll first need to install the *extended
version* of Hugo.

The Hugo [install page](https://gohugo.io/getting-started/installing/) has
instructions for different platforms and installers; make sure you end up with
the extended version.

On Linux it may be easiest to pick up a tarball of the latest extended version
from the [release page](https://github.com/gohugoio/hugo/releases/) and
install it per https://gohugo.io/getting-started/installing/#install-hugo-from-tarball.

Next, clone this repository, and install the theme:

```bash
git submodule update --init
```

The development web server is started with:

```bash
hugo server
```

or

```bash
hugo server -D
```

to run the hugo server with draft enabled.

after which the site should be served at http://localhost:1313.

You'll see

```bash
error: failed to transform resource: TOCSS: failed to transform "style.sass"
```

if you don't have the Hugo extended version.


## User Experience (UX)

### NumPy Color Palette

![#013243 Warm Black](./static/images/content_images/swatch_013243_warm_black.png) `#013243` **Warm Black**

![#4D77CF Han Blue](./static/images/content_images/swatch_4D77CF_han_blue.png) `#4D77CF` **Han Blue**

![#4DABCF Maximum Blue](./static/images/content_images/swatch_4DABCF_maximum_blue.png) `#4DABCF` **Maximum Blue**

![#6C7A89 Aurometalsaurus](./static/images/content_images/swatch_6C7A89_aurometalsaurus.png) `#6C7A89` **Aurometalsaurus**

![#EEEEEE Isabelline](./static/images/content_images/swatch_EEEEEE_isabelline.png) `#EEEEEE` **Isabelline**

![#FFC553 Mustard](./static/images/content_images/swatch_FFC553_mustard.png) `#FFC553` **Mustard**

![#FFFFFF White](./static/images/content_images/swatch_FFFFFF_white.png) `#FFFFFF` **White**

## Deployment

Submit pull requests first, those get run on [Netlify](https://quansight-labs.netlify.app/) and you can see a build preview by clicking on the `details` link at the bottom.

![Build previews](images/readme-build-previews.png)
