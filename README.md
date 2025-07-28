# GhostPWM

Despliega un entorno de hacking profesional para Kali Linux ejecutando solo un script.

## Instalación y uso

- Se recomienda el uso de una instalación nueva/limpia de Kali Linux.
- Testado en Kali Linux 2025.1 con VMware, VirtualBox y Bare Metal.

```
git clone https://github.com/f4ntasma/ghostpwm.git
cd ghostpwm
bash kalipwm.sh
sudo reboot
```
- Una vez reiniciado cambia a bspwm en la pantalla de inicio de sesión
- El fondo de pantalla se toma de ~/Wallpapers/wallpaper.*

## Comandos

> [!NOTE]
> En MacOS, cambia Windows por Command, y Alt por Option.

| Comando                     | Descripción                                                 |
|-----------------------------|-------------------------------------------------------------|
| Clic derecho en Polybar     | Cambia el tema de Polybar usando el menú del clic derecho   |
| Windows + 1,2,3,4           | Navega entre escritorios                                    |
| Windows + Enter             | Abre una nueva terminal                                     |
| Windows + Enter             | Divide la terminal actual                                   |
| Windows + Flechas           | Navega entre ventanas abiertas                              |
| Windows + Tab               | Cambia entre los dos escritorios más recientes              |
| Windows + + Shift + W       | Cierra la terminal actual                                   |
| Windows + Alt + R           | Recarga el entorno de escritorio                            |
| Windows + Alt + Q           | Reiniciar BSPWM                                             |
| Windows + Alt + Flechas     | Redimensiona la ventana actual                              |
| Windows + Shift + F         | Abre Firefox                                                |
| Windows + Shift + B         | Abre Burp Suite                                             |
| Windows + Shift + A         | Abre el gestor de archivos Thunar                           |
| Windows + Shift + 1,2,3,4   | Mueve la ventana actual a otro escritorio                   |
| Windows + Shift + Flechas   | Mueve la ventana actual                                     |
| Ctrl + Shift + -+           | Cambia el tamaño del texto en la terminal                   |
| Ctrl + T                    | Abre un buscador avanzado desde la terminal                 |
| .config/sxhkd/sxhkdrc       | Archivo de configuración de atajos (sxhkd)                  |
| .config/bspwm/bspwmrc       | Archivo de configuración de BSPWM                           |
| .config/polybar             | Carpeta con temas de Polybar                                |
| .config/kitty/kitty.conf    | Archivo de configuración predeterminado para el terminal Kitty  |
| ~/Wallpapers                | Carpeta de fondos de pantalla. Solo se permite un archivo llamado wallpaper.jpg  |
| target 10.0.0.1             | Selecciona una IP de destino y se muestra en la Polybar     |
| target reset                | Elimina el objetivo seleccionado                            |
| tmux                        | Cambia la terminal a tmux                                   |
| tmux —help                  | Muestra la ayuda de tmux                                    |
| p10k configure              | Configura el tema de terminal Powerlevel10K                 |
| .zshrc                      | Archivo de configuración de ZSH y alias de comandos         |
| bpython                     | Python interactivo en la terminal                           |

## Paquetes incluídos:

```
Bspwm
Polybar
Oh my zsh + Plugins
Powerlevel10k
Hack Nerd Fonts
JetBrains Font
Python + pip + bpython
Tmux + Oh my tmux
Kitty
lsd
Batcat
Fastfetch
Scrot
feh
Rofi
Sxhkd
Picom
Neovim
```

## Créditos
- Autor:       Ghost 
- Instagram:   <a href="https://www.instagram.com/angel_low03/">Ghost</a>
- Tiktok:     <a href="https://www.tiktok.com/@ghost_zzz03">Ghost</a>

## Soporte

<a href="https://ko-fi.com/f4ntasma" rel="nofollow"><img width="250" align="left">
![buy-me-a-coffe](https://github.com/user-attachments/assets/8c8f9e81-334e-469e-b25e-29888cfc9fcc)
</a>
