# Paquete DEB vx-dga-l-pseint

Paquete basado en el software PseInt para aprender Lógica de Lenguajes de Programación en Vitalinux.
Lo que se ha hecho es paquetizar en formato DEB el software suministrardo por PseInt en formato *.tgz, de tal forma que se facilita su instalación en distros derivadas de Debian (Debian, Ubuntu, Mint, etc.)

# Usuarios Destinatarios

Usuarios que quieren aprender Lógica de Lenguajes de Programación

# Aspectos Interesantes:
```
Ninguno a resaltar
```
# Como Crear el paquete DEB a partir del codigo de GitHub
Para crear el paquete DEB será necesario encontrarse dentro del directorio donde localizan los directorios que componen el paquete.  Una vez allí, se ejecutará el siguiente comando (es necesario tener instalados los paquetes apt-get install debhelper devscripts):

```
apt-get install debhelper devscripts
/usr/bin/debuild --no-tgz-check -us -uc
```

# Como Instalar el paquete generado vx-dga-l-*.deb:
Para la instalación de paquetes que estan en el equipo local puede hacerse uso de ***dpkg*** o de ***gdebi***, siendo este último el más aconsejado para que se instalen también las dependencias correspondientes.
```
gdebi vx-dga-l-*.deb
```
