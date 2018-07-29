# HDP-Net: Haze Density Prediction Network for Nighttime Dehazing
Yinghong Liao, Zhuo Su, Xiangguo Liang, and Bin Qiu 

Released in 24/05/2018. The test codes are partly based on [DehazeNet](https://github.com/zlinker/DehazeNet).

# Environment Requirement
[Caffe](https://github.com/BVLC/caffe)

[OpenCV](https://opencv.org/)

# Description
This is a test implementation for paper: HDP-Net: Haze Density Prediction Network for Nighttime Dehazing. Here we provide the test demo.

# Usage
Run the python file <code>HDP-Net_test.py</code> with the code like <code>python HDP-Net_test.py img/*.jpg</code> in command. 

# Datasets
We also provide the [datasets](https://pan.baidu.com/s/1cY8O5H8EYIwetPdb6xdupA) adopted in the work: Haze-Free, NightHaze-1, NightHaze-2, YellowHaze-1 and YellowHaze-2. Due to the limited capability of building datasets, these datasets are merely provided as reference. The initial size of images is not 128 x 128 but they are downsampled to smaller resolution before training. Dehazing effects may vary when a different dataset is trainedIf you have any question, please contact us and we are willing to answer.

# Citation
        
	@inproceedings{hdpnet_liao_2018,		
	  title={HDP-Net: Haze Density Prediction Network for Nighttime Dehazing},
	  author={Liao, Yinghong and Su, Zhuo and Liang, Xiangguo and Qiu, Bin},
	  booktitle={The Pacific-Rim Conference on Multimedia (PCM)},
	  year={2018}
	} 

# Examples
<img src="https://github.com/nicholasly/HDP-Net/blob/master/img/01.jpg" width="250px" height="280px" align=left />
<img src="https://github.com/nicholasly/HDP-Net/blob/master/result/Dehaze_01.jpg" width="250px" height="280px" align=right/>

<img src="https://github.com/nicholasly/HDP-Net/blob/master/img/02.bmp" width="280px" height="180px" align=left />
<img src="https://github.com/nicholasly/HDP-Net/blob/master/result/Dehaze_02.bmp" width="280px" height="180px" align=right/>

<img src="https://github.com/nicholasly/HDP-Net/blob/master/img/03.jpeg" width="250px" height="280px" align=left />
<img src="https://github.com/nicholasly/HDP-Net/blob/master/result/Dehaze_03.jpeg" width="250px" height="280px" align=right/>

<img src="https://github.com/nicholasly/HDP-Net/blob/master/img/04.bmp" width="280px" height="180px" align=left />
<img src="https://github.com/nicholasly/HDP-Net/blob/master/result/Dehaze_04.jpg" width="280px" height="180px" align=right/>

<img src="https://github.com/nicholasly/HDP-Net/blob/master/img/05.bmp" width="280px" height="180px" align=left />
<img src="https://github.com/nicholasly/HDP-Net/blob/master/result/Dehaze_05.bmp" width="280px" height="180px" align=right/>
