# Why does this exist?

Lately while doing experiments I have noticed some pre-trained models to be hosted on S3. These dependencies are easy to break as its on an S3 instance hosted by someone who might accidently change the settings, move files or due to some unseen incident make the files unaccessible.

This repo is meant to upload binary models as a Github release for such models.

Focussed only for Torch models to keep the # of releases maintainable.

Make a PR if you want to add a new model.

## License

MIT