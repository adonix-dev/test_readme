# TP ARCHI 1 - IDE ARM INSTALL

## TELECHARGER 
> **archive:**
> https://developer.arm.com/-/media/Files/downloads/gnu-rm/7-2017q4/gcc-arm-none-eabi-7-2017-q4-major-mac.tar.bz2?revision=7f453378-b2c3-4c0d-8eab-e7d5db8ea32e?product=GNU%20Arm%20Embedded%20Toolchain,64-bit,,Mac%20OS%20X,7-2017-q4-major


## CREER
> /usr/local/gcc_arm

## EXTRAIRE LE CONTENUE DANS 
> /usr/local/gcc_arm/gcc-arm-none-eabi-7-2017-q4-major/

## EXPORTER DANS LE PATH
> export PATH="$PATH:/usr/local/gcc_arm/gcc-arm-none-eabi-7-2017-q4-major/bin/"

## DANS LE MAKEFILE DU TP
Nom du fichier executable
> TARGET = tp1exo1

## Prefixe de la chaine de compilation
> TCHAIN = arm-none-eabi
