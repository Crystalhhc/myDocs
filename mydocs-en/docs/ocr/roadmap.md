# Roadmap

## Roadmap

```mermaid
graph TD
    A(Pahse 1 - OCR Service API) --> A1(Phase 2 - OCR Accuracy Improvement)
	A1 --> B[Phase 3 - Table Detection and Table Structure Recognition]
	A1 --> A2(Phase 4 - OCR Model Reconstruction)
	A2 --|OCR Accuracy Improved|-->A 

	B -->B1[Phase 5 - Document AI Model Building]
	B1 -->D{Document Type}
	D -->D1[Invoice]
	D -->D2[Receipt]
	D -->D3[Application Form]

	B1 -->B2[Phase 6 - Full Document Process Flow]


```

## Timeline
```mermaid
timeline
    title History of Social Media Platform
    2025/Q1 : Phase 1 - OCR API Service
			: Phase 2 - OCR Accuracy Improvement
			: Phase 3 - Table Detection and Table Structure Recognition
    2025/Q2 : Phase 4 -
         	: Google
    2025/Q3 : Youtube
    2025/Q4 : Twitter
```

## Phase 1 - OCR Service API
- To build a OCR microservice
- Version v. 0.1 
- Features
	- To upload an image file
	- To recognize the content to text using Tesseract OCR
- Tech Stacks
	- FastAPI
	- Celery
	- Redis Queue
	- Docker

## Phase 2 - OCR Accuracy Improvement
- To improve Tesseract ocr for Traditional Chinese character recognition
- Version: v. 0.2 
- Features
	- To recognize at least 12000 mostly used printed characters
- Tech Stacks
	- Machine Learning - Pytorch

## Phase 3 - Table Detection and Table Structure Recognition
- Go through a complete Table Detection workflow with an existed model
- Features
	- upload image file
	- Table Detection
	- Table Structure Recognition 
	- OCR
	- Export to Json
	- convert to a dataframe

## Phase 4 - OCR Model Reconstruction

- To improve Tesseract ocr for Traditional Chinese character recognition
- Version: v. 0.2 
- Features
	- To recognize at least 12000 most used printed characters
- Tech Stacks
	- Machine Learning - Pytorch

## Phase 5 - Document AI Model Building 


## Phase 6 - Full Document Process Flow
To create a Document Layout Parsing  → Json → HTML(Markdown)
Including:

- File upload
- Image Pre-processing
- Layout Parsing
- Reading Order
- OCR for Traditional Chinese
-  Conversion to : Json, Markdown, HTML
- FastAPI
- Deploy in AWS

## Phase 7 - Process Model
To improve OCR accuracy

## Phase 6 - Different Document Types
To include Auto-annotation with pre-trained model. Try to make the solution as a self-training loop.

## Phase 8
To Improve UI 