# Proyecto Unitree ROS con Docker y Soporte NVIDIA

Este repositorio contiene una configuración Docker para ejecutar Unitree ROS con aceleración GPU.


## Requisitos
- Docker instalado
- Drivers NVIDIA en el host

## Uso
```bash
docker build -t unitree_ros .
docker run -it --gpus all unitree_ros
