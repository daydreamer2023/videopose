## handle video
`python wild_video.py --viz-output output.mp4 --viz-video /path/to/video.mp4`
or
`python wild_video.py --viz-output output.gif --viz-video /path/to/video.mp4 --viz-limit 180`


## handle video with every frame keypoints
`python wild_video.py --viz-output output.mp4 --viz-video /path/to/video.mp4 --input-npz /path/to/input_name.npz`


## DEMO
`python demo.py`

<br>

```
指定输入视频  --viz-video  
指定输入视频的关节点  --input-npz   
指定输出视频名称  --viz-output   
```

添加hrnet 2D关键点检测模块,实现更高精读的3D video 重构   
(hrnet)[git@github.com:lxy5513/hrnet.git]
