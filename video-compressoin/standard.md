# Standard

## H. 261

![H.261 Frame sequence](../.gitbook/assets/image%20%2818%29.png)

* image compression -&gt; Motion compensation -&gt; MC -&gt; MC -&gt; IC -&gt; ....

### Intra-Frame \(I-Frame\) Coding

* Spatial redundancy removal
* 一段時間使用 \(避免錯誤擴大\)
* 
![I-Frame coding](../.gitbook/assets/image%20%2821%29.png)



### Inter-Frame \(P-Frame\) Predicting Coding

* Forward predicting coding
* Motion Vector Difference
  * MVD = MV\_prediction - MV\_current
* Non-motion  compensated macroblock
  * MV過大 \(場景轉換\)
* 
![p-frame coding](../.gitbook/assets/image.png)

### Quantization

![](../.gitbook/assets/image%20%2840%29.png)



