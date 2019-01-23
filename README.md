# MFCoind
Для тех кому лень компилировать MFCoin для CentOS из исходников или происходят какие-то ошибки.

## Установка
```
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
...не работает. 
```
MFCoind: error while loading shared libraries: libboost_system.so.1.53.0: cannot open shared object file: No such file or directory
```
напишите мне в t.me/sagleft как дописать этот readme
