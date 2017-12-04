# VIZION

## Dependencies:
- OpenCV: 3.3.1
- OpenCV Contribs: 3.3.1
- Python: 2.7
- Hadoop: 2.9.0
- libav: 11.11
- CUDA: 9.0

## For OpenCV:
In order to compile OpenCV, OpenCv Contribs and CUDA must be configured during cmake in order for the libraries to work

## To run hadoop
- Go to out_jar
- run: hadoop VIZION.jar <input_path_hdfs> <output_path_hdfs>
