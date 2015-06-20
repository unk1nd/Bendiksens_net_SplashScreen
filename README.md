# Bendiksens.net PlyMouth Splash Screen #

I made this plymouth boot screen for my ubuntu laptop.

# Install #

- Make /lib/plymouth/themes/unk1nd/
- Download the files in this folder
- sudo update-alternatives --install /lib/plymouth/themes/default.plymouth default.plymouth /lib/plymouth/themes/unk1nd/unk1nd.plymouth 100
- sudo update-alternatives --config default.plymouth
- Pick the unk1nd theme
- sudo update-initramfs -u
