Attribute Information: (class attribute has been moved to last column)
-- -----------------------------------------
1. Sample code number id number
2. Clump Thickness 1 - 10
3. Uniformity of Cell Size 1 - 10
4. Uniformity of Cell Shape 1 - 10
5. Marginal Adhesion 1 - 10
6. Single Epithelial Cell Size 1 - 10
7. Bare Nuclei 1 - 10
8. Bland Chromatin 1 - 10
9. Normal Nucleoli 1 - 10
10. Mitoses 1 - 10
11. Class: (2 for benign, 4 for malignant)
Chú ý là cột 11 chính là label của tập training (2 là u lành, 4 là u ác). Chọn negative class là
u lành và positive class là u ác.

Chia tập dữ liêu trên ra 2 phần train và test theo tỉ lệ 7:3. Xây dựng các mô hình Logistic
Regression, Decision Trees, và Random Forest. Giả sử chúng ta dự đoán đây là u ác nếu
xác suất u ác lớn hơn hoặc bằng 0.5. Với mỗi mô hình, tính
- False Positive Rate, False Negative Rate
- Precision, Recall, Accuracy
- AUC
Mô hình nào cho AUC lớn nhất
