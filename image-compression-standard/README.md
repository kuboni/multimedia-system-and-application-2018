---
description: ch9
---

# image compression standard

## JPEG

* joint photographic experts group
* lossy image compression
  * DCT
  * 觀察1:有效的影像資訊不會做跳進的改變
  * 觀察2:物理上，低頻相較高頻來得容易察覺
  * 觀察3:\(visual acuity 敏銳度\) 對灰階的敏銳度比色彩

### JPEG main step



![JPEG encoder](../.gitbook/assets/image%20%2833%29.png)

* DCT on image block
  * blocky
* Quantization

![](../.gitbook/assets/image%20%282%29.png)

### Quantization

### AC

RLC \(run-length coding\)

![](../.gitbook/assets/image%20%2822%29.png)

### DPCM

### Entropy Coding

#### Huffman Coding for DPCM

#### Huffman Coding for AC



### Common JPEG Mode

* sequential mode
  * right-to-left
  * top-to-bottom
* progressive mode
  * low quality first
  * high quality next
  * 作法
    * spectral selection
    * successive approximation
* hierarchical mode
  * encode low resolution first
  * Algorithm \(encode\)
    * reduce image resolution
    * compress low-resolution image F4
    * compress difference image d2
    * compress difference image d1
  * Algorithm \(decode\)
    * decompress the encode low-resolution image F4
    * Restore image ~f2 the intermediate  resolution
    * Restore image ~f1 the original resolution
* lossless mode

