# Atomic Array 
This repository explores attention-based deep learning applied to atomic array representations for predicting and classifying bandgap of solid-state materials. Atomic arrays encode crystal structures into fixed-size tensors, providing a machine-readable representation of atomic arrangements. By integrating attention mechanisms into deep neural networks, the models are able to identify and emphasize the most relevant atomic interactions. This work aims to improve predictive performance over standard architectures and enhance interpretability in materials informatics workflows. The primary goal is to benchmark the effectiveness of attention-enhanced models for electronic property prediction. 

## Repository Contents
```text
AtomicArray_Model/
├── nnCoords2Properties_2.0.ipynb       # Main notebook with model implementation and evaluation
│    
├── data/      # Training and test datasets (limited due to file size)
├── models/    # Trained models (limited due to file size)
├── README.md
├── .gitignore
└── requirements.txt
```
---

## Dependencies

- Python 3.12.4  
- TensorFlow 2.17 
- keras   
- pandas  
- numpy  
- netron (optional)
  

> Use `pip install -r requirements.txt` to install all dependencies.

---

## Usage

All notebooks are interactive and can be run in Jupyter or Colab. 

## Datasets

The `data/` folder contains training and test sets. 

> Note: Trained model files and datasets are provided selectively due to their large size. Users can train models using the notebooks.

---

## Citation

This project extends prior research and tools developed by [Dr. Gomez Peralta ](https://github.com/gomezperalta) in the field of AI for materials science.


> Developed as part of a research internship at LANNBIO-CINVESTAV.

