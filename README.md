# faster-image-gif
A copy of the `src/image/gif` folder from my Go fork (where the main addition is `EncodeMultiThreaded`). This function is significantly quicker at the cost of a small amount more RAM usage. This repository was made for a number of reasons:
- Allowing for a easy to use package which I can import in software which I am working on now.
- Saves me having to wait for my [PR to be reviewed](https://github.com/golang/go/pull/39527), which could be a while due to this being a code freeze period.
- Allows for easily done external benchmarks.
Please note pull requests will NOT be accepted to this repository. They should be done to [golang/go](https://github.com/golang/go).
