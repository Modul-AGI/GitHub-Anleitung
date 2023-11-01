

These screenshots were created with the following environment:

- Screen: Built it laptop screen 
- Browser: Firefox, zoomed to 150%
- Ubuntu Screenshot utility, screenshot type "Screen"

Using ImageMagick, the top of the screenshot was cropped with the following command:

```
find images/*.png -exec convert {} -gravity North -chop 0x25 {} \;
```