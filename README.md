# AdvCar: Adversarial Attacking Method Against Vehicle Detectors With Multi-Scales Enhancement

## ❗ Rebuttal Supplementary materials
Since we cannot effectively present the relevant experimental results in the main text, we will supplement them here.
### Digital Comparison Chart
Please note: In the images, the red boxes around the cars with our textures in YOLOv2, YOLOv3, YOLOv5, and Faster-RCNN are ground truth (GT) boxes, not detection boxes. In the D-DETR images, the green boxes are GT boxes.
![contrast](src/demo_video/contrast_2.png)

### Physical Comparison Chart
We expect to complete the supplementary physics experiments within 1-2 days.
Experimental setup：
We used two Audi A6L models for physical verification, one as a control group without texture and the other as an experimental group with texture.
![physical_1](src/demo_video/physical_1.png)

## Abstract

Adversarial attacks on autonomous driving perception have recently attracted increasing research interest. Despite many physical-world approaches, their effectiveness often deteriorates in real road settings, with limited transfer across changes in viewpoint, distance, and illumination. To address this, we introduce a unified training framework spanning the multi-scale vehicle surface domain, simultaneously optimizing different scales vehicle adversarial textures to improve attack efficacy in both digital and physical environments. The framework incorporates an illumination-consistency module that corrects lighting discrepancies between the textured vehicle and its background, preserving photometric coherence across viewpoints and imaging conditions. Extensive experiments in both digital and physical environments show that, compared with existing methods, our method achieves higher and more stable attack success rates across mainstream detectors and exhibits stronger cross-model and cross-scene generalization.

## Demonstration
## 🎥 Demo Videos

| Normal | DTA |
|--------|-----|
| [![Normal](https://img.youtube.com/vi/u2CB_8c-UDs/0.jpg)](https://youtu.be/u2CB_8c-UDs) | [![DTA](https://img.youtube.com/vi/YWtx-TSjUEw/0.jpg)](https://youtu.be/YWtx-TSjUEw) |

| ACTIVE | AdvCar |
|--------|--------|
| [![ACTIVE](https://img.youtube.com/vi/wKGEWYsH73w/0.jpg)](https://youtu.be/wKGEWYsH73w) | [![AdvCar](https://img.youtube.com/vi/5-ArfuogGKo/0.jpg)](https://youtu.be/5-ArfuogGKo) |

## Video link
Normal：https://youtu.be/u2CB_8c-UDs

DTA：https://youtu.be/YWtx-TSjUEw

ACTIVE：https://youtu.be/wKGEWYsH73w

Ours：https://youtu.be/5-ArfuogGKo
