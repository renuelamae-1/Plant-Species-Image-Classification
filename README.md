# 🌸 Plant Species Image Classification (Terrestrial Orchids)

## 📌 Project Overview

This project focuses on building an image classification model using Google Teachable Machine to identify 20 different terrestrial orchid species. The goal is to train a machine learning model that can accurately classify orchid images based on their visual characteristics such as flowers, leaves, and structure.

---

## 🌿 Plant Species

### 1. Paphiopedilum (Slipper Orchids)

![Paphiopedilum](images/plants/1.jpg)
Paphiopedilum are known for their unique slipper-shaped pouch and are popular ornamental orchids.

### 2. Cypripedium (Lady’s Slipper Orchids)

![Cypripedium](images/plants/2.jpg)
Cypripedium orchids are terrestrial orchids with pouch-like flowers and are commonly found in temperate regions.

### 3. Bletilla striata (Chinese Ground Orchid)

![Bletilla striata](images/plants/3.jpg)
A hardy terrestrial orchid known for its purple flowers and ease of cultivation.

### 4. Calanthe

![Calanthe](images/plants/4.jpg)
Calanthe orchids produce multiple flowers and thrive in tropical and subtropical regions.

### 5. Habenaria

![Habenaria](images/plants/5.jpg)
Habenaria orchids often have intricate flower shapes and are widely distributed.

### 6. Orchis

![Orchis](images/plants/6.jpg)
Orchis species are known for their colorful flowers and are commonly found in Europe and Asia.

### 7. Dactylorhiza

![Dactylorhiza](images/plants/7.jpg)
These orchids are recognized for their spotted leaves and dense flower spikes.

### 8. Eulophia

![Eulophia](images/plants/8.jpg)
Eulophia orchids are tropical terrestrial orchids with tall flowering stems.

### 9. Anacamptis

![Anacamptis](images/plants/9.jpg)
Anacamptis orchids are known for their vibrant pink and purple flowers.

### 10. Ophrys (Bee Orchids)

![Ophrys](images/plants/10.jpg)
Ophrys orchids mimic insects in appearance to attract pollinators.

### 11. Spiranthes (Ladies’ Tresses)

![Spiranthes](images/plants/11.jpg)
These orchids have spiral arrangements of small white flowers.

### 12. Goodyera (Jewel Orchids – Terrestrial Type)

![Goodyera](images/plants/12.jpg)
Goodyera orchids are valued for their patterned leaves and subtle flowers.

### 13. Epipactis

![Epipactis](images/plants/13.jpg)
Epipactis orchids are adaptable and found in a wide range of habitats.

### 14. Phaius tankervilleae

![Phaius tankervilleae](images/plants/14.jpg)
Also known as Nun’s Orchid, it produces large and showy flowers.

### 15. Spathoglottis

![Spathoglottis](images/plants/15.jpg)
A common tropical terrestrial orchid often used in landscaping.

### 16. Chloraea

![Chloraea](images/plants/16.jpg)
Chloraea orchids are native to South America and have striking greenish flowers.

### 17. Ponerorchis

![Ponerorchis](images/plants/17.jpg)
Small terrestrial orchids commonly found in East Asia.

### 18. Cremastra

![Cremastra](images/plants/18.jpg)
These orchids grow in forested areas and produce elegant flowers.

### 19. Sobralia

![Sobralia](images/plants/19.jpg)
Sobralia orchids resemble bamboo and produce large flowers.

### 20. Galeandra

![Galeandra](images/plants/20.jpg)
Galeandra orchids can be terrestrial or epiphytic and have long floral spurs.

---

## ⚙️ Model Training Details

* **Platform:** Google Teachable Machine
* **Project Type:** Image Classification
* **Epochs:** 50
* **Batch Size:** 16
* **Learning Rate:** 0.001
* **Images per Class:** 250
* **Total Images:** 5,000+

---

## 📊 Model Evaluation

### Confusion Matrix

![Confusion Matrix](images/training/confusion_matrix.png)

### Accuracy per Class

![Accuracy per Class](images/training/accuracy_per_class.png)

### Overall Accuracy

![Overall Accuracy](images/training/overall_accuracy.png)

---

## 🧪 Model Testing (Preview Results)

### Test 1

![Test 1](images/testing/test1.png)

### Test 2

![Test 2](images/testing/test2.png)

### Test 3

![Test 3](images/testing/test3.png)

### Test 4

![Test 4](images/testing/test4.png)

### Test 5

![Test 5](images/testing/test5.png)

### Test 6

![Test 6](images/testing/test6.png)

### Test 7

![Test 7](images/testing/test7.png)

### Test 8

![Test 8](images/testing/test8.png)

### Test 9

![Test 9](images/testing/test9.png)

### Test 10

![Test 10](images/testing/test10.png)

---

## 📦 Model Export

The trained model was exported from Google Teachable Machine in TensorFlow format and uploaded to this repository.

---

## 📁 Repository Contents

* README.md
* Model files (TensorFlow)
* Dataset screenshots
* Training screenshots
* Evaluation screenshots
* Testing screenshots

---

## ✍️ Reflection

### 1. Effect of Number of Images per Class

Increasing the number of images per class improved the model’s accuracy by allowing it to learn more variations of each plant.

### 2. Misclassified Species

Some species like Orchis and Dactylorhiza were misclassified due to similar flower structures and colors.

### 3. Training Parameters Impact

Higher epochs improved accuracy but risked overfitting, while batch size and learning rate helped stabilize training.

### 4. Challenges Encountered

Collecting diverse and non-duplicate images was difficult and time-consuming.

### 5. Future Improvements

Improving dataset quality, adding more distinct species, and increasing image diversity would enhance model performance.

---

## 🔗 Model Link

[https://teachablemachine.withgoogle.com/models/zBVfxh0le/](https://teachablemachine.withgoogle.com/models/zBVfxh0le/)
