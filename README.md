# Handwriting-recognition-CNN-and-DNN-

## MNIST手寫數字辨識 - CNN和DNN

本專案使用Keras在MNIST資料集上實現了CNN和DNN模型,用於手寫數字辨識。

###  資料集
使用MNIST資料集,包含60,000張28x28的手寫數字訓練圖片和10,000張測試圖片。

### 使用套件
Keras
Numpy
Matplotlib

### 主要步驟
1. 資料集預處理：將圖片reshape為28x28x1
2. 構建CNN/DNN模型
3. 編譯及訓練模型
4. 評估模型在測試集上的指標
5. 列印訓練過程指標

### 網路結構
-  CNN模型：包含卷積層、池化層、全連接層
-  DNN模型：包含全連接層

### 結果討論
CNN能夠更好地提取圖像的空間特徵，因此其識別準確率高於DNN。可以嘗試新增網路層、調參等方法來進一步提升DNN模型的效果。
