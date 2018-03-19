### Light and Spectra

* 光
  * 電磁波
  * 人：可見光波段
* Spectrophotometer
  * ![](https://upload.wikimedia.org/wikipedia/commons/f/f7/NormSPD.png)
  * SPD - Spectral Power Distribution

### Human Vision

* 三種視錐神經 \(RGB\) - cone cell
* 一組視桿細胞矩陣 \(Grey Level\) - rod cell

### Spectral Sensitivity of the Eye

* 接收藍色的頻段較小
* RGB cone cell -&gt; luminous efficiency function

### Image Formation

### Camera Systems

### Gamma Correction

* gamma-corrected
* ![](https://cg2010studio.files.wordpress.com/2011/12/gamma3.png?w=378&h=378)
  * Vin &lt; 0.018, Vout = 4.5 x Vin
  * Vin &gt;= 0.018, Vout = 1.099 x \(Vin^0.45\) 0.099

### Color Matching Function

* Color Primaries
  * Red
  * Green
  * Blue
* colorimeter 
* CIE RGB color-matching function
  * ![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/CIE1931_RGBCMF.svg/650px-CIE1931_RGBCMF.svg.png)

### CIE chromaticity Diagram

chromatic: 色度

* 在 Color-matching function 中存在負值的部份，因此改以CIE standard XYZ color-matching function表示
* ![](/assets/import.png)

* CIE chromaticity diagram

  * CIE 1931 color space

  * ![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/60/CIE1931xy_CIERGB.svg/495px-CIE1931xy_CIERGB.svg.png)

  * E : white point

### Color Monitor Specification

### Out-of-Gamut Colors

gamut 範圍

* RGB值中有負值

  * 人眼可見、機器不能顯
  * solution :  
  * 1. in-gamut color 

    ![](/assets/in-gamut.png)  
    2. closest complementary color

* Grassman's Law

  * 顏色可線性相加

  * \[R1, G1, B1\] + \[R2, G2, B2\] = \[R, G, B\]

##### subtractive color vs additive color 顏色系統

| subtractive color | additive color |
| :--- | :--- |
| 印表機 | 投影機 |
| ![](/assets/add.png) | ![](/assets/sub.png) |

### 

### 

### White Point Correction

##### 問題

從 XYZ 系統 map 到 RGB 需要進行修正，使得白點相互對應皆為1

correction factor

### XYZ to RGB Transform

* T = M D

![](/assets/TMD.png)

### Transform with Gamma Correction

### L\*a\*b \(CIELAB\) Color Model

* L 
* A
* B
* ![](/assets/CIELAB.png)
* 與人類感知的色彩差距一致



