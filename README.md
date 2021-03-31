# -surveillance-system-object-detection
In addition to security purposes, closed circuit video camera (CCTV) can provide extra customer information, e.g., Count of customers, whether they are entering alone or with group. Such valuable information allows marketing analysis to better understand customer behavior and can provide a more satisfying service. The detection is evaluated on YOLO model is used to detect objects from the frames which is trained on the dataset named COCO taking pretrained weights and configurations. Further part of research can be done on the basis of detected results.



In the project , I have used some pretrained models and classes , coco dataset and pretrained weights and configration file.

Centroid tracker is a class file created which is used for tracking the persons in frames of videos. 

Steps:
Check paths . create folders of videos , input images,output images,setup files in D/Project.
Keep your video in dataset in videos and keep the name as your video name in second block of the code .

make sure coco weights, coco confighration path , coco names files are there in setup_files folder.
