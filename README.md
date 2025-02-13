# Bilder umwandeln mit ImageMagick

Um ein Bild auf **4 Graustufen** zu reduzieren und auf die Auflösung deines Displays anzupassen, benutze den folgenden Befehl:

```bash
magick input.jpg -resize 400x300 -colorspace Gray -dither FloydSteinberg -colors 4 image.bmp
