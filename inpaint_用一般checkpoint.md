# 简单说明

按照[官方的inpaint例子](https://comfyanonymous.github.io/ComfyUI_examples/inpaint/)来改一下。

采用DeepTranslatorCLIPTextEncodeNode来做自动翻译并使用SaveImagePlus来保存为jpg扩展。

但效果不如[用controlnet inpaint来做内补](https://github.com/phyblas/stadif_comfyui_workflow/blob/master/workflow/controlnet_inpaint.json)。

# 需要插件

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型