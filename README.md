# lainos_repo
A Pacman repository for the inclusion of Calamares installer during LainOS ISO build and for packages not included in the Arch Core, Extra, Community, and AUR repositories.

This is also where i'm hosting the Skid Kit(aka pentestiong toolkit), and hopefully, everything in my local repo fits so i don't have to use local repos anymore

To use this repo, append these lines to /etc/pacman.conf:

[lainos_repo]

SigLevel = Optional TrustAll

Server = https://github.com/The-LainOS-Project/lainos_repo/raw/main/x86_64/
