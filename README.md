# Configuraciones Cyberpunk para Arch Linux

Este repositorio contiene mis configuraciones personalizadas para mi sistema Arch Linux con un tema inspirado en el estilo cyberpunk.

## Contenido

- **.config**: Directorio que contiene las configuraciones de varias aplicaciones, como gestores de ventanas, navegadores, editores de texto, etc.
- **.xprofile**: Archivo de configuración del perfil X que se ejecuta al iniciar sesión en X11. Contiene ajustes de configuración del entorno de escritorio y variables de entorno.
- **themes**: Directorio que almacena los temas personalizados para diferentes aplicaciones y componentes del sistema.
- **pkglist.txt**: Lista de paquetes instalados desde los repositorios oficiales de Arch Linux.
- **pkglist-aur.txt**: Lista de paquetes instalados desde el AUR (Arch User Repository).

## Uso

Puedes usar estos archivos y configuraciones en tu propio sistema Arch Linux si deseas experimentar con un tema cyberpunk o simplemente para inspirarte en cómo personalizar tu propio entorno.

### Instalando los paquetes

Si quieres instalar los paquetes listados en `pkglist.txt` en tu sistema, puedes usar los siguientes comandos:

#### Oficiales
Para instalar paquetes desde los repositorios oficiales de Arch Linux:
```
pacman -S - < pkglist.txt
```
Si deseas omitir la instalación de paquetes ya instalados, puedes usar la opción `--needed`:
```
pacman -S --needed - < pkglist.txt
```
#### AUR

Para instalar paquetes desde el Arch User Repository (AUR) usando `yay`:
```
yay -S - < pkglist-aur.txt
```

## Contribuciones

Si tienes sugerencias de mejoras o nuevas configuraciones que podrían agregarse, ¡no dudes en contribuir! Siéntete libre de enviar un pull request o abrir un issue con tus ideas.

## Agradecimientos

Agradezco a la comunidad de Arch Linux por proporcionar una base sólida para construir y personalizar mi sistema operativo.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más detalles.
