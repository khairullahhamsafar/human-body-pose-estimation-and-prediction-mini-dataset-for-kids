# Human Body Pose Estimation and Prediction Mini Dataset for Kids

A small, kid-friendly human body pose dataset designed for teaching machine learning, computer vision, pattern recognition, and prediction concepts to children.

This dataset supports beginner AI activities such as pose classification and body movement prediction using tools like Google Teachable Machine.

## 📁 Dataset Structure

```text
human-body-pose-estimation-and-prediction-mini-dataset-for-kids/
├── Both_Hands_Normal/   # 5 training images
├── One_Hand_Up/         # 5 training images
├── Both_Hands_Up/       # 5 training images
└── Test_Set/            # 9 testing images
```

### Training Classes

- `Both_Hands_Normal`
- `One_Hand_Up`
- `Both_Hands_Up`

### Test Set

The `Test_Set` directory contains:

- 3 images of `Both_Hands_Normal`
- 3 images of `One_Hand_Up`
- 3 images of `Both_Hands_Up`

These images can be used to test a trained model and evaluate its prediction accuracy.

## 🎯 Purpose

This dataset is perfect for:

- Teaching machine learning to kids
- Learning about patterns and predictions
- Human body pose classification projects
- Introduction to computer vision concepts
- Google Teachable Machine activities
- Understanding how AI recognizes body movements

## 📊 Details

| Attribute | Value |
|-----------|---------|
| Classes | 3 pose classes |
| Training images per class | 5 |
| Total training images | 15 |
| Test images | 9 |
| Total images | 24 |
| Dataset size | Mini/small |
| Source | Selected from a larger pose-labeled dataset |

## 🤖 Learning Objective

Using this dataset, students can:

1. Train a simple pose recognition model
2. Learn how computers identify patterns in images
3. Understand how machine learning makes predictions
4. Test model accuracy using unseen images
5. Explore the relationship between data quality and prediction performance

## 🚀 Quick Start

```python
from pathlib import Path

dataset_dir = Path("human-body-pose-estimation-and-prediction-mini-dataset-for-kids")

for class_dir in dataset_dir.iterdir():
    if class_dir.is_dir():
        print(f"{class_dir.name}: {len(list(class_dir.glob('*')))} images")
```

## 🎮 Suggested Classroom Activity

Train a pose recognition model using the three pose classes and then use the images from `Test_Set` to see whether the model can correctly predict each pose.

Questions for students:

- Which pose was easiest to predict?
- Which pose was most confusing for the model?
- How does adding more training images improve predictions?
- What patterns did the computer learn to recognize?

## ⚠️ Notes

- Images were selected and prepared from a larger publicly available pose-labeled dataset
- Intended for educational purposes and beginner AI/ML projects
- Designed for teaching pattern recognition and prediction concepts
- Small size enables quick experimentation on local machines
- Suitable for classroom demonstrations and guided learning activities

## 📝 License

Public dataset for educational use.

## 🔍 Keywords

Machine Learning for Kids, AI for Kids, Computer Vision Dataset, Human Pose Dataset,
Pose Estimation, Pose Classification, Pose Recognition, Body Movement Detection,
Educational Dataset, Beginner Machine Learning Dataset, Teachable Machine Dataset,
Google Teachable Machine, AI Education, STEM Education, Kids Coding,
Image Classification Dataset, Human Action Recognition, Pattern Recognition,
Prediction Models, Supervised Learning, Training Data, Test Data,
Mini Dataset, Small Dataset, Classroom AI Activities, Computer Vision for Beginners

## 🏷️ Topics

#MachineLearning #ArtificialIntelligence #ComputerVision #PoseEstimation
#PoseRecognition #PoseClassification #TeachableMachine #GoogleTeachableMachine
#KidsAI #AIForKids #MachineLearningForKids #STEMEducation
#EducationalDataset #ImageClassification #HumanPoseDataset
#PatternRecognition #Predictions #SupervisedLearning
#DataScienceEducation #ComputerVisionEducation

## 👨‍💻 Author

Prepared and curated by **Khairullah Hamsafar** for educational and classroom learning purposes.

GitHub: https://github.com/<your-github-username>

Focused on making Machine Learning, Artificial Intelligence, Computer Vision, and Generative AI accessible to children and beginners.
