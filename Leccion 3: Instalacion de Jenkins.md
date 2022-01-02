# Lección 3: Instalación de Jenkins
<br>

## 3.1 Notas de la clase
<br>

En las fuentes están expresados los siguientes enlaces de interes:

* [**Tutorial de instalación de jenkins en Linux**](https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-20-04-es)

* [**Documentación official de Jenkins**](https://www.jenkins.io/doc/)

Cabe recordar, que Jenkins es una herramienta multiplataforma, esto quiere decir que es sopsortado en Sistemas con base en Windows, Linux o UNIX (Mac). Por cuestiones didácticas, instalaremos Jenkins sobre Linux (Ubuntu), por lo que es necesario consuiderar consultar las guias de instalación en la documentación oficial, para otros Sistemas Operativos.

## 3.2 Conceptos clave
<br>

A continuación, se expresa la lista de comandos necesarios para instalar las dependencias que necesitará Jenkins:
<br>
```
wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -

sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'

sudo apt update

sudo apt install jenkins

```

<br>

## 3.3 Resumen
<br>

## 3.4 Fuentes
<br>

* [**Tutorial de instalación de jenkins en Linux**](https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-20-04-es)

* [**Documentación official de Jenkins**](https://www.jenkins.io/doc/)
