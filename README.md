## Installing on Virtual Machine

---

## Table of Contents
- [Software and Hardware](#id-specification)
- [Installaion Procedure](#id-installation)
- [Simulation Testing](#id-simulation)
- [Reference](#id-reference)

---

<div id='id-specification'/>

## Software and Hardware

### Hardware Specification
| Module           | Detail                                         |
| -----------      | -----------                                    |
| Operating System | Windows 11 Home 21H2                           |
| Processer        | 11th Gen Intel(R) Core (TM) i5-1135G7 @2.40GHz |
| RAM              | 16.0 GB                                        |
| Graphics Card    | Intel(R) Iris(R) Xe Graphics                   |
| Connectivity     | Intel(R) Wi-Fi 6 AX201 160MHz                  |

### Software Used
| Software      | Version                 |
| -----------   | -----------             |
| VirsualBox    | VirtualBox 6.1          |
| UERANSIM      | Release v3.2.5          |
| Ubuntu Server | Ubuntu Server 20.04 LTS |

---

<div id='id-installation'/>

## Installation Procedure

### 1. Create Virtual Machine
| Module      | Detail         |
| ----------- | -----------    |
| Memmory     | 2GB            |
| HDD         | 10GB           |
| Network     | Bridge Adapter |

### 2. Install and Setup Ubuntu Server

Clone this project
~~~ text
cd ~
git clone https://github.com/porrama/install_ueransim
~~~

Run **aptinstall_ueransim.sh**
~~~ text
cd ~/install_ueransim
sudo sh aptinstall_ueransim.sh
~~~

### 3. Install UERANSIM software

Clone UERANSIM project
~~~ text
cd ~
git clone https://github.com/aligungr/UERANSIM
~~~

Install
~~~ text
cd ~/UERANSIM
make
~~~

---

<div id='id-simulation'/>

## Simulation Testing

Run **gNodeB**
~~~ text
~~~ 

Run **UE**
~~~ text
~~~

---

<div id='id-reference'/>

### Reference
- [UERANSIM Documentation](https://github.com/aligungr/UERANSIM)

---
