# Mirror Padding

## Example

![](results/result_1.jpg)

![](results/result_2.jpg)

![](results/result_3.jpg)


## How to Use

```
$ python
>>> from mp import MirrorPadding
>>> import cv2
>>> img = cv2.imread('data/sample_1.jpg')
>>> mp = MirrorPadding('../shape_predictor_68_face_landmarks.dat')
>>> mirror = mp.padding(img)
>>> detected = mp.detect(img, mirror)
```

