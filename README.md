# pfpp_vx_tools

Plan Formación Permanente Profesorado Videoxogos

## unity

Despliegue de imagen para ejecutar unity en docker container. Para levantar el escenario:

```make```

Para acceder al container:

```make sh service=unity```

Ejecución de UnityHub desde el container (con redirección de salida gráfica al host):

```/opt/unity/UnityHub.AppImage --no-sandbox```
