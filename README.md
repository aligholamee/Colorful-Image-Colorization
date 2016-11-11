# Image-Color
A deep learning approach to colorizing images

The current model was trained on screenshots taken from Pokemon Silver,
and tested on Pokemon Blue Version. Sample results below.

## Basic Usage
`python train.py --help`

`-c --checkpoint_dir <str> [path to save the model]`

`-b --batch_size     <int> [batch size]`

`-d --data_dir       <str> [path to root image folder]`

`-n --normalize      <str> [y/n normalize training images]`


Run `python train.py -c model_dir/ -b 5 -d ../images/train/ -n n` to start training
on the small amount of sample images.


## Using your own data


![test_1](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_3.png?raw=true)
![test_1](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_3_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_5.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_5_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_1.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_1_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_2.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_2_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_4.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_4_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_6.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_6_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_7.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_7_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_8.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_8_output.png?raw=true)

[test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_9.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_9_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_10.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_10_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_11.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_11_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_12.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_12_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_13.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_13_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_14.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_14_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_15.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_15_output.png?raw=true)

![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/testing/test_16.png?raw=true)
![test_2](https://github.com/cameronfabbri/Colorful-Image-Colorization/blob/master/images/resized/output/test_16_output.png?raw=true)

