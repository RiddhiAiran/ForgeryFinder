# Forgery Finder: PAN Card Tampering Detection

## 📸 Project Overview
Forgery Finder is an advanced Computer Vision project designed to detect tampering in PAN (Permanent Account Number) cards. This innovative solution helps organizations verify the authenticity of identification documents submitted by employees, customers, or any other individuals.

## 🎯 Project Objectives
- Develop a robust image analysis system
- Detect potential manipulations in PAN cards
- Provide a reliable method for document verification
- Enhance organizational security through advanced image forensics

## 🛠 Technical Approach
The project employs sophisticated image processing techniques to identify potential forgeries:

1. **Image Acquisition**: Collect PAN card images from users
2. **Image Preprocessing**:
   - Validate image size and format
   - Resize and reshape images
   - Convert to grayscale
3. **Comparative Analysis**:
   - Calculate image similarity index
   - Determine image thresholds
   - Detect and analyze image contours
4. **Visualization**:
   - Draw boundary rectangles
   - Compare original and potentially tampered images
5. **Tampering Detection**:
   - Compare similarity scores
   - Make tampering determination

## 🔍 Key Features
- Automated PAN card authenticity verification
- Advanced computer vision algorithms
- Detailed image comparison techniques
- High precision tampering detection

## 📦 Installation

### Prerequisites
- Python 3.8+
- OpenCV
- NumPy
- Imutils

### Setup
```bash
git clone https://github.com/riddhiairan/ForgeryFinder.git
cd ForgeryFinder
pip install -r requirements.txt
```
