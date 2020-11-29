# ObjectDetection
Basic Object Detection

# References
- https://towardsdatascience.com/creating-your-own-object-detector-ad69dda69c85
- https://gilberttanner.com/blog/live-object-detection
- https://github.com/tzutalin/labelImg
- https://github.com/vc1492a/Hey-Waldo
- https://towardsdatascience.com/how-to-find-wally-neural-network-eddbb20b0b90
- https://www.pyimagesearch.com/2018/05/14/a-gentle-guide-to-deep-learning-object-detection/

## Resolving tensorflow.contrib issue
- https://stackoverflow.com/questions/55082483/why-i-cannot-import-tensorflow-contrib-i-get-an-error-of-no-module-named-tensor

```
python generate_tfrecord.py --csv_input=labelled\\train_labels.csv --image_dir=images\train --output_path=train.record
```