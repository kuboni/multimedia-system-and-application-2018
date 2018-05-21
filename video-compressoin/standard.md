# Standard

## H. 261

![H.261 Frame sequence](../.gitbook/assets/image%20%2814%29.png)

* image compression -&gt; Motion compensation -&gt; MC -&gt; MC -&gt; IC -&gt; ....

### Intra-Frame \(I-Frame\) Coding

* Spatial redundancy removal
* 一段時間使用 \(避免錯誤擴大\)
* 
![I-Frame coding](../.gitbook/assets/image%20%2817%29.png)



### Inter-Frame \(P-Frame\) Predicting Coding

* Forward predicting coding
* Motion Vector Difference
  * MVD = MV\_prediction - MV\_current

