# Introduction

This folder is all the code from this [competition](https://www.kaggle.com/competitions/classification-of-plants-of-southeast-asia) of our team.

# What to do next?

1. metric: F1 score,...
2. k can sampling
3. chia theo class, thu voi cac cach split: 80-20,95-5,...
4. chay n lan de thong ke ket qua tinh gia tri giao dong cua metric

# What to do now?

> Ai train rồi update kết quả vào bảng nhé. Trong mỗi ô điền với định dạng: `lần train 1, lần train 2,....`

Chọn 3 model sau để thống kê: alexnet, resnet, vgg16

Tất cả đều train với 5 epoch, batchsize 64

Metric để đánh giá: F1 score, recall, precision, accuracy

1. Train với unbalanced dataset (data dữ nguyên không làm gì), split 80-20 (train, val). Train 5-10 lần để thống kê.
   | Model | F1 score | recall | precision | accuracy |
   |:-----|:--------:|:------:|:---------:|:--------:|
   | Resnet | x | x | x | 0.5238, |
   | Alexnet | x | x| x| x |
   | VGG16 | x| x| x | x |

   -> kết luận: overfit với unbalanced dataset

2. Oversampling data (augmentation data), split 80-20 (train, val). Train 5-10 lần để thống kê.
   | Model | F1 score | recall | precision | accuracy |
   |:-----|:--------:|:------:|:---------:|:--------:|
   | Resnet | x | x | x | x |
   | Alexnet | x | x| x| x |
   | VGG16 | x| x| x | x |

   -> kết luận: kết quả tốt hơn. -> Chọn dc model tốt nhất

3. Train với các split khác nhau: 50-50, 80-20, 95-5,... Train 5-10 lần để thống kê.
   | Model | F1 score | recall | precision | accuracy |
   |:-----|:--------:|:------:|:---------:|:--------:|
   | Resnet 50-50 | x | x | x | x |
   | Resnet 80-20 | x | x | x | x |
   | Resnet 95-5 | x | x | x | x |
   | Alexnet 50-50 | x | x| x| x |
   | Alexnet 80-20 | x | x| x| x |
   | Alexnet 95-5 | x | x| x| x |
   | VGG16 50-50 | x| x| x | x |
   | VGG16 80-20 | x| x| x | x |
   | VGG16 95-5 | x| x| x | x |

   -> đưa ra thống kê
