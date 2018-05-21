# Wavelet-Based Coding

* decompose input signal
  * 分解成較好處理
  * 或特殊處理
  * 或Threshold（去極）

## Continuous Wavelet Transform

* integral  f\(x\)  = 0
* mother wavelet \(母小波\) : 用於 scaling
* 
![](../.gitbook/assets/image%20%2813%29.png)

## Discrete Wavelet Transform

* 一樣有 mother wavelet transform
* filter banks
* 
![](../.gitbook/assets/image%20%285%29.png)

以 2 的倍數去做平移、縮放

### multi-resolution analysis

* 將訊號分成兩大部份
  * smoother
    * scaling function
  * coarser
    * wavelet function

#### scaling function

* dilation function
* 
![](../.gitbook/assets/image%20%281%29.png)

## Wavelet Type

### mexican-hat wavelet

![](../.gitbook/assets/image%20%286%29.png)

### Orthogonal wavelet

![](../.gitbook/assets/image%20%289%29.png)

### Biorthogonal wavelet

![](../.gitbook/assets/image%20%2838%29.png)



## 1D Wavelet Transform

block diagram​ of 1D Dyadic Wavelet Transform

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LAlAgwHSv5LZoYRtnBx%2F-LBtJtczoYtCQSuTsZIq%2F-LBtMMoE_OZAdsaRCsQn%2Fimage.png?alt=media&token=eec19862-0718-4833-8d04-2e7ae791b0d9)

![](../.gitbook/assets/image%20%2829%29.png)



## 2D Wavelet Transform

* 如圖示

![](../.gitbook/assets/image%20%2825%29.png)

