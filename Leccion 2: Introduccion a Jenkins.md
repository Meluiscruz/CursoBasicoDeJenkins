# Lección 2: Introducción a Jenkins
<br>

## 2.1 Notas de la clase
<br>

**Jenkins** es **open source** y probablemente el **software de automatización más usado de todos**, escrito en **Java** y corre en **JVM**. Es muy conveniente al ser una **herramienta extensible** al tener un ecosistema de **plugins** que te permiten extenderlo, puedes escribir tus propios plugins con Java, pero ya **la comunidad** ha desarrollado un sinfín de ellos.

También nos permite **escalar** de manera **horizontal** y **verticalmente**, puede correr un sin número de **trabajos concurrentemente** en una sola máquina y si esa máquina no da abasto se le puede dar más recursos a Jenkins. O una máquina no es suficiente entonces Jenkins nos permite escalar horizontalmente con ““slaves”” y controlar varios nodos para que trabajen por él.

Jenkins siempre esta **siendo innovado** y teniendo **actualizaciones de seguridad**, esto es importante porque es el target más grande de seguridad de una empresa porque lo tiene todo.

Algo que Jenkins ha trabajado mucho en los últimos años es que puedes escribir tus **“jobs”** o **unidades de trabajo** en código. Nosotros queremos que nuestra **automatización** también sea **programática**, no solo los comando a ejecutar sino poder migrar nuestro trabajo a un nuevo Jenkins de manera **reproducible**. Han creado **Pipelines as code**.
<br>

## 2.2 Conceptos clave
<br>

- **JVM**: El acrónimo de _Java Virtual Machine_
- **Escalamiento horizontal**: Se refiere al crecimiento de operaciones del proyecto. Debido al alto volumen de transacciones, se requerirá de más recursos de hardware, el escalamiento de este tipo delega el trabajo mediante _slaves_, al igual que la gestión de servidores en una red centralizada.
- **Escalamiento horizontal**: Se refiere al crecimiento del proyecto en función de sus tipos y volumen de operaciones, sin llegar a necesitar más recursos de hardware.
- **Honeypot**: Es un sistema "señuelo" cuyo propósito es ralentizar el ataque hacia el sistema principal, también suele ser utilizado como herramienta de seguridad informática para desviar un ataque informático, y en el proceso tomar la información del atacanté.

<br>

## 2.3 Resumen
<br>

## 2.4 Fuentes
<br>

[Clase 2 del Curso Básico de Jenkins, en Platzi. ](https://platzi.com/clases/1436-jenkins-basico/15627-introduccion-a-jenkins/)