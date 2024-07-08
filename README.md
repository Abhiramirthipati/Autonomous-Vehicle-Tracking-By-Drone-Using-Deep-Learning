
# Autonomous Vehicle Tracking By Drone Using Deep Learning

Problem Statement: How can we utilize the modern drone technology to improve aspects of transportation and security, like vehicle tracking and other related security issues?

This This deeply motivates us to enable mini drones to track vehicles, which helps in security and surveillance, parking management, stolen vehicle recovery, evaluating driving license tests, etc.

This project uses multiple deep learning models working together to track vehicles effectively.

    1. Object classification model - Basic CNN
    The first and foremost step of object classification was done through basic CNN.  

    2. Object detection model
        a. Yol0 v8 
        b. Faster-RCNN 
    Based on the comparison work conducted by us, we concluded that YOLOv8 detection model is suitable for object tracking purposes

    3. Feature extraction model - ResNet-50
        a. Dataset Preparation: Snapshots of target objects from various video sources across the internet from their entry to exit 21 different cars were selected for dataset preparation 

## Tech Stack

**Language:** Python

**Frameworks:** Numpy, cv2, Pytorch, Tensorflow, Keras, sklearn, Ultralytics.

**Platform:** Jupyter notebook


## Acknowledgements

 - [Project Guide - Dr. Shital S Chiddarwar, Professor, VNIT Nagpur](https://www.linkedin.com/in/shital-chiddarwar-ph-d-5a7173b6/)
 - [Project Mentor - Vinay Araveti, Software Developer, HILTI Technologies](https://www.linkedin.com/in/araveti-vinay/)

## References
- [P. F. Felzenszwalb et al., “Object detection with discriminatively trained part-based models,” IEEE Trans. Pattern Anal. Mach. Intell., vol. 32, no. 9, pp. 1627–1645, Sep. 2010.]
- [R. Barták and A. Vykovský, "Any Object Tracking and Following by a Flying Drone," 2015 Fourteenth Mexican International Conference on Artificial Intelligence (MICAI), Cuernavaca, Mexico, 2015, pp. 35-41, doi: 10.1109/MICAI.2015.12.]
- [M. A. Bin Zuraimi and F. H. Kamaru Zaman, "Vehicle Detection and Tracking using YOLO and DeepSORT," 2021 IEEE 11th IEEE Symposium on Computer Applications & Industrial Electronics (ISCAIE), Penang, Malaysia, 2021, pp. 23-29, doi: 10.1109/ISCAIE51753.2021.9431784.]
- [N. M. Krishna, R. Y. Reddy, M. S. C. Reddy, K. P. Madhav and G. Sudham, "Object Detection and Tracking Using Yolo," 2021 Third International Conference on Inventive Research in Computing Applications (ICIRCA), Coimbatore, India, 2021]

