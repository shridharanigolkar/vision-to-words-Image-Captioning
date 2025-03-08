Image Captioning using Transformers

Overview

This project implements an image captioning system using Transformers. It leverages EfficientNetB0 for image feature extraction and a Transformer-based model for generating captions.

Features

Uses EfficientNetB0 as the feature extractor.

Implements a Transformer-based decoder to generate captions.

Supports custom datasets for training and inference.

Provides preprocessing and training scripts for easy model training.

Dataset Preparation

Download an image-caption dataset (e.g., MS COCO, Flickr8k, or custom dataset).

Place images in data/images/ and captions in data/captions.json.

Preprocess the data:
