# Static assets

This repo contains various static assets (i.e.: image, fonts, javascript, css) for apps and websites.

# Image conversions:

### .png to .webp

> find . -name '\*.png' | xargs -I% cwebp -m 6 -q 90 % -o %.webp
