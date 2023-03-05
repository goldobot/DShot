# DShot
Petite brique logicielle pour le contrôle des actionneurs acceptant le protocole DShot (pneumatique, balistique..)

README:
 - /!\ attention cette branche (dev_goldo) a ete reconfiguree pour utiliser un microcontroleur different de celui de Emeric => sur cette branche on utilise un STM32F303K8
 - /!\ attention ce projet utilise des makefiles et ne devrait marcher que sur Linux (Ubuntu)
 - pour flasher le firwmare sur la carte Nucleo utiliser la commande:
$st-flash write build/Goldo_new.bin 0x08000000

