# grwrbunt
How to get root without root by ubuntu in termux

## What's This?

This is a script by which you can install Ubuntu in your termux application without a rooted device to get root access

## Updates
**• Updated to ubuntu 20.04**

### Installation steps
1. Update termux: `apt-get update && apt-get upgrade -y`
2. Install wget: `apt-get install wget -y`
3. Install proot: `apt-get install proot -y`
4. Install git: `apt-get install git -y`
5. Go to HOME folder: `cd ~`
6. Download script: `git clone https://github.com/alinikkhah1383/grwrbunt.git`
7. Go to script folder: `cd ubuntu-in-termux`
8. Give execution permission: `chmod +x ubuntu.sh`
9. Run the script: `./ubuntu.sh -y`
10. Now just start ubuntu: `./startubuntu.sh`
