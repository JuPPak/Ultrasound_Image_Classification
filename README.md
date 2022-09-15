# 🔦 Ultrasound_Image_Classifications

## 📌 Discription

> open source로 제공되는 ultrasound data들을 이용해서 classification 하는 모델을 구성해볼 예정

## 🎁 Datasets

### busi structure

```
├── train
│   ├── normal
│   ├── malignant
│   └── benign
├── test
│   ├── normal
│   ├── malignant
│   └── benign
├── all
│   ├── normal
│   ├── malignant
│   └── benign
```

## 📑 notebooks

### - busi_classifier
```
# version_0915 
  기본적인 3 class prediction하는 
  : basic classification (with timm or torchvision)
  : metrics (Acc, ROC curve, AUC, Classfication reports, Confusion Matrix)
  : k-fold validation (StratifiedKFold,..)
```
