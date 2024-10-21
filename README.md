This study delves into the EUROSAT dataset, featuring satellite images categorized
into 10 distinct land cover classes. Due to variations in class sizes, a stratified approach is
essential during data splitting to ensure equitable representation across all classes. The project
initiates with an exploratory visual analysis of the dataset, showcasing representative satellite
images for each land cover category. Data preprocessing entails segregating the dataset into
training and testing subsets using a stratified splitting technique, ensuring balanced class
distributions in both subsets. Augmentation techniques are then applied to the training data to
introduce controlled variations, Increasing the model's robustness and generalization
capabilities. A diverse array of machine learning and deep learning models are enlisted for the
image classification task, including traditional algorithms such as Random Forest, alongside
advanced Convolutional Neural Networks (CNNs) like ResNet50, ResNet50V2, ResNet152V2, VGG16, and VGG19. Each model undergoes meticulous training and
evaluation protocols. Results underscore the superiority of CNNs over traditional machine
learning methods. ResNet50 emerges as the top performer, achieving an impressive accuracy
of 97.53%, closely trailed by ResNet50V2 at 94.26%. Other noteworthy models include
VGG19 with 96.83% accuracy, VGG16 at 95.21%, and ResNet152V2 at 93.22%. These
findings underscore the efficacy of deep learning techniques, particularly CNNs, in extracting
intricate features from satellite imagery for precise land cover classification. Ultimately, the
study selects and preserves the best-performing model, ResNet50, for future deployment in
practical applications. This project enriches the understanding of land cover classification
using satellite imagery and furnishes valuable insights into the relative performance of various
machine learning and deep learning techniques in this realm. The outcomes hold promise for
diverse applications including urban planning, environmental monitoring, resource
management, and other geospatial analysis pursuits

Dataset:
![Data set](https://github.com/user-attachments/assets/b1fb5cbe-493c-4071-a67e-1d61669ecb56)

The EuroSAT dataset com prises 27,000 images captured by the ESA Sentinel-2
satellite, each with a resolution of 64x64 pixels. These images represent 10 distinct land
cover classes across 34 European countries. The dataset is available in two versions: RGB
only and all 13 Multispectral (MS) Sentinel-2 bands. EuroSAT is deemed a relatively simple
dataset, with ResNet-50 architecture capable of achieving about 98.6% accuracy.
Fig 3.3 Preview of the different classes in Dataset
13
The dataset contains 10 land cover classes: annual crop, forest, herbaceous vegetation, highway, industrial buildings, pasture, permanent crop, residential buildings, river, and
sea/lake. It is composed of RGB images, with three bands, making it suitable for various
classification tasks

Architecture:
![Data set](https://github.com/user-attachments/assets/8a60009d-7b63-4a06-977c-f272b932c729)

