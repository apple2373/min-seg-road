# Minimizing Supervision for Free-space Segmentation

This is the **informal** soruce code for the following paper. The formal one is here: https://github.com/pfnet-research/superpixel-align 

http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Tsutsui_Minimizing_Supervision_for_CVPR_2018_paper.pdf
```
@inproceedings{tsutsui2018minimizing,
  title={Minimizing Supervision for Free-Space Segmentation},
  author={Tsutsui, Satoshi and Kerola, Tommi and Saito, Shunta and Crandall, David J},
  comment = {the first three authors contributed equally},
  booktitle={Conference on Computer Vision and Pattern Recognition (CVPR) Workshop on Autonomous Driving},
  year={2018}
}
```

please see minimum-workingexample.ipynb

# Disclaimer

This is just a minimum working example to show how our automatic road mask generation works, which is implemented solely by me (Satoshi Tsutsui). Because I did the work in an internship and  still do not have the company's permission to open source the code, I reproduced from scratch by myself.  For the experiments in the paper, we used other implementation with gpu enabled cupy backed, and the core part is mostly coded by Shunta Saito (my co-author). As far as I recognize, a big difference is the input resolution. While this one use 224 x 224 for input, the paper used higher resolution for superpixels algorithms so that we can get more precise superpixels. 

Update: My PFN co-author made the official one available: https://github.com/pfnet-research/superpixel-align
