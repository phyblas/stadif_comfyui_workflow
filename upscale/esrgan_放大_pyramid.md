# 简单说明

使用esrgan（Enhanced Super-Resolution Generative Adversarial Networks）把原本图片放大2倍、4倍、8倍而拿来做对比。

# 需要插件

- [kijai / ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)
- - ImageConcatMulti

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### upscale
- [RealESRGAN_x2](https://huggingface.co/ai-forever/Real-ESRGAN/blob/main/RealESRGAN_x2.pth)
- [RealESRGAN_x4](https://huggingface.co/ai-forever/Real-ESRGAN/blob/main/RealESRGAN_x4.pth)
- [RealESRGAN_x8](https://huggingface.co/ai-forever/Real-ESRGAN/blob/main/RealESRGAN_x8.pth)