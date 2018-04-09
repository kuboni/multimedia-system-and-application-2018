#### 常見編碼方式

* time domain coding
* frequency domain coding
* linear predict coding
* homomorphic analysis

  * 同構分析
  * 拿掉訊號中的聲帶部份e\[n\]，取出聲道部份 h\[n\] =&gt; 辨認提昇

  * x\[n\] = e\[n\]\*h\[n\] --&gt;&gt; x\[n\] = e\[n\]+h\[n\]

  * ![](/assets/homomorphic-analysis.png)

  * -&gt; Cepstrum \(倒頻譜\)

#### Speech Coder

-

* loseless compression
* lossy compression

-

##### Speech coder 的兩種分類

* 波形編碼 \(wavform\)
  * time domain
  * frequency domain
* 音源編碼 \(source\)
  * linear predict coding

-

tradeoff

* bit rate &lt;-&gt; quality
  * quality 
    *  MOS \(mean opinion score\)
    * SNR \(signal to noise rate\)

-

##### scalar waveform coder

– Linear PCM

– $$\miu$$-law

– A-law PCM

– APCM

– DPCM

– DM





