
#  Ship Detection in SAR Imagery 

Running YOLOv5 on HRSID dataset for maritime vessel detection

[HRSID.pdf](https://github.com/AnshCharak/YOLOV5-HRSID-SHIP-DETECTION-/files/12334942/HRSID.pdf)


## YOLOv5 Framework
![yolov5](https://github.com/AnshCharak/YOLOV5-HRSID-SHIP-DETECTION-/assets/60294845/b708d0db-3396-497e-b729-8e59abab15e4)

YOLOv5's architecture consists of three main parts:

Backbone: This is the main body of the network. For YOLOv5, the backbone is designed using the New CSP-Darknet53 structure, a modification of the Darknet architecture used in previous versions.
Neck: This part connects the backbone and the head. In YOLOv5, SPPF and New CSP-PAN structures are utilized.
Head: This part is responsible for generating the final output. YOLOv5 uses the YOLOv3 Head for this purpose.


####




    Dependancies: pycocotools, numpy, skimage, pandas, matplotlib, torch, wandb, yaml,tensorboard





## Results

https://api.wandb.ai/links/charak/kbb8sy5v

<img src="https://github.com/AnshCharak/YOLOV5-HRSID-SHIP-DETECTION-/assets/60294845/760b0f04-2b4d-4f0f-a182-a3a5c0206805" width="400">
<img src="https://github.com/AnshCharak/YOLOV5-HRSID-SHIP-DETECTION-/assets/60294845/dfea7314-65e9-4726-8c38-66b7e1943550" width="400">
<img src="https://github.com/AnshCharak/YOLOV5-HRSID-SHIP-DETECTION-/assets/60294845/36bc632b-5bd2-4373-88ed-4976a4177d80" width="400">
<img src="https://github.com/AnshCharak/YOLOV5-HRSID-SHIP-DETECTION-/assets/60294845/a3866aa4-4bf2-4501-80a2-4094e5524396" width="400">
<img src="https://github.com/AnshCharak/YOLOV5-HRSID-SHIP-DETECTION-/assets/60294845/d118c04b-2558-4160-a85e-74d63ba59823" width="400">
