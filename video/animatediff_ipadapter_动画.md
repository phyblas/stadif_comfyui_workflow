# 简单说明

用animatediff和ipadapter，从一张图片跟提示词来生成动画。

# 需要插件

- [cubiq / ComfyUI_IPAdapter_plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus)
- - IPAdapterModelLoader
- - IPAdapterAdvanced

- [Kosinkadink / ComfyUI-AnimateDiff-Evolved](https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved)
- - ADE_AnimateDiffLoaderWithContext

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Kosinkadink / ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite)
- - VHS_VideoCombine

# 需要模型

### ipadapter
- [ip-adapter_sd15_light_v11](https://huggingface.co/h94/IP-Adapter)

### animatediff
- [mm-Stabilized_mid](https://huggingface.co/manshoety/AD_Stabilized_Motion/blob/main/mm-Stabilized_mid.pth)

### clip_vision
- [CLIP-ViT-H-14-laion2B-s32B-b79K](https://huggingface.co/h94/IP-Adapter/tree/main/models/image_encoder)
（下载model.safetensors，然后改名为CLIP-ViT-H-14-laion2B-s32B-b79K.safetensors）