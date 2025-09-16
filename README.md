Handwritten Digit Recognition using CNN (MNIST) .

Overview :
This project implements and compares multiple Convolutional Neural Network (CNN) architectures for handwritten digit recognition using the MNIST dataset.

Dataset :
- MNIST dataset with 60,000 training images and 10,000 test images.
- Grayscale images, 28x28 pixels.
- Labels: digits from 0 to 9.

Models :
Four CNN models were built and evaluated:
1. **Model 1: Basic CNN.
2. **Model 2: CNN + Dropout (25%).
3. **Model 3: Deeper CNN with more filters.
4. Model 4: Deeper CNN + Dropout.

Results :
- Model 1 Accuracy: 99.06%  
- Model 2 Accuracy: 99.25%  
- Model 3 Accuracy: 99.05%  
- Model 4 Accuracy: 99.29% (Best)  

Tools & Libraries :
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

How to Run :
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
