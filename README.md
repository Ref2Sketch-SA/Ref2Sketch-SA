## Ref2Sketch-SA

This is official implementation of the paper **"Ref2Sketch-SA"**

**Anonymous submission**

## Demos

###  Examples of Ref2Sketch-SA on in-the-wild images

<p align="center">
  <img src="figures/sub_fig3.jpg">
</p>

###  Examples of Ref2Sketch-SA on Flickr-Faces-HQ Datase

<p align="center">
  <img src="figures/sub_fig4.jpg">
</p>

###  Illustration of variable sketch outputs generated from the same content and reference style by adjusting the β parameter.

<p align="center">
  <img src="figures/fig4.jpg">
</p>

###  Qualitative ablation study results

<p align="center">
  <img src="figures/sub_fig0.jpg">
</p>


### Comparison with Previous Works

<p align="center">
  <img src="figures/fig5.jpg">
  <img src="figures/sub_fig1.jpg">
</p>


## Download
Follow [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter?tab=readme-ov-file#download-models) to download pre-trained checkpoints from [here](https://huggingface.co/h94/IP-Adapter).

```
git clone https://github.com/Ref2Sketch-SA/Ref2Sketch-SA.git
cd Ref2Sketch-SA

# download the models
git lfs install
git clone https://huggingface.co/h94/IP-Adapter
mv IP-Adapter/models models
mv IP-Adapter/sdxl_models sdxl_models
```


---
## Acknowledgements
Ref2Sketch-SA is highly built on [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter) and [InstantStyle](https://github.com/InstantStyle/InstantStyle). Additionally, we also acknowledge [StyleID](https://github.com/jiwoogit/StyleID) for Inversion processes.
