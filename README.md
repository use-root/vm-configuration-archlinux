# Minimal Arch Linux Oracle Virtual Box ௹

This is my workflow for hacking, before I used `Kali-minimal` and if I would to say the differents are minimal. 

### Minimal recomendations:
```javaScript

RAM(Base Memory):4gb
Disk: 50GB
Procesors:3
Acceleration: Nested Paging, KVM Paravirtualization (If You in linux, you can use QEU + KVM Is 10x better).
Video-memory: 75MB
```


### Make the particions: 

Ok I use the structure like:

- '/boot' / '/boot/efi' (512MB<)
- '/root ' (30gb)
- '/home' (45gb)
- 'swap' (5-4gb) (Depend of your Ram, but if you have 4 so put 8gb or 6gb).

For arch I use: `cfdisk` and selected the GPT, I know I'm in vm but GPT is more actual that DOS, but you can choose what ever you want.

|hola|hola|
-----------
|jdkdk|kadsfasfd





When run your VM, you need to activate de 3d-aceleration `(Is recommendable)` 




#### Tiling Window Manager: **BSPWM + SXHKD**




- Terminal: **Alacritty**
- Picom
- Nvim 
- Bat : alias cat
- lsd : alias ls
- powerlevel10k: zsh-sudo (Script)
- shell: zsh
- rofi: launcher
- Uso de virtualboxguest: VBoxClient --clipboard

