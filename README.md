# Notes

Resize Images:

```sh
mkdir _resized
find . -maxdepth 1 -iname "*.jpg" | xargs -L1 -I{} convert -resize 1200x800 "{}" _resized/"{}"
```

Run
```sh
RUBYOPT="-W0" bundle exec jekyll serve
```
