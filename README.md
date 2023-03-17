# pointpillar_ros_re  
0317:  
报错见0317_path.log,原因是没有修改yaml文件中的路径  
修改`/home/xilm/openPCdet/OpenPCDet/tools/cfgs/kitti_models`中的`pointpillar.yaml`文件第四行为绝对路径  


------------------------------
Reference:  
1. pointpillar-ros [github](https://github.com/BIT-DYN/pointpillars_ros);  
2. some csdn blogs   
- [1.original](https://blog.csdn.net/weixin_43807148/article/details/125867953?spm=1001.2014.3001.5502);  
- [2.modified](https://blog.csdn.net/jiachang98/article/details/126106126?spm=1001.2014.3001.5501);  
3. modified code in [gitee](https://gitee.com/ximing689/pointpillars_ros/tree/main)  
