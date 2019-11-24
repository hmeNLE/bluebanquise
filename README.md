# BlueBanquise
![BlueBanquise Logo](resources/pictures/BlueBanquise_logo_large.svg)

## The stack

**BlueBanquise** is an **Ansible** based stack, designed to deploy and manage large group of hosts.

Main target is High Performance Computing, but stack is generic and can adapt to any kind of architecture (University or Enterprise network, render farm, etc.).

Currently supported OS are:

* Fully supported:
  * RedHat/Centos 7.6
  * RedHat/Centos 8.0

* Ready to be included if demand (PXE ready):
  * Ubuntu 18.04
  * OpenSuse Leap 15.1

Debian is dropped for now because we fail to install it through PXE (modules conflicts).

Ansible >= 2.8.2 is mandatory for BlueBanquise to run properly.

**[OpenHPC](https://openhpc.community/downloads/)** scientific packages and OpenHPC slurm job scheduler are compatible with the stack.

BlueBanquise is part of the **Algoric** Project from the [**Fabrique du Loch**](https://www.lafabriqueduloch.org/fr/accueil/) FabLab.

![BlueBanquise Logo](resources/pictures/FabriqueDuLochAlgoric_logo_large.svg)

BlueBanquise is a revamping of the old stack [Banquise](https://github.com/oxedions/banquise), based on Salt.

## The name

You may wonder where this name comes from:

* [BlueBanquise](https://en.wikipedia.org/wiki/File:Blue_iceberg_in_the_Ilulissat_icefjord.jpg)
* [Blue Iceberg](https://en.wikipedia.org/wiki/Blue_iceberg)

## Thanks

Special thanks:

* to [CINES](https://www.cines.fr/en/) who provided Algoric team with hardware to develop this stack.
* to [@remyd1](https://github.com/remyd1) for his help on [Banquise](https://github.com/oxedions/banquise) original stack.
* to [@bouriquet15](https://github.com/bouriquet15) for his active help on the stack.
