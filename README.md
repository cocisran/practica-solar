# Practica-solar

En esta práctica aprenderas a usar ROS2 en conjunto con redes neuronales para obtener información del entorno de un robot con camara

##  Prerrequisitos

Los organizadores deberan proporcionarte una rasperry py que cuente con los nodos: watcher_pub y server_img_delivery activos y corriendo. Es importante que todos se encuentren conectados a la misma red de internet.

El encargado de la practica les propocionará tambien un servicio configurado para la rasppery de cada equipo, el cual contiene una red neuronal para detectar polvo en un panel solar.

Clonar este repositorio en un pc que tenga la versión de ros que se indique.

## Comandos utiles
```bash
# Obtener los recursos de ROS
source /opt/ros/<ros_version>/setup.bash

# Construye el paquete 
colcon build --symlink-install --packages-select <package_name>

# Correr un ejecutable de ROS
ros2 run <package_name> <node|script_name> 
```