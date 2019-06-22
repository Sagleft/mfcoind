# MFCoind
Для тех кому лень компилировать MFCoin для CentOS из исходников или происходят какие-то ошибки.

## Установка
```
yum install -y epel-release
yum install autoconf automake boost-devel gcc-c++ git libdb4-cxx libdb4-cxx-devel libevent-devel libtool openssl-devel wget miniupnpc-devel patch
yum install -y git
cd /tmp
git clone https://github.com/Sagleft/mfcoind.git
cd mfcoind
mv MFCoind /usr/local/bin/
```
Первый запуск
```
MFCoind
```
Далее следуйте инструкциям.
