# alci-iso
inspired by https://github.com/arch-linux-calamares-installer

artix-linux-calamares-installer is a bare bones framework for designing custom Artix Linux ISO's with a GUI installer which uninstalls itself and the
graphical environment on completion. 
We can interrupt this process, stop the removal of the GUI and then proceed to add our own configs to the mix, effectively making our own spin on Artix Linux.

# For Builders:
You can direclty install AUR packages onto the root filesystem without compiling them by appending their names to `AUR_PACKAGES` file.
