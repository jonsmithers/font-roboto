# About

A webapp built with Polymer will probably pull in the
`PolymerElements/font-roboto` bower package which loads external fonts from
"https://fonts.googleapis.com". This doesn't work very well when you want
everything to be self-hosted. This repo can be used to override the
`PolymerElements/font-roboto` package and self-host the roboto fonts.

# How to Use

1. Add `"font-roboto": "https://github.com/jonsmithers/font-roboto.git"` in your `bower.json` file.
2. Run `bower install font-roboto`
3. You should be presented with this prompt:

```
Unable to find a suitable version for font-roboto, please choose one by typing one of the numbers below:
```

Choose the option corresponding to this repo. Now, the roboto font will be self-hosted.

---------------------------

The roboto fonts and stylesheets were downloaded from https://google-webfonts-helper.herokuapp.com.
