# LinuxMint
=============== instalando jdk8 mint ===================
1º - sudo apt install openjdk-8-jdk
2º - closed terminal
3º - sudo update-alternatives --config java
  3.1 - choose version 8
  #configurando variavel de ambiente.
4º - sudo nano /etc/environment
5º - JAVA_HOME="/usr/lib/jvm/java-8-oracle"
6º - source /etc/environment
7º - echo $JAVA_HOME
=============== instalando android studio ==============
1º - software manager 
  1.1 - find android studio
  #instalar kvm
  sudo apt install qemu-kvm
  whoami
2º - sudo adduser anderson kvm
3º - sudo chown anderson /dev/kvm

  #ver usuario

3º - sudo chown $USER /dev/kvm
  #configurando variavel de ambiente.
4º - sudo nano /etc/environment
5º - paste and sabe
export ANDROID_HOME=$HOME/Android/Sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
export PATH=$PATH:$ANDROID_HOME/platform-tools
============== instalando node/yarn====================
sudo apt-get install curl python-software-properties
curl -sL https://deb.nodesource.com/setup_12.x | sudo bash -
sudo apt-get install nodejs
curl -o- -L https://yarnpkg.com/install.sh | bash
============== react-native cli =======================
npm install -g react-native-cli 
============== gimp ===================================
1º - software manager 
  1.1 - find gimp

  
  1.2 - inkscape
  1.3 - steam
  1.4 - discord
  1.5 - steam
  1.6 - claro videos
  1.7 - netflix
  
