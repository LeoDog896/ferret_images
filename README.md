# Ferret Images

Collection of various ferret images for use with the [ferret_api](https://github.com/LeoDog896/ferret_api).

## Contributing

- All contributed images will be transformed to a JPG under 300kb, as standard with [dog.ceo's image collection](https://github.com/jigsawpieces/dog-api-images).
- Ensure your photos are of a good quality and the ferret is easily identifiable in the photo
- Ensure your photo features one ferret only (although additional ferrets can be in the background)
- Photos must not represent any human, even human body parts; it's illegal in most states of the world

### How to contribute images

Make an issue submission: [Ferret Submission Form](https://github.com/LeoDog896/ferret_images/issues/new?assignees=LeoDog896&labels=submission&template=SUBMIT.yml&title=%5BSubmission%5D%3A+).

### How to contribute in other ways

Many images need "tagging"! Being able to make alt descriptions, add patterns and colors for ferrets, or more, can help give this repository rich information and descriptions for ferrets, as well as making it accessible!

### How to contribute (developer)

Use the [`ferret_api`](https://github.com/LeoDog896/ferret_api) repository instead. The `ferret_images` repository is available as a submodule that you can contribute to by using the `ferret_image` CLI. More information is available in the other repository.

## Layout

`/collection/<uuid>`:
- `image.json` - metadata for the ferret image
- `image.jpg` - the actual image itself
