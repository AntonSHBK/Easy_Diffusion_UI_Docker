# Easy_Diffusion_UI_Docker
[Install documentation Easy-Diffusion](https://github.com/easydiffusion/easydiffusion?tab=readme-ov-file#installation)
Install:
```bush
docker-compose up --build
```

Running:
```bush
docker ps
docker exec -it stable_diffusion_ui_docker-easy_diffusion-1 bush
```
where `stable_diffusion_ui_docker-easy_diffusion-1` name container in docker.

Run UI:
```bush
cd /app/easy-diffusion
./start.sh
```