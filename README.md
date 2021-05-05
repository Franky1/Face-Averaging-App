# Face-Averaging-App

Face Averaging using OpenCV and Streamlit

> forked from original Github repository to clean up the project

## Improvements

- linting
- sorting imports
- removed conda
- added `requirements.txt`
- added `Dockerfile`
- added `docker-compose.yml`
- fixed bug with text input
- changed pip package to `dlib-bin`

## pip packages

> The trick was to change `dlib` to `dlib-bin` package.

Currently these packages are in the `requirements.txt` file:

```txt
numpy
Pillow
opencv-python-headless
dlib-bin
streamlit
```

## apt packages

Currently no `packages.txt` file is needed.
