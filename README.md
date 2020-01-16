# fectch-
Instalasi React Native
Perhatian !!! Tutorial instalasi yang saya buat menggunakan sistem operasi Linux , jika kamu menggunakan sistem operasi lain seperti windows or mac kamu bisa cari referensinya di bawah ini :

Windows
Mac
Install NodeJs
$ sudo apt update
$ sudo apt install nodejs
$ nodejs -v
Install npm
$ sudo apt install npm
$ npm -v
Install Java JDK
$ sudo apt install openjdk-8-jdk openjdk-8-jdk-headless openjdk-8-jre
Cek JDK
$ javac -version
Cek JRE
$ java -version
Install Android SDK
Menambahkan direktori ~/Android/Sdk ke dalam file ~/.bashrc , agar perintah android dapat digunakan pada terminal.
Buka file ~/.bashrc dengan nano
$ nano ~/.bashrc
Lalu pada bagian akhir tambahkan baris ini
export ANDROID_HOME=$HOME/Android/Sdk
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
export PATH=$PATH:$ANDROID_HOME/platform-tools
Tekan Ctrl+x untuk keluar dan pilih y untuk menyimpan
Cek Android Version
$ android --version
Install React Native
$ sudo npm install -g react-native-cli
