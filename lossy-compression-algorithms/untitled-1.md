# Embedde Zerotree of Wavelet Coefficients \(EZW\)

E - Embedded encoding

Z - Zero tree

W - Wavelet transform

* 基本概念
  * multi-resolution
  * 方法
    * 設定 threshold \(臨界值\)
      * wavelet &gt; threshold ? 1:0
  * ![](blob:https://popo.gitbook.io/e411f333-86c3-4cfc-834e-f1d972ffa11c) 

### Zero Tree

* quad tree
  * 例外 : root node
* hypothesis
  * 在相同方位下，所有子孫皆為 0 ，則稱為 zero tree
* 演算法

1.  DWT 2-D image
2. 用 threshold 的方式Progressively處理
3. ​編碼 \(e.g. 算術編碼\)





