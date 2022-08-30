# Cambio de hora Ubuntu 20.04 LTS - Chile septiembre 2022.
```
wget http://ftp.us.debian.org/debian/pool/main/t/tzdata/tzdata_2022c-1_all.deb
sudo dpkg -i tzdata_2022c-1_all.deb
sudo dpkg-reconfigure tzdata #Seleccionar America -> Santiago.
zdump -v America/Santiago | grep 2022
```

