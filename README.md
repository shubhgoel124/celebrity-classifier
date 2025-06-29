# 🧠 Sports Celebrity Image Classifier

A machine learning project that classifies sports celebrities from images using OpenCV, Wavelet Transforms, and Scikit-learn. 

## 🏆 Celebrities Covered

- Maria Sharapova  
- Serena Williams  
- Roger Federer  
- Virat Kohli  
- Lionel Messi



## 🧪 Model Pipeline

1. **Face Detection**: OpenCV Haar cascade detects faces with at least 2 eyes.
2. **Feature Extraction**:
   - Raw grayscale image
   - Wavelet transformed image
3. **Modeling**:
   - Combined features passed into `LogisticRegression`
   - GridSearchCV used for tuning
