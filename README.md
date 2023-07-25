# Masterclass_QIB2023
Microbes, Microbiomes and Bioinformatics MRC DTP MRC CLIMB-BIG-DATA

## Pre-requisites for the Microbiome day, 28th July 2023

We will explore a dataset in Anvio. Please download the software.

### 1. Download anvio. 
You can follow the full installation instructions (https://anvio.org/install/#4-check-your-installation), but they often fail. This is why we will use a Docker container:

- 1.1. Install docker in your mac. If you have a M1/M2 chip, please run:
````bash
softwareupdate --install-rosetta
````

- 1.2 Download docker installer for mac:
https://docs.docker.com/desktop/install/mac-install/

- 1.3 From the terminal, download anvio using docker
````bash
docker pull meren/anvio:7.1_main_0522
````
