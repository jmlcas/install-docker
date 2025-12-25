# install-docker.sh
Script for install docker 
## 🎥 Video Tutorial

A step-by-step video walkthrough of this project is available on YouTube:  
👉 https://youtu.be/blHg8IcRZ08

The video explains how to use the script and shows the full installation process in real time.
### Docker Installation Script 

This script automates the installation of Docker on Linux systems. It checks whether Docker is already installed, and if not, it installs Docker along with its required dependencies.

Requirements

    Internet connection to download Docker packages
    Root or sudo privileges to install packages

Installation Steps

    Copy the script into a new .sh file, for example install_docker.sh.
    Give the script execute permissions:

chmod +x install_docker.sh

Run the script:

    ./install_docker.sh

Notes

    The script automatically handles the entire Docker installation process, including adding the Docker repository and GPG key.
    If Docker is already installed, the script will exit and notify you that Docker is already present on your system.

License

This script is open source. Feel free to modify or distribute it as needed.
