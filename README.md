Ici on trouvera le  moyen de faire booté windows 10 et une distribution linux avec Grub2 ceci passera par les etapes suivante : 

	1) Faire un coup de os-prober
	2) Metre a jour grub2 avec update-grub2
	3) Modifier le nouveau fichier de configuration dans /boot/grub/grub.cfg chercher "chainloader /EFI/Microsoft/Boot/bootmgfw.efi" modifier ici Microsoft par ex : "MS-Microsoft" puis enregistrer
	4) puis aller dans /boot/efi/EFI/ et modifier le nom du dossier Microsoft par MS-microsoft 
	5) Pour finir redemare le pc vous remarque qu'il boot sur Grub et non plus directement sur Windows apres vous avez le choix de booté sur windows ou la distribution linux de votre choix

Voila voila sa devrais marcher ici vous trouverais un exlample de fichier de configuration Grub avec Debian Jessie et WIndows 10.
