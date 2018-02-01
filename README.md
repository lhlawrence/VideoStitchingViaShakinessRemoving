# Dynamic Video Stitching via Shakiness Removing

Demo code and example inputs for the works below:
 - Nie, Yongwei, et al. "Dynamic Video Stitching via Shakiness Removing." IEEE Transactions on Image Processing 27.1 (2018): 164-178.
 - Su, Tan, et al. "Video stitching for handheld inputs via combined video stabilization." SIGGRAPH ASIA 2016 Technical Briefs. ACM, 
 2016. 
 
## External libraries and code used
 - Shankar Rao's Motion Segmentation Code: http://perception.csl.illinois.edu/coding/motion/#Software
 - CVX: http://cvxr.com/cvx/
 - vlfeat: http://www.vlfeat.org/
 - peter kovesi matlab toolbox: http://www.peterkovesi.com/matlabfns/
 - Liu Shuaicheng's As-similar-as-possible Warping code: http://www.liushuaicheng.org/SIGGRAPH2013/index.htm
 
## How to use this demo code

1. In file fodler '/case-cuhk_lib', extract video frames of case17-l.mp4 to folder '/left', and extract video frames of case17-r.mp4 to folder '/right'. After the frame extracation, each folder should contain 400 png files. The file names shoudl be indexed properly. (e.g. 001.png 002.png ...)

2. You may need to install CVX. 

3. Set MATLAB path to '/Stitching-1.1.0', run RunStitching.m

For more details, please read the comments

Please cite our papers:

@article{nie2018dynamic,
  title={Dynamic Video Stitching via Shakiness Removing},
  author={Nie, Yongwei and Su, Tan and Zhang, Zhensong and Sun, Hanqiu and Li, Guiqing},
  journal={IEEE Transactions on Image Processing},
  volume={27},
  number={1},
  pages={164--178},
  year={2018},
  publisher={IEEE}
}

@inproceedings{su2016video,
  title={Video stitching for handheld inputs via combined video stabilization},
  author={Su, Tan and Nie, Yongwei and Zhang, Zhensong and Sun, Hanqiu and Li, Guiqing},
  booktitle={SIGGRAPH ASIA 2016 Technical Briefs},
  pages={25},
  year={2016},
  organization={ACM}
}
 
Code by Tan Su, Zhensong Zhang and Yongwei Nie. For research purpose ONLY. 