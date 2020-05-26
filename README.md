# Sequence-to-function deep learning frameworks for synthetic biology

This repository provides code for [Valeri, Collins, et al. 2019](https://www.biorxiv.org/content/10.1101/870055v1). 

## Abstract
While synthetic biology has revolutionized our approaches to medicine, agriculture, and energy, the design of novel circuit components beyond nature-inspired templates can prove itself challenging without well-established design rules. Toehold switches — programmable nucleic acid sensors — face an analogous prediction and design bottleneck: our limited understanding of how sequence impacts functionality can require expensive, time-consuming screens for effective switches. Here, we introduce the Sequence-based Toehold Optimization and Redesign Model (STORM), a deep learning architecture that applies gradient ascent to re-engineer poorly-performing toeholds. Based on a dataset of 91,534 toehold switches, we examined convolutional filters and saliency maps of sequences to interpret our sequence-to-function model, identifying hot spots where mutations change toehold effectiveness and features unique to high-performing switches. Our modeling platform provides frameworks for future toehold selection, augmenting our ability to construct potent synthetic circuit components and precision diagnostics, and enabling straightforward translation of this in silico workflow to other circuitries.

## Analysis
There are two notebooks corresponding to STORM's two purposes: prediction and redesign. First, a notebook to use the trained model for predicting ON and OFF values of toehold sequences has been uploaded. Second, a notebook to use the trained model and our gradient ascent framework for optimizing toehold sequences has been uploaded. Example sequences for both are located in their respective folders, where the output of the notebook will display.

## Website
A web version of these tools has been made available to ease integration into lab workflows. The beta version of our website is available at https://storm-toehold.herokuapp.com. Please note there is a ~10 second delay on startup if the website has not been used in a while. For any feedback, questions, or bug reports, email valerij@mit.edu.
