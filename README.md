# mri-deep-learning-tools
Resurces for MRI images processing and deep learning in 3D

| Project Name | Description | Scenario |
| ------- | ------ | ------ |
|[Clinica Deep Learning (clinicadl)](https://github.com/aramis-lab/AD-DL)| This repository hosts the code source for reproducible experiments on automatic classification of Alzheimer's disease (AD) using anatomical MRI data. It allows to train convolutional neural networks (CNN) models. The journal version of the paper describing this work is available here. | classification |
|[DeepMedic](https://github.com/deepmedic/deepmedic)| Efficient Multi-Scale 3D Convolutional Neural Network for Segmentation of 3D Medical Scans Project aims to offer easy access to Deep Learning for segmentation of structures of interest in biomedical 3D scans. It is a system that allows the easy creation of a 3D Convolutional Neural Network, which can be trained to detect and segment structures if corresponding ground truth labels are provided for training. The system processes NIFTI images, making its use straightforward for many biomedical tasks.| segmentation |
| [Deep Cascade of Convolutional Neural Networks and Convolutioanl Recurrent Nerual Networks for MR Image Reconstruction](https://github.com/js3611/Deep-MRI-Reconstruction) | Reconstruct MR images from its undersampled measurements using Deep Cascade of Convolutional Neural Networks (DC-CNN) and Convolutional Recurrent Neural Networks (CRNN-MRI). This repository contains the implementation of DC-CNN using Theano and Lasagne, and CRNN-MRI using PyTorch, along with simple demos. Note that the library requires the dev version of Lasagne and Theano, as well as pygpu backend for using CUFFT Library | reconstruction |
| [GANCS](https://github.com/gongenhao/GANCS) | Compressed Sensing MRI based on Generative Adversarial Network | reconstruction |
| [Layer-wise relevance propagation for explaining deep neural network decisions in MRI-based Alzheimer’s disease classification](https://github.com/moboehle/Pytorch-LRP) | *Moritz Böhle, Fabian Eitel, Martin Weygandt, and Kerstin Ritter* <br>Preprint: [https://arxiv.org/abs/1903.07317](https://arxiv.org/abs/1903.07317) | classification |
| [Medical Detection Toolkit](https://github.com/MIC-DKFZ/medicaldetectiontoolkit) | The Medical Detection Toolkit contains 2D + 3D implementations of prevalent object detectors such as Mask R-CNN, Retina Net, Retina U-Net, as well as a training and inference framework focused on dealing with medical images. | detection, segmentation |
| [MedicalTorch](https://github.com/perone/medicaltorch) | is an open-source framework for PyTorch, implementing an extensive set of loaders, pre-processors and datasets for medical imaging. | preprocessing |
| [MEDICAL ZOO](https://github.com/black0017/MedicalZooPytorch) | a 3D multi-modal medical image segmentation library in PyTorch | segmentation |
| [NiftyTorch](https://github.com/NiftyTorch/NiftyTorch.v.0.1) | is a Python API for deploying deep neural networks for Neuroimaging research | classification, segmentation |
| [nipy](https://nipy.org/)<br>Computational Anatomy:<br> - [dipy](https://github.com/dipy/dipy)<br> - [mindboggle](https://github.com/nipy/mindboggle)<br>File I/O and Data Management:<br> - [nibabel](https://github.com/nipy/nibabel)<br>Functional MRI:<br> - [Nipy](https://github.com/nipy)<br> - [Nitime](https://github.com/nipy/nitime)<br> - [popeye](https://github.com/kdesimone/popeye)<br>Machine Learning:<br> -  [Nilearn](https://github.com/nilearn/nilearn) <br> -  [PyMVPA](https://github.com/PyMVPA/PyMVPA)<br>Human Electrophysiology:<br> -  [MNE](https://github.com/mne-tools/mne-python)<br> Data Visualisation:<br> -  [niwidgets](https://github.com/nipy/niwidgets) | -a community of practice devoted to the use of the Python programming language in the analysis of neuroimaging data <br>Computational Anatomy:<br> - Focuses on diffusion magnetic resonance imaging (dMRI) analysis. <br> - Improves the accuracy, precision, and consistency of labeling & morphometry of brain imaging data.<br>File I/O and Data Management:<br> - Read / write common neuroimaging file formats. <br>Functional MRI:<br> - Analysis of structural and functional neuroimaging data.<br> - Time-series analysis of neuroscience data.<br> - Population receptive field estimation <br>Machine Learning:<br> - Fast and easy statistical learning on neuroimaging data.<br> - Eases statistical learning analyses of large neuroimaging datasets.<br>Human Electrophysiology:<br> - Processes magnetoencephalography (MEG) and electroencephalography (EEG) data <br> - Provides interactive plots for volumetric images.<br> Data Visualisation:<br> - Provides a uniform interface to existing neuroimaging software.|- denoising, registration, reconstruction, tracking, clustering, visualization, and statistical analysis|
| [SegNet](https://github.com/alexgkendall/caffe-segnet) | SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation Vijay Badrinarayanan, Alex Kendall and Roberto Cipolla, PAMI 2017 [http://arxiv.org/abs/1511.00561] | segmentation |
| [TractSeg](https://github.com/MIC-DKFZ/TractSeg) | -Tool for fast and accurate white matter bundle segmentation from Diffusion MRI. It can create bundle segmentations, segmentations of the endregions of bundles and Tract Orientation Maps (TOMs). Moreover, it can do tracking on the TOMs creating bundle-specific tractogram and do Tractometry analysis on those. | segmentation |
| [TorchIO](https://github.com/fepegar/torchio) | is a Python package containing a set of tools to efficiently read, preprocess, sample, augment, and write 3D medical images in deep learning applications written in PyTorch <br> [Pérez-García et al., 2020, TorchIO: a Python library for efficient loading, preprocessing, augmentation and patch-based sampling of medical images in deep learning.](https://arxiv.org/abs/2003.04696)| preprocessing |
| [3D-UNet-PyTorch-Implementation](https://github.com/JielongZ/3D-UNet-PyTorch-Implementation) | -the implementation of 3D UNet Proposed by Özgün Çiçek et al.,<br>Preprint:[3D U-Net: Learning Dense Volumetric Segmentation from Sparse Annotation.](https://arxiv.org/abs/1606.06650)| segmentation |


# Tenserflow
| Project Name | Description | Task |
| ------- | ------ | ------ |
|[DLTK](https://github.com/DLTK/DLTK) | Deep Learning Toolkit (DLTK) for Medical Imaging <br> DLTK is a neural networks toolkit written in python, on top of TensorFlow. It is developed to enable fast prototyping with a low entry threshold and ensure reproducibility in image analysis applications, with a particular focus on medical imaging. Its goal is to provide the community with state of the art methods and models and to accelerate research in this exciting field. | classification, segmentation, super-resolution, regression |
| [Graph CNNs for population graphs: classification of the ABIDE dataset](https://github.com/parisots/population-gcn) | code provides a python - Tensorflow implementation of graph convolutional networks (GCNs) for semi-supervised disease prediction using population graphs | classification |
| [Nobrainer](https://github.com/neuronets/nobrainer) | -is a deep learning framework for 3D image processing. It implements several 3D convolutional models from recent literature, methods for loading and augmenting volumetric data that can be used with any TensorFlow or Keras model, losses and metrics for 3D data, and simple utilities for model training, evaluation, prediction, and transfer learning.| preprocessing, segmentation |
| [3D-Convolutional-Network-for-Alzheimer's-Detection](https://github.com/RishalAggarwal/3D-Convnet-for-Alzheimer-s-Detection) |This repository consists of an attempt to detect and diagnose Alzheimer's using 3D MRI T1 weighted scans from the ADNI database.It contains a data preprocessing pipeline to make the data suitable for feeding to a 3D Convnet or Voxnet followed by a Deep Neural Network definition and an exploration into all the utilities that could be required for such a task.| detection, preprocessing |4
