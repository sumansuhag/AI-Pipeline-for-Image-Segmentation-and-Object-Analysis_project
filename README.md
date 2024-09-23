# AI-Pipeline-for-Image-Segmentation-and-Object-Analysis_project

## Project Overview
This project implements an AI pipeline that processes input images to segment, identify, and analyze objects within the image. The pipeline outputs a summary table with mapped data for each object.

## Features
- Image segmentation using Mask R-CNN
- Object extraction and storage
- Object identification
- Text/data extraction from objects
- Summarization of object attributes
- Data mapping to objects and master image
- Output generation with annotated image and summary table

2. Use the UI to upload an image and process it through the pipeline.

## Project Structure
```
project_root/
├── data/
│   ├── input_images/
│   ├── segmented_objects/
│   └── output/
├── models/
│   ├── segmentation_model.py
│   ├── identification_model.py
│   ├── text_extraction_model.py
│   └── summarization_model.py
├── utils/
│   ├── preprocessing.py
│   ├── postprocessing.py
│   ├── data_mapping.py
│   └── visualization.py
├── streamlit_app/
│   └── app.py
├── tests/
│   ├── test_segmentation.py
│   ├── test_identification.py
│   ├── test_text_extraction.py
│   └── test_summarization.py
├── README.md
└── requirements.txt


## Implementation Details
### Image Segmentation
The image segmentation is implemented using Mask R-CNN from torchvision. The `SegmentationModel` class in `models/segmentation_model.py` handles the segmentation process.

