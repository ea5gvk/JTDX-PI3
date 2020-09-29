Librerias a instalar
dpkg: problemas de dependencias impiden la configuración de jtdx:
 jtdx depende de libgfortran4 (>= 4.8.2); sin embargo:
  El paquete `libgfortran4' no está instalado.
 jtdx depende de libqt5multimedia5 (>= 5.2.0); sin embargo:
  El paquete `libqt5multimedia5' no está instalado.
 jtdx depende de libqt5multimedia5-plugins (>= 5.2); sin embargo:
  El paquete `libqt5multimedia5-plugins' no está instalado.
  
  apt --fix-broken install
  
  sudo dpkg -I jtdx-2.2.0-rc152_u_armhf.deb | grep Depends
