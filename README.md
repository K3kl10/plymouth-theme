# Theme plymouth au couleurs de YUMI.
Sur la base des travaux de @adi1090x (https://github.com/adi1090x/plymouth-themes/).<br><br>
Je vous partage un bootloader pour YUMI SmartPad - Wanhao-klipper-pad.<br> 
Voici le lien pour vous en procurer un: <br>
https://wanhao-europe.com/collections/yumi-smart-pad/products/wanhao-klipper-pad?variant=50407737786708

![illustration](./Yumi.gif)

# Information sur l'utilisation et l'installation

En premier lieu, vous devez récupérer le dossier du github.

- clone:
  ```
  git clone https://github.com/K3kl10/yumi-plymouth-theme.git
  ```

Puis pour l'installation: 

- Copiez et renommez le dossier dans le dossier de theme plymouth :
  ```
  sudo cp -r  yumi-plymouth-theme /usr/share/plymouth/themes/yumi
  ```
- Vérifiez s'il y est vraiment :
  ```
  sudo plymouth-set-default-theme -l
  ```
- Définissez le theme yumi par défaut et reconstruisez le démarrage du smartpad :
  ```
  sudo plymouth-set-default-theme -R yumi
  ```
- Pour visualiser le theme (il est conseiller d'avoir plymouth-X11):
  ```
  sudo ./showplymouth.sh 20
  ```
- sinon exécutez simplement :

  ```
  sudo reboot
  ```

- Et voyez ce que cela donne sur votre smartpad !
