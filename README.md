# Obligatorio Taller de Servidores Linux 2023

## El repositorio contiene 2 playbooks para ser ejecutados con ansible, los playbooks se llaman playbook.yml y mariadbserver.yml.

playbook.yml: Este playbook corre en un servidor Rocky Linux.
Funciones: 
- Automatiza la instalacion de podman
- Asegura que el servicio podman siempre corra 
- Inicia un contenedor con tomcat
- Instalacion apache
- Crea un directorio de configuracion de virtualhost 
- Copia un archivo de configuracion a ese directorio 
 - Abre los puertos 80 y 443 en el firewall 
 - Inicia el servicio httpd

mariadbserver.yml: Este playbook corre en un servidor Ubuntu. 
Funciones:
- Instalacion de mariadb y requisitos
- Incio de servicio mariadb
- Abre puerto 3306 en firewall
- Automatiza instalacion segura de mariadb
- Crea base de datos



