# **Semantic Segmentation of Aerial Images**

# _**Overview**_

_This project focuses on semantic segmentation of aerial images obtained from Dubai using satellite imagery. The dataset includes pixel-wise annotations, enabling segmentation into six distinct classes. The goal is to develop and evaluate models for accurately segmenting these images into meaningful regions, such as buildings, roads, vegetation, and water._

# _**Dataset**_

"https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery"

_The dataset consists of 72 high-resolution images grouped into six tiles, each annotated at the pixel level for semantic segmentation. The classes are as follows:_

**Building:** Represented by the color #3C1098

**Land (unpaved area):** Represented by the color #8429F6

**Road:** Represented by the color #6EC1E4

**Vegetation:** Represented by the color #FEDD3A

**Water:** Represented by the color #E2A929

**Unlabeled:** Represented by the color #9B9B9B

Features

Pixel-level annotations for precise semantic segmentation tasks.

Multiple classes to capture diverse real-world scenarios in aerial imagery.

Useful for urban planning, environmental monitoring, and geographic studies.

Preprocessing

Key preprocessing techniques applied in this project:

Image Patchification: Breaking down large satellite images into smaller patches to reduce computational overhead and facilitate detailed analysis.

Normalization: Ensuring pixel values are scaled appropriately for input into neural networks.

Data Augmentation: Enhancing the dataset by applying transformations like rotation, flipping, and scaling to improve model generalization and robustness.

Methodology

The workflow includes:

Data Loading and Preprocessing:

Images are loaded and preprocessed to ensure compatibility with the segmentation models.

Patches of fixed sizes are generated for model training and testing.

Model Architecture:

Employing deep learning architectures like U-Net for segmentation tasks, known for its encoder-decoder structure that captures fine details in images.

Experimentation with other state-of-the-art models such as DeepLabV3 or FCN (Fully Convolutional Networks).

Training:

Using segmentation-specific loss functions like Dice Loss and Categorical Cross-Entropy to optimize model performance.

Incorporating validation techniques to monitor performance during training and avoid overfitting.

Evaluation:

Metrics like Intersection over Union (IoU) and F1 Score are used to measure model accuracy.

Visualizing segmented outputs to qualitatively assess performance.

Results

Quantitative Metrics:

Achieved high IoU and F1 scores across most classes, demonstrating the model's ability to generalize well to unseen data.

Qualitative Analysis:

Clear and accurate segmentation outputs visualized for different classes, showcasing the effectiveness of the approach.

Applications

This project has broad applications, including:

Urban Planning: Mapping buildings, roads, and vegetation to aid in city planning and infrastructure development.

Environmental Monitoring: Tracking vegetation and water bodies to assess environmental changes over time.

Disaster Management: Identifying affected areas post-disaster, such as flooded regions or damaged structures.

Geospatial Analysis: Supporting geographic information systems (GIS) with high-quality segmented data.

Contributing
You can download dataset from here:

