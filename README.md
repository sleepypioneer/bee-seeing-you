# Bee-seeing-you computer vision 🐝

## Start a Jupyter server for notebooks 📓

To spin up a Docker container with Jupiter Notebook, run:

```sh
make dev
```

## Run GoCV count code :stopwatch:

The following script uses the GoCV library to count the number of bees going into the Hive. To run this script you will need to install [GoCV](https://gocv.io/) and the GoCV dependencies.

You also need to download the video file from the google drive and put it in data/video/bee_count.mp4.

```sh
go run ./count_with_gocv.go data/video/bee_count.mp4 800 x 240
```

## Resources

- Counting objects with Python: https://thecleverprogrammer.com/2021/05/11/count-objects-in-image-using-python/
- Neural net for counting bees:
http://matpalm.com/blog/counting_bees/ and the code for this: https://github.com/matpalm/bnn
