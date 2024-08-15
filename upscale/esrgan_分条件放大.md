# 简单说明

使用esrgan（Enhanced Super-Resolution Generative Adversarial Networks）把原本图片放大到指定的大小。有分段条件用不同的esrgan模型。
2倍以下：RealESRGAN_x2
大于2倍而4倍以下：RealESRGAN_x4
大于4倍：RealESRGAN_x8

节点有点复杂。包含很多要安装的插件。

# 需要插件

- [WASasquatch / was-node-suite-comfyui](https://github.com/WASasquatch/was-node-suite-comfyui)
- - Text String

- [ltdrdata / ComfyUI-Impact-Pack](https://github.com/ltdrdata/ComfyUI-Impact-Pack)
- - ImpactInt
- - ImpactFloat
- - ImpactCompare
- - ImpactConditionalBranch

- [cubiq / ComfyUI_essentials](https://github.com/cubiq/ComfyUI_essentials)
- - GetImageSize+

- [jamesWalker55 / Various ComfyUI Nodes by Type](https://github.com/jamesWalker55/comfyui-various)
- - JWIntegerDiv
- - JWImageResizeByFactor

- [Suzie1 / ComfyUI_Comfyroll_CustomNodes](https://github.com/Suzie1/ComfyUI_Comfyroll_CustomNodes)
- - CR String To Combo

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### upscale
- [RealESRGAN_x2](https://huggingface.co/ai-forever/Real-ESRGAN/blob/main/RealESRGAN_x2.pth)
- [RealESRGAN_x4](https://huggingface.co/ai-forever/Real-ESRGAN/blob/main/RealESRGAN_x4.pth)
- [RealESRGAN_x8](https://huggingface.co/ai-forever/Real-ESRGAN/blob/main/RealESRGAN_x8.pth)