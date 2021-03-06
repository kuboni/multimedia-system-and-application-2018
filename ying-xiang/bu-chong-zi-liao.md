# 補充資料

## Image

* Spatial domain
* Intensity domain

#### Color system

* RGB
* CMYK

#### Image acquisition

* Illumination \(energy\)  source
* Reflct
* f \(x,y\) = i\(x ,y\)  \* r\(x, y\) 

#### Three  types  of  images

* Binary  images
* Gray-scale images
* Colored image

#### Notation

* Intensity
* Brightness
* Grey-level

#### Weber law

![](../.gitbook/assets/download.gif)

* 強度越小感知越大

#### Nyquist freqency

* Nyquist Rule : 取樣率必須大於２f， f 為訊號之最高頻率
* Aliasing
  * ![](../.gitbook/assets/download.png)
  * e.g. Moire Patterns
    * ![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/16/Moire_on_parrot_feathers.jpg/160px-Moire_on_parrot_feathers.jpg)\(鸚鵡的翅膀\)
    * ![](https://insaneimpact.com/wp-content/uploads/2017/11/moire-gif.gif)
    * ![](https://swannsmith.com/wp-content/uploads/2013/04/concentric-lines.gif)
  * Image De-mosaicing

#### Digitalization

* Spatial Sampling
  * 取樣率 e.g. 512 x 512
  * Nyquist Rule
* Quantization
  * 8 bit, 16 bit ...
  * uniform quantization
  * non-uniform quantization
    * weber's law
    * ![](https://analogquantized.files.wordpress.com/2013/02/nonuniform_sampling.png?w=768&h=351)
  * Optimal Quantization \(Lloyd-Max\)
    * Lloyd-Max Quantizer
    * 依資料型態分佈分割

#### Image resolution & size

* ppi = pixel per inch \(未印出\)
* dpi = dots per inch \(印出\)

### Color Quantization

More

* Generalized Lloyd Algorithm \(GLA\)
* RGB
* CIELAB
* 人對於低頻誤差較敏感
  * solution : 賦予顏色權重

