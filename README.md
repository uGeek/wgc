# wgc
Create clients and Wireguard server configuration

## Download
```
mkdir -p /etc/wireguard ; cd /etc/wireguard
```

```
wget https://raw.githubusercontent.com/uGeek/wgc/master/wgc
```

```
sudo chmod +x wgc
```

```
./wgc
```



## Help
```
wgc
Crea clientes y configuración del servidor Wireguard 

./wgc    [Nombre del dispositivo]     Crea clientes de wireguard
./wgc -sr                              Crea archivo de configuración del servidor wireguard para Raspbian
./wgc -sd                              Crea archivo de configuración del servidor wireguard para Debian
./wgc -su                              Crea archivo de configuración del servidor wireguard para Ubuntu
 
./wgc -ir                             Instalar Wireguard en Raspbian
./wgc -id                             Instalar Wireguard en Debian
./wgc -iu                             Instalar Wireguard en Ubuntu
 
 
wgc v0.6 
```

## Contact

If you want to contact me you can reach me at https://ugeek.github.io.

## License

This project uses the following license: [MIT License](https://choosealicense.com/licenses/mit/).

