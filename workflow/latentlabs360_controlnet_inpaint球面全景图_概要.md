# 简单说明

使用[LatentLabs360](https://civitai.com/models/10753/latentlabs360) LoRA来做球面全景图。用controlnet inpaint来修补。

提示词必须包含“a 360 equirectangular panorama”。

这个工作流有点复杂。比较推荐采用tiled_ksampler的方法。

不能使用SDXL模型。

# 需要插件

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [WASasquatch / was-node-suite-comfyui](https://github.com/WASasquatch/was-node-suite-comfyui)
- - Image Blank

- [kijai / ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)
- - ImageConcanate

- [Fannovel16 / comfyui_controlnet_aux](https://github.com/Fannovel16/comfyui_controlnet_aux)
- - InpaintPreprocessor

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### LoRA
- [LatentLabs360](https://civitai.com/models/10753/latentlabs360)