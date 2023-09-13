# VisualGrounding
The aim of this project is to fine tune [CLIP (Contrastive Language-Image Pre-training)](https://openai.com/research/clip) model in order to face a visual grounding task.

Given an image and a prompt we try to extract the best bounding box.

In this project we present different methods:
- Baseline (Yolo+Clip)
- Baseline with contrastive finetuning
- A two stage approach (Faster RCNN + Clip)
- A one stage approach exploiting a Fusion Module architecture
- A one stage approach based on the the paper ["A Fast and Accurate One-Stage Approach to Visual Grounding"](https://arxiv.org/pdf/1908.06354.pdf)

Students: Trevisan Thomas, Scialla Giovanni, Canova Tommaso
