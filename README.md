# 1. To reproduce the results of the following paper  

@inproceedings{venugopalan2015sequence,  
  title={Sequence to sequence-video to text},  
  author={Venugopalan, Subhashini and Rohrbach, Marcus and Donahue, Jeffrey and Mooney, Raymond and Darrell, Trevor and Saenko, Kate},  
  booktitle={Proceedings of the IEEE international conference on computer vision},  
  pages={4534--4542},  
  year={2015}  
}  

I modified the code from https://github.com/chenxinpeng/S2VT to Tensorflow r1.3 and Python3.  

# 2. Folders are expected to be organized as follows:
## ./s2vt_r1.3
  ## /models [null, to save trained models]
  ## /rgb_feats [null, to save rgb CNN features for frames]
  ## /vgg
    ## ilsvrc_2012_mean.npy
    ## VGG_ILSVRC_16_layers_deploy.prototxt
    ## VGG_ILSVRC_16_layers.caffemodel
  ## /data
    ## /msvd
      ## video_corpus.csv [video corpus download from Microsoft website]
    ## /youtube_videos [null, to save videos downloaded from Youtube]

