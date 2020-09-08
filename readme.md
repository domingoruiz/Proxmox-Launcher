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


Este proyecto se publica bajo la licencia MIT. Consulte el archivo [LICENSE] para obtener más detalles.