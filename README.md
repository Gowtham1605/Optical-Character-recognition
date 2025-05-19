# Optical Character Recognition (OCR)

## Overview

This is an Optical Character Recognition (OCR) projet, a specific type of `Image-To-Text technique` using traditional computer vision and deep learning approaches, to recognize and extract text from images.

**Popular OCR Tools**

| Name | Description | Pros | Cons |
|---|---|---|---|
| Tesseract-OCR (Tesseract) | Core OCR engine (C++) | Powerful, open-source | Not directly usable in Python |
| Tesserocr | Python wrapper for Tesseract-OCR C++ API | Less common, allows Python use | Might be less user-friendly than PyTesseract |
| PyTesseract | Python library for Tesseract-OCR | Simple to use, powerful | Requires separate Tesseract-OCR installation |
| EasyOCR | Separate Python library for OCR | Lightweight, good for receipts/PDFs, multi-language | Might not be as powerful as Tesseract-OCR for all tasks |
| Keras-OCR | Python library built on Keras/TensorFlow | User-friendly, deep learning approach | Might require more computing resources |
| Ocrad/GOCR | Open-source OCR engines | Established, free options | May have lower accuracy compared to newer libraries |
| ocropus/Calamari | Free, open-source OCR with LSTMs | Potentially high accuracy | May be more complex to set up |
| Amazon Textract | Cloud-based OCR service (AWS) | High accuracy, scalable, pre-built functionalities | Requires paid AWS account |
| Microsoft Azure Cognitive Services - Computer Vision | Cloud-based OCR solution (Microsoft) | Various features, text extraction, document processing | Requires paid Azure account |
| Google Cloud Vision API | Cloud-based OCR with image intelligence functionalities | Offered by Google Cloud Platform | Requires paid GCP account |

## Requirements

```
- tesseract-ocr
- libtesseract-dev
- pytesseract
- pillow
- io
- matplotlib.pyplot
```

## Applications

- Image-To-Text
- Convert scanned documents to text
- Handwritten text to machine digital text
- Text extraction and Recognition from images



