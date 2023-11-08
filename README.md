# Servidores-DNS

## Pautas

 * 2 MV Debian (11 o superior) en modo puente.
 * Visibilidad entre ambas MV (Ip acordes con la red).
 * Instalación bind9.
 * Systemctl restart bind9 cada vez que hagamos cambios.
 * journalctl -b -u named (Para ver donde están los posibles fallos).
 * Configurar /etc/resolv.conf para poner la ip de nuestro servidor (127.0.0.1), en cada reinicio de la MV hay que cambiarlo.

 ## Archivos a modificar

 * [DNS Maestro](https://github.com/juanASIR/Servidores-DNS/tree/main/DNS%20Maestro)
 * [DNS Secundario](https://github.com/juanASIR/Servidores-DNS/tree/main/DNS%20Secundario)

 ## Configuración paso a paso

 * PDF
