# Horizontall-HTB

## NMAP 

![image](https://github.com/gecr07/Horizontall-HTB/assets/63270579/14604345-f74c-4b4f-853e-d82a08a5c107)


Aqui habia de 2 o encontrabas el otro dominio por el archivo http://horizontall.htb/js/app.c68eb462.js

![image](https://github.com/gecr07/Horizontall-HTB/assets/63270579/2d4be43c-a67b-4241-9cb2-b40624ec33db)



## RCE

Para poder ejecutar comandos necesitamos saber la version de scrapi

![image](https://github.com/gecr07/Horizontall-HTB/assets/63270579/16c30811-59ab-4cd8-baa2-bd3d5557e502)

Encontramos un exploit justo para esa version y ejecutamos comandos.

![image](https://github.com/gecr07/Horizontall-HTB/assets/63270579/bd4d52a5-e5bd-4ef0-801b-720aed81bc72)


Ejecutamos comandos. 

## Priv escalation

Nos damos cuenta que existen puertos abietos en escucha uno de esos es el 8000 nos lo traemos ya sea con chisel o con ssh.

![image](https://github.com/gecr07/Horizontall-HTB/assets/63270579/0210626f-6103-4d1a-ab45-93385290d93d)

```
ss -ntln

```























