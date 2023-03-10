# Animal-Classification-and-Detection-using-ML-Techniques


Biodiversity conservation depends on accurate, up-to-date information about wildlife population
distributions. Motion-activated cameras, also known as camera traps, are a critical tool for population
surveys, as they are cheap and non-intrusive. However, extracting useful information from camera trap
images is a cumbersome process: a typical camera trap survey may produce millions of images that require
slow, expensive manual review. Consequently, critical information is often lost due to resource limitations,
and critical conservation questions may be answered too slowly to support decision-making. Computer
vision is poised to dramatically increase efficiency in image-based biodiversity surveys, and recent studies
have successfully harnessed deep learning techniques for automatic information extraction from camera
trap images. However, the accuracy of results depends on the amount, quality, and diversity of the data
available to train models, and the literature has focused on projects with millions of relevant, labeled
training images.
Many camera trap projects do not have a large set of labeled images, and hence cannot benefit
from existing machine learning techniques. Furthermore, even projects that do have labeled data from
similar ecosystems have struggled to adopt deep learning methods because image classification models
overfit to specific image backgrounds. We focus not on automating the labeling of camera trap images,
but on accelerating this process. We combine the power of machine intelligence and human intelligence
to build a scalable, fast, and accurate active learning system to minimize the manual work required to
identify and count animals in camera trap images.
We apply Context R-CNN to two settings species detection using camera traps, showing that the
Context R-CNN leads to performance gains over strong baselines. Moreover, we show that increasing the
contextual time horizon leads to improved results.
