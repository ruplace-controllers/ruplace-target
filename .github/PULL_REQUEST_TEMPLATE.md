To request changes to the target image, create a PNG file with a transparent background,
which includes *only* the additional feature to add. This image should be saved as
`pr_<feature_name>.png`.

To make pixels which were previously opaque be transparent, colour them dark red, a
colour not present in the normal palette:
![#800000](https://placehold.it/15/800000/000000?text=+) `#800000`.

The image should be the same size as the existing image so that they can be easily
combined, and should only include:
- Colours from the palette
- Transparent
- Half-intensity red

Please include an enlarged view of the overlay, and the combined image in the text
of the PR.
