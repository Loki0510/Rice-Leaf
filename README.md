# Rice-Leaf
Rice leaf disease detection
Here's a README file for your GitHub repository based on your project "Rice Plant Leaf Disease Prediction using Transfer Learning-based Ensemble Deep Learning Models":  

# Rice Plant Leaf Disease Detection  

## Project Overview  
This project aims to develop a deep learning-based system for detecting and classifying rice leaf diseases using an ensemble model. The model leverages pre-trained architectures such as VGG16, InceptionV3, and MobileNet to enhance classification accuracy. This system helps in early disease detection, enabling farmers to take timely actions to mitigate crop losses.  

## Features  
- Ensemble Model: Combines predictions from VGG16, InceptionV3, and MobileNet for improved accuracy.  
- Deep Learning & Transfer Learning: Utilizes pre-trained models to improve classification performance.  
- Data Augmentation & Preprocessing: Enhances dataset quality and generalization.  
- Web Application: Allows users to upload leaf images for disease detection.  
- Performance Metrics: Evaluated using accuracy, precision, recall, and F1-score.  

## Dataset  
The dataset consists of 16,000 rice leaf images categorized into four classes:  
1. Healthy  
2. Leaf Smut 
3. Bacterial Leaf Blight  
4. Brown Spot  

### Dataset Preprocessing  
- Resizing: Standardized to 224x224 pixels.  
- Augmentation: Includes rotation, width/height shift, zooming, and flipping.  
- Normalization: Scaled pixel values between 0 and 1.  

## Model Architecture  
- Feature Extraction: Uses VGG16, InceptionV3, and MobileNet.  
- Concatenation: Features are merged into a single vector.  
- Fully Connected Layers: Dense layers are used for classification.  
- Softmax Activation: Produces probability distributions for class predictions.  

## Performance  
| Model               | Accuracy  |  
|---------------------|----------|  
| Proposed Ensemble Model | 97% |  
| VGG16              | 92%      |  
| InceptionV3        | 94%      |  
| MobileNet          | 94%      |  

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/rice-leaf-disease-detection.git
   cd rice-leaf-disease-detection
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the web application:  
   ```bash
   python app.py
   ```  

## Usage  
1. Open the web app in your browser.  
2. Upload a rice leaf image.  
3. Click "Predict" to classify the disease.  

**Future Enhancements**  
Mobile App Integration  
IoT-based real-time disease detection
Support for multiple crops
