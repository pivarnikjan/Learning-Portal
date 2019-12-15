# Installation steps

1. Download `Ubuntu` image <br>
https://www.wikihow.com/Install-Ubuntu-on-VirtualBox

2. Install `VirtualBox` guest additions <br>
https://www.maketecheasier.com/install-guest-additions-in-virtualbox/

3. Install `Pycharm`
  
4. Install `GIT`
    ```bash
    sudo apt-get install -y git
   ```
   
5. Generate `SSH` key-pair <br>
https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

6. Install `node.js` <br>
https://tecadmin.net/install-latest-nodejs-npm-on-ubuntu/

7. Install `truffle` <br>
https://www.codeooze.com/blockchain/ethereum-dev-environment-2019/
    ```bash
    sudo npm install -g truffle
    ```
   a. Install solc
   ```bash
   truffle obtain --solc=0.5.8
   ``` 
   
   b. check truffle version
   ```bash
   truffle version
   ```

8. Install `ganache` <br>
https://www.codeooze.com/blockchain/ethereum-dev-environment-2019/

    a. Install GTK (dependency for ganache)
    ```bash
   sudo apt-get install libgtk2.0-0 
   ```
   b. Install GTK Canberra module
   ```bash
   sudo apt-get install libcanberra-gtk-module
   ```
   
9. Install `Metamask` firefox/chrome extension

    a. init truffle
    ```bash
   truffle init 
   ```
   b. run truffle
   ```bash
   truffle develop
   ```
   c. copy seed to Metamask