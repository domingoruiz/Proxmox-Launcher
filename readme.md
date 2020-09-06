# Proxmox Launcher

Proxmox Launcher es una utilidad que nos permitira acceder de una forma rápida y sencilla a todas las máquinas virtuales de nuestros distintos servidores Proxmox sin tener que pasar por la interfaz web ni escribir las credenciales cada vez que se le de uso.

## Requisitos previos a la instalación
Para instalar esta aplicación debemos comprobar que tenemos los siguientes componentes instalados en nuestra máquina Linux:
- remote-viewer
- jq
- curl
- whiptail

## Instalación

Descargamos y colocamos el script Proxmox_Launcher en un lugar que nos sea cómodo, le damos permiso de ejecución y estará listo para ser usado.

```bash
git clone https://github.com/domingoruiz/Proxmox-Launcher.git
mv Proxmox-Launcher/ProxmoxLauncher /usr/bin/
chmod +x /usr/bin/ProxmoxLauncher
```

## Uso

Ejecutamos en terminal o a través de un acceso directo el comando Proxmox-Launcher y automáticamente se nos abrirá la aplicación dentro de la terminal.

```bash
ProxmoxLauncher
```

## Desarrollo
Aplicación desarrollada por Domingo Ruiz Arroyo <ordenadordomi@gmail.com>

## Licencia

Copyright 2020 Domingo Ruiz

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.