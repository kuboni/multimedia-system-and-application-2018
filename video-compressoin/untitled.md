---
description: 運動向量
---

# Motion Vector

* 兩個frame中最小的差異，即為 Motion Vector

## Sequential Search

* 每次都要搜尋 \(2p+1\) x \(2p+1\) 的size
* full search
* highly cost
* O\(p^2 N^2\)

## 2-D logarithmic Search

* cheaper
* suboptimal 
* 類似 binary search
* O\(log p N^2\)

## Hierarchical Search

* multi-resolution
* 降低解析度做搜尋

## different way speed comparison

![](../.gitbook/assets/image%20%2820%29.png)

