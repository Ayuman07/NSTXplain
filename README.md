# Neural Style Transfer with Explainable AI (XAI)

This repository presents an implementation of Neural Style Transfer (NST) enhanced with Explainable AI (XAI) techniques to analyze and interpret the contributions of content and style features in the style transfer process.

The project focuses on improving the interpretability of neural style transfer models through layer-wise analysis and ablation-based validation.

---

## Project Overview

Neural Style Transfer combines the content of one image with the artistic style of another using deep convolutional neural networks. Although the generated results are visually compelling, traditional NST methods offer limited insight into how different network layers influence the final output.

This work addresses this limitation by providing a structured explainability framework.

---

## Key Features

- Implementation of Neural Style Transfer using a pretrained convolutional neural network  
- Separate computation of content loss and style loss  
- Layer-wise attribution analysis for style features  
- Explainability-driven ablation studies  
- Visualization of loss convergence behavior  

---

## Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Google Colab  

---


## How to Run

1. Open `NST_XAI.ipynb` in Google Colab  
2. Upload the required content and style images  
3. Run all cells sequentially  
4. Analyze the generated stylized images and explainability results  

---

## Explainability and Ablation Study

- Layer-wise style losses are normalized to obtain relative attribution scores  
- Multiple configurations are evaluated, including:
  - All selected layers  
  - Shallow layers only  
  - Mid-level layers only  
  - Deep layers only  
  - Selective layer exclusion  
- The study highlights how different CNN depths capture distinct stylistic characteristics  

---

## Results

- Stable convergence of total loss after initial optimization iterations  
- Balanced integration of content and style objectives  
- Clear interpretation of stylistic influence across network layers  
- Validation of explainability results through ablation experiments  

---

## Use Case

This project is suitable for academic research, coursework, explainable AI demonstrations, and computer vision studies, including IEEE-style research publications.

---

## Future Enhancements

- Extension of explainability analysis to other CNN architectures  
- Quantitative evaluation of perceptual quality  
- Real-time neural style transfer with interpretability  
- Integration with advanced vision models  

---

## Author

Ayushmaan Dutta

---

## License

This project is intended for educational and research purposes.



