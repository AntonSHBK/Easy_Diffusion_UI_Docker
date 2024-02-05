# Stable_Diffusion_UI_Docker
[Установка](https://github.com/easydiffusion/easydiffusion?tab=readme-ov-file#installation)

```bush
bash <(wget -qO- https://raw.githubusercontent.com/AUTOMATIC1111/stable-diffusion-webui/master/webui.sh) -f
wget https://huggingface.co/runwayml/stable-diffusion-v1-5/resolve/main/v1-5-pruned.ckpt
```
Примечание: Библиотека Xformers предоставляет дополнительный метод для ускорения генерации изображений:
```bush
./webui.sh --xformers
```
