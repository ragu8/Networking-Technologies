# NS-3.36.1 Installation Guide

This guide provides step-by-step instructions for installing NS-3.36.1 on an Ubuntu-based system. Please make sure you have administrative privileges and a working internet connection before you begin.
## 1. Update Package Repositories

Open a terminal and run the following commands:

```
sudo apt update
```

## 2. Install Prerequisites

Install the necessary packages by running:

```

sudo apt install g++ python3 python3-dev pkg-config sqlite3 cmake python3-setuptools git qtbase5-dev qtchooser qt5-qmake qtbase5-dev-tools gir1.2-goocanvas-2.0 python3-gi python3-gi-cairo python3-pygraphviz gir1.2-gtk-3.0 ipython3 openmpi-bin openmpi-common openmpi-doc libopenmpi-dev autoconf cvs bzr unrar gsl-bin libgsl-dev libgslcblas0 wireshark tcpdump sqlite sqlite3 libsqlite3-dev libxml2 libxml2-dev libc6-dev libc6-dev-i386 libclang-dev llvm-dev automake python3-pip libxml2 libxml2-dev libboost-all-dev
```
## 3. Download NS-3

Download ns-allinone-3.36.1.tar.bz2 from nsnam.org.

You can use the command line:

```
wget https://www.nsnam.org/releases/ns-allinone-3.36.1.tar.bz2
```
## 4. Extract NS-3

Navigate to your home folder and extract the downloaded file. You can do this using the GUI by right-clicking and selecting "Extract" or use the following command:

```
tar jxvf ns-allinone-3.36.1.tar.bz2 -C ~/
```
## 5. Build NS-3

Change to the extracted directory:

```
cd ~/ns-allinone-3.36.1/
```
Run the build script with options to enable examples and tests:
```
./build.py --enable-examples --enable-tests
```

# NS-3.36.1 Installation Guide using Bash Script 

## 1. Clone the Repository
```
git clone https://github.com/ragu8/Networking-Technologies
```
## 2. Change Directory
```
cd Networking-Technologies
```
## 3. Add Execute Permissions
```
chmod +x ns3.sh
```
## 4. Run the Bash Script
```
bash ns3.sh

```

# Executing C++ Program

## Navigate to NS-3 Directory

```
cd ns-3.36.1

```
## Command to Execute C++ Program

```
./ns3 run scratch/filename

```
# Executing Python Program

## Navigate to NS-3 Directory

```
cd ns-3.36.1
```
## Command to Execute Python Program

```
./ns3 run scratch/filename.py
```




