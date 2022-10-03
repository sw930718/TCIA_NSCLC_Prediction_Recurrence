## Chest CT Images  
**Data** : TCIA([The Cancer Imaging Archive](https://www.cancerimagingarchive.net/))의 비소세포폐암(NSCLC) 환자 100명(재발68명,무재발32명)의 수술 전 흉부 CT영상 
  
**feature**   
- CT 이미지에서 종양 기준으로 160X160(Pixel)로 Crop 
- Feature Extraction: Histogram, Texture, Shape 등 총 104개의 Radiomics feature   
- Feature Selectioin: 중요도 상위 20, 40, 60, 80, 80, 104개로 구분하여 학습 및 비교 

**Classification Model**
- LDA(Linear Discriminant Analysis)  
- SVM(Support Vector Machine)  
- RF(Random Foreast)
- GB(Gradient Boosting)   

**Metrics**
- Accuracy  
- Sensitivity   
- Specificity  
- PPV  
- NPV  
