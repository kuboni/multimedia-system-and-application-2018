---
description: ch9 supplement
---

# Edge Detection

## Spatial Mask

g\(x,y\) = T\[f\(x,y\)\]

![convolution of spatial ](../.gitbook/assets/image%20%282%29.png)

## Edge Detection

> identify sudden change

using convolution

![](../.gitbook/assets/image%20%2828%29.png)

* associative in convolution
* 
![associative](../.gitbook/assets/image%20%2833%29.png)

![](../.gitbook/assets/image%20%2822%29.png)

{% hint style="info" %}
smooth derivative remove noise, but blurs edge.
{% endhint %}

## Design an edge detector

* good detection
  * find all real edges
  * ignore noise
  * ignore artifacts
* good localization
  * close to true edge
  * return only one point for edge
* Cues:
  *  color, intensity, texture
  * continuity and closure
  * high-level knowledge....etc.

## Operator

### Laplacian Operator

* one dimension function

![](../.gitbook/assets/image%20%2826%29.png)

![](../.gitbook/assets/image%20%2817%29.png)

* two-dimension function

![](../.gitbook/assets/image%20%2839%29.png)

![](../.gitbook/assets/image%20%2830%29.png)

![](../.gitbook/assets/image%20%2835%29.png)

### Sobel Operator

![](../.gitbook/assets/image%20%2812%29.png)

* Advantage
  * implement 容易
  * 整數計算
* Drawback
  * 雜訊敏感
  * 準確率不穩定 \(3x3\)

## Pre-Processing

### Histogram Equalization

經由 以下轉換

> s = T\(r\),  0≤r ≤L−1

* T\(r\)  single-valued and monotonically increasing in the interval 0 ≤ r ≤ L − 1
*  0 ≤ T\(r\) ≤ L − 1 for 0 ≤ r ≤ L − 1

### Noise Reduction

### Morphology

