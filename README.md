# Kenobi-THM

### Descripcion General:
***kenobi_exploit.py*** es un script escrito en python, que automatiza la intrusion para la Maquina Kenobi de la plataforma [Try Hack Me](https://tryhackme.com/room/kenobi) ganando una shell interactiva
- Exploit: ProtFTPd 1.3.5 - Remote Command Execution
- Autor: ErickBuster
- Maquina: Kenobi - Try Hack Me
- Software: ProFTPd Version 1.3.5
- CVE: 2015-3306

> Permite a los atacantes remotos leer y escribir en ficheros arbitrarios a traves de los comandos site cpfr y site cpto
> Automatiza la instruccion a la maquina Kenobi ejecutando comandos remotamente por medio del software ProFTPd version 1.3.5.
### Ejecucion:
```
python3 kenobi_exploit.py < rhost >
```
