# TensorFlow Lite Python object detection example with Raspberry Pi

Run the code with desired object detection.

Added with custom object detection model for andriod figure, so can test easily.

```
python3 detect.py \
  --model efficientdet_lite0.tflite
```


```
python3 detect.py \
  --enableEdgeTPU
  --model efficientdet_lite0_edgetpu.tflite
```