## 🚀 ¡Movido a Codeberg!
Nueva ubicación: https://codeberg.org/daskashk/deb_installer.sh



# Instalador de Paquetes .deb
Un script de Bash simple para instalar paquetes .deb descargados localmente.

## Uso
Ejecuta el script y proporciona el nombre del paquete.deb como argumento:
```
./deb_installer.sh paquete.deb
```
## Requisitos
* Sistema Linux con `apt` instalado
* Permiso de superusuario para instalar paquetes

## Instrucciones para usar este instalador por defecto
1. Copia el script en `/usr/local/bin/`
2. Haz que el script sea ejecutable con `chmod +x /usr/local/bin/deb_installer.sh`
3. (Opcional) Crea un .desktop que ejecute el script y añadelo como opción por defecto para archivos .deb. Así se usará el script para instalar paquetes DEB desde el gestor del archivos.

## Importante
Recuerda que el script utiliza `apt` para instalar paquetes.deb, lo que puede requerir dependencias adicionales
