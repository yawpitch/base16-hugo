# base16-hugo
[Base 16](http://chriskempson.com/projects/base16/) templates for static sites built with [Hugo](https://gohugo.io/).

## Getting started

First you'll need to [configure Hugo's Chroma syntax highlighter](https://gohugo.io/content-management/syntax-highlighting/#configure-syntax-highlighter) to add classes to the generated HTML for your site.

```toml
# config.toml
pygmentsUseClasses = true
```

Once classes are enabled you'll need download or copy one of the pre-built `hugo-base16-css/*.css` files and incorporate it into your site. This is an ideal use for [Hugo Pipes](https://gohugo.io/hugo-pipes/), as you can use the [SASS/SCSS](https://gohugo.io/hugo-pipes/scss-sass/) pipe to incorporate and minify the styling CSS for you. Once you've got a pipeline working trying out different Base16 themes is as simple as overwriting a file in the **assets** directory and letting `hugo server` do the rest.

The template has been designed to generate the CSS in the same form that [Hugo can generate](https://gohugo.io/content-management/syntax-highlighting/#generate-syntax-highlighter-css), so modifiying the CSS for your own needs should be fairly easy.
