# Utils
## QEMU
Dal terminale, dare
```
wget https://raw.githubusercontent.com/atvacs/utils/master/installa-qemu
sh installa-qemu
```
Lo script scaricherà tutti i file necessari per il funzionamento di qemu nella cartella `~/qemu`. Per avviarlo basterà quindi chiamare lo script di startup presente nella stessa cartella
```
./start-arm
```
Se siete su WSL con [VcXsrv](https://sourceforge.net/projects/vcxsrv/), consiglio di modificare `start-arm` inserendo in cima, dopo `#!bin/bash`, la riga
```
export DISPLAY=127.0.0.1:0
```
per evitare di doverla riscrivere ogni volta.
