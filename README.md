# pfpp_vx_tools

Plan Formación Permanente Profesorado Videoxogos

## Requisitos

- docker
- docker-compose
- make

## unity

Creamos un directorio en nuestro directorio personal para los proyectos unity, el cual será mapeado en la ruta /opt/unity dentro del container:

```mkdir ~/unity```

Despliegue de imagen para ejecutar unity en docker container. Para levantar el escenario:

```make```

Para acceder al container:

```make sh service=unity```

Ejecución de UnityHub desde el container (con redirección de salida gráfica al host):

```UnityHub.AppImage --no-sandbox```
