# Ferret Images

Collection of ferret images

## Contributing

- All contributed images will be transformed to a JPG under 300kb, as standard with [dog.ceo's image collection](https://github.com/jigsawpieces/dog-api-images).
- Ensure your photos are of a good quality and the ferret is easily identifiable in the photo
- Ensure your photo features one ferret only (although additional ferrets can be in the background)
- Photos must not represent any human, even human body parts; it's illegal in most states of the world

### How to contribute (not a developer)

First, make a folder with a random UUID: [this website generates them for you](https://leodog896.github.io/doke/uuid).

Then, upload your image to that folder, and rename it to `image.jpg`.
If you want to say anything about the ferret, feel free to leave it in the description in the PR, and a contributor will transform it into metadata for you.

### How to contribute (developer)

You can use the `ferret_image_cli` to use an interactive builder for adding ferret images.

## Layout

`/collection/<uuid>`:
- `image.json` - metadata for the ferret image
- `image.jpg` - the actual image itself
