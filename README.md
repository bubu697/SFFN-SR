

# SFFN: Scale-aware Implicit Fourier-in-Fourier Network for Arbitrary-Scale Image Super-Resolution



------



## 📢 News & Status



- 

------



## 🚀 Abstract





------



## 🖼️ Method Overview



*Figure 1: Architecture of the proposed SFFN framework. It consists of the ESDC module for adaptive scale perception and the NFTB for efficient frequency-domain texture reconstruction.*

------



## 📈 Performance



SFFN achieves state-of-the-art performance on the **DIV2K** validation set and standard benchmarks (**Set5, Set14, B100, Urban100**) across both in-distribution ($\times2$-$\times4$) and out-of-distribution ($\times6$-$\times30$) scales.

| **Method**      | **Scale**  | **Params (M)** | **Inference Time (ms)** | **PSNR (dB)** |
| --------------- | ---------- | -------------- | ----------------------- | ------------- |
| CiaoSR          | $\times 4$ | 2.65           | 242                     | 26.92         |
| CLIT            | $\times 4$ | 16.91          | 843                     | 26.92         |
| **SFFN (Ours)** | $\times 4$ | **4.09**       | **94**                  | **26.91**     |

*> Note: Inference time is averaged over 100 runs on a 256x256 input using an NVIDIA L20 GPU.*

------



## 📅 To-Do List



- [ ] Release training and inference code.
- [ ] Release pretrained models (EDSR-baseline & SwinIR backbones).
- [ ] Provide a demo script for arbitrary-scale upsampling.

------



## 📝 Citation



If you find our work helpful, please consider citing:

代码段

```
@article{pan2025sffn,
  title={SFFN: Scale-aware Implicit Fourier-in-Fourier Network for Arbitrary-Scale Image Super-Resolution},
  author={Pan, Ming},
  journal={arXiv preprint arXiv:xxxx.xxxxx},
  year={2025}
}
```

*(BibTeX will be updated upon publication)*

------



## 📧 Contact



If you have any questions, please feel free to contact me at `[241516071006@zufe-edu.cn]`.






