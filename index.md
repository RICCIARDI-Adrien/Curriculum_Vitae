# Ingénieur informaticien/électronicien systèmes embarqués

## Compétences

* **Informatique :** Programmation de microcontrôleurs sans système d'exploitation, bootloader, développements kernel et drivers Linux, Linux embarqué, développement userspace POSIX, développement Qt, développement QML.
* **Electronique :** Electronique logique, microcontrôleurs, robotique mobile.
* **Langues :** *Anglais :* lu, écrit, parlé (880 au TOEIC en juin 2012); *Italien :* bilingue.
* **Langages :** C, C++, assembleur x86, assembleur PIC, shell, GNU makefile.
* **Plateformes :** Linux, BSD, Windows, [bare metal](https://en.wikipedia.org/wiki/Bare_machine).
* **CAO électronique :** KiCad (schématique et routage), Autodesk EAGLE (schématique et routage), Cadence OrCAD (schématique).
* **Microcontrôleurs :** Microchip PIC16 et PIC18, Silicon Labs C8051 et EFM8 (coeurs 8051), Atmel ATmega328P, STM32, ESP32.
* **SoC / coeurs :** Broadcom BCM283x (Raspberry Pi), Freescale i.MX 6, x86, MIPS 4K, Z80, plusieurs expériences sur Raspberry Pi Compute Module.
* **Bus :** Bus classiques de microcontrôleurs (I2C, UART, SPI...), PCI, USB, CAN, CAN FD.
* **Linux embarqué :** Buildroot, OpenWRT.
* **RTOS :** Zephyr, Trampoline
* **Gestionnaires de sources :** git, svn.

## Expériences professionnelles

* **2021/actuellement :** Ingénieur R&D Informatique chez [BayLibre](https://baylibre.com). Conception hardware, revue de schémas, développement de logiciels embarqués sur microcontrôleurs 8 et 32 bits, Linux embarqué, développement de drivers Linux, portage de distributions Linux sur des cartes spécifiques, développement Qt. Voici quelques projets majeurs :
  * **Portage d'une carte Intel sur une nouvelle version de Zephyr RTOS :** Portage d'une carte propriétaire de Zephyr 2.6 à Zephyr 3.5, mise à jour Device Tree, correction de drivers, optimisation, debug bas niveau (MMU, locking) et de certains périphériques (UART, I2C, SPI, ...). Travail sur simulateur.
  * **Ajout de l'architecture Renesas R-Car S4 au RTOS Trampoline :** Participation à la conception et à l'implémentation de l'architecture des drivers de l'OS, conception et implémentation de la stack CAN et CAN FD, création de drivers multi-architectures pour le bloc CAN/CAN FD.
  * **Preuve de concept CBQRI RISC-V :** Participation à la revue de la spécification Capacity and Bandwidth QoS RISC-V et implémentation de la preuve de concept sous Linux qui permet de valider la spécification.
  * **Bringup d'une carte d'automate Linux pour centrale photovoltaïque :** Tests électriques et logiciels de tous les périphériques de la carte (USB, CAN, RS485, RS232, eMMC, RAM, ...) et correctifs/améliorations dans le BSP Linux et sur la carte.
  * **Carte d'acquisition et diffusion audio pour communication VoIP :** Conception d'une carte avec micro, haut-parleur et actuateurs pour de la communication VoIP. Interfaçage de la carte avec un SoM via I2S pour l'audio. Traitements analogiques de l'acquisition du micro et de la sortie haut-parleur.
  * **Amélioration et fiabilisation de drivers CAN/CAN FD sur voiture autonome :** Debug, amélioration, fiabilisation du driver Linux sous Buildroot et découverte d'un bug dans le silicium sur le module CAN/CAN FD d'un SoC destiné aux voitures autonomes. Travail sur simulateurs FPGA puis sur première révision silicium de la puce finale.
  * **Jeu électronique pour enfant :** Portage de fonctionnalités tournant sur un SoC MIPS sous Linux vers un ESP32 tournant sous FreeRTOS. Ajout de fonctionnalités (roaming WiFi, serveur Bluetooth LE avec fonctionnalités spécifiques, ...), et optimisation (meilleure utilisation des cycles CPU, diminution de la consommation mémoire, stabilité des pilotes, ...).
  * **Migration du SDK Texas Instrument :** Participation à la migration du SDK officiel basé sur Yocto de Texas Instruments du kernel Linux 5.4 au kernel Linux 5.10.
* **2018/actuellement :** Inventeur, concepteur, développeur et mainteneur du gestionnaire de mots de passe matériel [Hoplite Key Manager](https://hoplitekeymanager.com/index-fr). Hardware, microcontrôleurs, C, C++, Qt multi-plateformes, déploiement multi-plateformes, cryptographie, sécurité.
* **2017/2020 :** Ingénieur Développement chez [Electronie](http://www.electronie.fr). Conception hardware, schématique, routage, développement de logiciels embarqués sur microcontrôleurs 8 et 32 bits, développement de drivers Linux et portage de distributions Linux sur des cartes spécifiques, conception et réalisation de cartes basées sur SoC Linux, développement Qt.
* **2014/2017 :** Ingénieur Développeur chez SFR. Développement de la box [NB6VAC](https://assistance.sfr.fr/internet-tel-fixe/box-plus/caracteristiques-techniques-box-plus-de-sfr.html) (connue sous le nom de "la box Plus de SFR") : debug hardware; conception et développement du firmware du microcontrôleur embarqué; développement de drivers Linux; portage, intégration et optimisation de la partie VoIP.
* **2013/2014 :** Stage de fin d'études de six mois en entreprise (SFR, anciennement Efixo), portage du bootloader U-Boot sur une box.
* **2012/2013 :** Stage de trois mois en entreprise (Efixo, R&D de SFR), étude et modification d'un accélérateur de paquets réseau.
* **2011/2012 :** CDD d'un mois en entreprise (Nexvision SAS, entreprise française spécialiste du monde de la vision électronique), développement en C++ de l'architecture d'un serveur de streaming.
* **2011/2012 :** Stage d'un mois en entreprise, participation à la conception d'un serveur de streaming pour plateformes embarquées et écriture de documents techniques (Nexvision SAS).
* **2010/2011 :** CDD d'un mois en entreprise, participation au développement d'un automate programmable pour le marché industriel (NexIO de Nexvision SAS).
* **2010/2011 :** Stage d'un mois en entreprise, participation à la conception et à la programmation d'un TAG ZigBee pour le monde de l'industrie (NexTag de Nexvision SAS).

## Formation

* **2011/2014 :** Polytech Marseille (ex Ecole Supérieure d'Ingénieurs de Luminy), Marseille, Filière Informatique, Réseaux et Multimédia.
* **2009/2011 :** IUT Université Paul Cézanne III, Marseille, Département Génie Electrique et Informatique Industrielle (GEII).
* **2008/2009 :** Lycée Frédéric Joliot-Curie, Aubagne, Baccalauréat scientifique Sciences de la Vie et de la Terre option Sciences de la Vie et de la Terre, mention assez bien.

## Centres d'intérêt

* **Sport :** Pratique du Judo et du Jiu-Jitsu pendant 10 ans (ceinture marron), natation, randonnées.
* **Passions :** La programmation, Linux, le bricolage, la littérature.
