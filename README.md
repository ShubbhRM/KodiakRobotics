# KodiakRobotics

# Shape and Color Detection with Classical Computer Vision

This project aims to identify geometric shapes (`circle`, `square`, `triangle`) and classify their colors (`red`, `green`, `blue`) in images using classical computer vision techniques. The pipeline uses contour approximation, thresholding, morphological operations, and color averaging to detect and classify each shape instance.


## 🎯 Goal

Generate a `submission.csv` file in the format:

```csv
image_path,label
test_dataset/img_0.png,"[('triangle', 'red'), ('square', 'blue')]"
test_dataset/img_1.png,"[('circle', 'green')]"
