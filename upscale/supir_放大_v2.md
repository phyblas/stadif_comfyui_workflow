# 简单说明

使用[SUPIR](https://github.com/Fanghua-Yu/SUPIR)把图片放大。跟旧版比起来有分成很多节点。

不仅是用来放大。也可以把模糊的图片便清楚。

在resize（缩放）节点指定要输出的图片大小。

放大的结果算不错，但要花很长时间。只支持CUDA。

# 需要插件

- [kijai / ComfyUI-SUPIR](https://github.com/kijai/ComfyUI-SUPIR)
- - SUPIR_model_loader_v2
- - SUPIR_first_stage
- - SUPIR_encode
- - SUPIR_conditioner
- - SUPIR_sample
- - SUPIR_decode

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorTextNode

- [cubiq / ComfyUI_essentials](https://github.com/cubiq/ComfyUI_essentials)
- - ImageResize+

- [kijai / ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)
- - ColorMatch

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### SUPIR
- [SUPIR-v0Q_fp16](https://huggingface.co/Kijai/SUPIR_pruned/tree/main)