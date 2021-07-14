# Education_Video_Classification
## Authors
Juan Manuel Origgi: jmoriggi@bu.edu

Tania Hasanpoor: taniahsp@bu.edu

Presentation pptx: https://docs.google.com/presentation/d/1CD12jIm-g7qzfzTIwBP_DVDw4Lch17na/edit#slide=id.ge338a65c9b_0_6

## Overview
The goal is to have a model that can predict student wandering using just a computers camera. When students are doing questions, the goal is to have a model in the backend to predict when a student is either wandering or engaged. If the model predicts student wandering, MathSpring(computer software used by students to do math questions) will do a set of things to make sure the student is back to being engaged. This can be 1) giving a hint to students, 2) pop up virtual companion. Overall, the purpose is to have a system to minimize student wandering when solving math questions.
<em>Note: This is a work in progress so the data and the graphs including the code keeps updating.</em>

## References
→ Deep Residual Learning for Image Recognition: [paper_link](https://arxiv.org/pdf/1512.03385.pdf)

→ Learning Spatiotemporal Features with 3D Convolutional Networks: [paper_link](https://arxiv.org/pdf/1412.0767.pdf)

→ Very Deep Convolutional Networks for Large-Scale Image Recognition: [paper_link](https://arxiv.org/pdf/1409.1556.pdf)

→ Learning 2D Temporal Adjacent Networks for Moment Localization [paper_link](https://arxiv.org/pdf/1912.03590.pdf)

## Dataset
- 33 distinct videos of students solving math problems
- 1567 frames images (FPS = 1)
- 3 different students
- For 3 different classes
- Only labels on frames

→ Split of a larger dataset (not labeled yet)

→ Labelling process done using MTurk
