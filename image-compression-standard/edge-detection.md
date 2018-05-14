---
description: ch9 supplement
---

# Edge Detection

## Spatial Mask

g\(x,y\) = T\[f\(x,y\)\]

![convolution of spatial ](../.gitbook/assets/image%20%281%29.png)

## Edge Detection

> identify sudden change

using convolution

![](../.gitbook/assets/image%20%2819%29.png)

* associative in convolution
* 
![associative](../.gitbook/assets/image%20%2823%29.png)

![](../.gitbook/assets/image%20%2815%29.png)

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

