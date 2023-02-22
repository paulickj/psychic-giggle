# psychic-giggle

## Abstract

In this project, I have attempted to Represent digital images (eculidian space as a graph in non-ecuclidian space. To create this mapping, I plan on making a finite set of nodes based on the (r, g, b) values. The edges will represent if the pixel is next to another node. These edges will have weights for how often the relationship is seen in the image. The theory is that in unaltered images, these physical relationships should indicate similarity, and any outliers are indicators of a change.

In an environment that is constantly becoming more online-centric, distinguishing truth from fiction is increasingly tricky. Online people try to control how they appear. Even more recently, AI-generated art has caused a stir as artists panic about the future. The ability to empirically tell if something is real/untampered or generated/edited would be crucial in using images as evidence.


### Other Solutions

- Adobe researchers (Creators of the Creative Cloud Suite [Photoshop]) trained a Convolutional Neural Network on faces edited using Photoshop's Face-Aware Liquify feature. This model can detect changes to faces and predict how the original looks. Many other papers took a similar approach to Adobe's researchers with CNN and RNN. Generally, these models get an accuracy of around 93% - 99% depending on the specifics.
- Beyond the Convolutional Neural Networks, more traditional methods of image forensics. Many of these methods look for a discrepancy in the edited image. (ex. shadows, natural skin flaws) These methods can be very subjective. One more empirical method for detecting changes is by looking at the Error Level Analyzer (ELA) algorithm. This method looks at how the image compares to the "original" when saved and preset qualities. If the image is original, each portion has been saved the same number of times. Specific parts will be saved at different levels with edits to the picture.


### Dataset

There are many private datasets for this problem. For this investigation I have selected a public dataset from Technische Fakultä as it contains 48 unedited images across four cameras. An added benefit to this dataset is the documented steps to create the altered images. Many current phones use automatic image processing to enhance the image fortunately these cameras do not contain this behavior.

https://lme.tf.fau.de/dataset/image-manipulation-dataset/


### Expected Learning
There are two things that I expect to learn regarding this project:
1. Since this is very experimental, my understanding of eculidian and non-eculidian space will be increased. Due to the ordering of pixels, photos are in euclidean space; conversely, graphs, by nature, are not.
2. There are no papers on this specific approach, so I will build my graph network from scratch. I learn best by implementing concepts meaning my comprehension of graph neural networks will dramatically increase.

## Methods


## Results


## Conclusion


## References


