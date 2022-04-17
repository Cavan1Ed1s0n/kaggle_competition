# Introduction

This folder is all the code from this [competition](https://www.kaggle.com/competitions/classification-of-plants-of-southeast-asia) of our team.

# What to do next?

1. metric: F1 score,...
2. k can sampling
3. chia theo class, thu voi cac cach split: 80-20,95-5,...
4. chay n lan de thong ke ket qua tinh gia tri giao dong cua metric

# What to do now?

Chọn 3 model sau để thống kê: alexnet, resnet, vgg16

Tất cả đều train với 5 epoch, batchsize 64

Metric để đánh giá: F1 score, recall, precision, accuracy

1. Train với unbalanced dataset, split 80-20 (train, val). Train 5-10 lần để thống kê.

   -> kết luận: overfit với unbalanced dataset

2. Oversampling data, split 80-20 (train, val). Train 5-10 lần để thống kê.

   -> kết luận: kết quả tốt hơn. -> Chọn dc model tốt nhất

3. Train với các split khác nhau: 50-50, 80-20, 95-5,...

   -> đưa ra thống kê
