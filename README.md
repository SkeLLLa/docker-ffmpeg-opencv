# docker-opencv

Docker image with ffmpeg and compiled OpenCV library (with ffmpeg support)

# OpenCV

OpenCV is built from source with contrib libraries. Latest git tag corresponds OpenCV version.

## Compile options

```
-D CMAKE_BUILD_TYPE=RELEASE
-D BUILD_DOCS=OFF
-D BUILD_TESTS=OFF
-D BUILD_PERF_TESTS=OFF
-D BUILD_JAVA=OFF
-D BUILD_opencv_apps=OFF
-D BUILD_opencv_aruco=OFF
-D BUILD_opencv_bgsegm=OFF
-D BUILD_opencv_bioinspired=OFF
-D BUILD_opencv_ccalib=OFF
-D BUILD_opencv_datasets=OFF
-D BUILD_opencv_dnn_objdetect=OFF
-D BUILD_opencv_dpm=OFF
-D BUILD_opencv_fuzzy=OFF
-D BUILD_opencv_hfs=OFF
-D BUILD_opencv_java_bindings_generator=OFF
-D BUILD_opencv_js=OFF
-D BUILD_opencv_img_hash=OFF
-D BUILD_opencv_line_descriptor=OFF
-D BUILD_opencv_optflow=OFF
-D BUILD_opencv_phase_unwrapping=OFF
-D BUILD_opencv_python3=OFF
-D BUILD_opencv_python_bindings_generator=OFF
-D BUILD_opencv_reg=OFF
-D BUILD_opencv_rgbd=OFF
-D BUILD_opencv_saliency=OFF
-D BUILD_opencv_shape=OFF
-D BUILD_opencv_stereo=OFF
-D BUILD_opencv_stitching=OFF
-D BUILD_opencv_structured_light=OFF
-D BUILD_opencv_superres=OFF
-D BUILD_opencv_surface_matching=OFF
-D BUILD_opencv_ts=OFF
-D BUILD_opencv_xobjdetect=OFF
-D BUILD_opencv_xphoto=OFF
-D OPENCV_EXTRA_MODULES_PATH=../../opencv_contrib/modules"
```

## Image support

* png
* jpeg
* jpeg2000
* tiff
* webp

## Without FFmpeg

FFmpeg support is available in different image:
* [DockerHub](https://hub.docker.com/r/m03geek/opencv/)
* [Github](https://github.com/SkeLLLa/docker-opencv)
