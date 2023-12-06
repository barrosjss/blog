---
title: "Git y GitHub"
description: "Git es un sistema de control de versiones distribuido de código abierto que permite a los desarrolladores rastrear y gestionar cambios en su código."
pubDate: "2023-12-06T17:07:43.776Z"
heroImage: "/placeholders/github.png"
categories: ['Git y GitHub']
tags: ['Git','GitHub']
author: ['Jesus Barros']
---
# Git y GitHub: Una guía rápida para principiantes

¡Hola! Si quieres aprender Git y GitHub, estás en el lugar correcto.

En este artículo encontrarás una breve introducción a Git y GitHub. Aprenderás por qué son herramientas muy poderosas y por qué deberías aprenderlas si tu meta es ser desarrollador.

## **¿Qué es control de versiones?**

Primero veamos qué es control de versiones porque este concepto es esencial para Git y GitHub.

¿Nunca has deseado poder volver a una versión previa de un proyecto o registrar los cambios que has hecho?

Permíteme decirte que esto es posible con control de versiones.

Con un sistema de control de versiones, puedes mantener un registro de los cambios que has hecho en tus archivos y puedes tener varias versiones de tu proyecto en la misma computadora de forma simultánea. Esto te permite cambiar de una versión a otra de tu proyecto mientras haces cambios y actualizaciones.

<center>
<img src="https://www.freecodecamp.org/espanol/news/content/images/2023/02/Screenshot-2023-02-02-at-3.27.27-PM.png" alt="Proyecto en Git" width="500">
</center>

Ese es el poder del control de versiones.

Puedes mantener una versión "experimental" de tu proyecto para desarrollar aspectos o funcionalidades nuevas al mismo tiempo que tienes la versión estable de tu proyecto en vivo para tus usuarios.

<center>
<img src="https://www.freecodecamp.org/espanol/news/content/images/size/w1600/2023/02/Screenshot-2023-02-02-at-3.30.45-PM.png" alt="Proyecto en Git" width="500">
</center>

Dos de las herramientas de control de versiones más populares en la comunidad global de desarrolladores son **Git y GitHub**. Comencemos viendo los fundamentos de Git.

## ¿Qué es Git?

Git es un sistema de control de versiones distribuido que permite a los desarrolladores rastrear y gestionar cambios en su código. Git permite a los desarrolladores trabajar en paralelo en el mismo proyecto, crear ramas para trabajar en nuevas características o correcciones de errores, y luego fusionarlas de nuevo en la base de código principal. Además, Git funciona sin conexión, lo que significa que puedes hacer commit de cambios y trabajar en tu proyecto incluso sin conexión a Internet [1](https://www.geeksforgeeks.org/git-cheat-sheet/).

### Conceptos básicos de Git

Los siguientes conceptos son esenciales para trabajar con Git:

**🔸 Repositorio (*Repository*)**

Un repositorio es donde Git almacena los archivos de tu proyecto y las distintas versiones de tus archivos. Un repositorio puede ser local o remoto. Un repositorio local se guarda de forma local en tu computadora. Un repositorio remoto se guarda en los servidores del servicio de *hosting* que escojas (por ejemplo, GitHub).

<center>
<img src="https://www.freecodecamp.org/news/content/images/2023/02/Screenshot-2023-02-02-at-10.57.53-AM.png" alt="Screenshot-2023-02-02-at-10.57.53-AM" width="500">
</center>

**🔸 Directorio de trabajo (*****Working directory*****)**

Este es el directorio del proyecto en el sistema de archivos, donde se guardan los archivos. Esta es, por ejemplo, la carpeta que abres en tu editor de código o IDE para trabajar con tus archivos.

**🔸 Área de preparación (*Staging area*)**

Este es el conjunto de archivos y cambios que serán incluidos en el siguiente commit. Podemos agregar y remover archivos de esta área si es necesario.

<center>
<img src="https://www.freecodecamp.org/espanol/news/content/images/2023/02/Screenshot-2023-02-09-at-8.21.55-AM.png" alt="Screenshot-2023-02-09-at-8.21.55-AM" width="500">
</center>

**🔸 Commit**

Un commit es como una "foto" de tu proyecto en un momento en particular. Un commit registra un cambio que se realizó en el proyecto. Tú escoges cuándo crear un commit y qué incluir en el commit.

<center>
<img src="https://www.freecodecamp.org/espanol/news/content/images/2023/02/commits.png" alt="commits" width="500">
</center>

**🔸 Rama (*Branch*)**

Una rama es una línea independiente de desarrollo de un proyecto que es administrada y rastreada por Git. Cada proyecto iniciar con una rama por defecto que normalmente llamamos `<strong>main</strong>`. Podemos crear una rama para trabajar en un aspecto nuevo del proyecto sin afectar la versión principal.

<center>
<img src="https://www.freecodecamp.org/espanol/news/content/images/2023/02/branch.png" alt="branch" width="500">
</center>

**🔸 Fusionar (*Merge*)**

Podemos combinar o fusionar (merge) ramas si necesitamos incorporar los cambios que hicimos en una rama en otra rama. Esto es lo que normalmente hacemos cuando un aspecto nuevo está listo para ser incorporado a la versión en vivo del proyecto.

<center>
<img src="https://www.freecodecamp.org/espanol/news/content/images/2023/02/merge.png" alt="merge" width="500">
</center>

### Git Bash

Durante el curso trabajaremos con Git Bash, una herramienta de línea de comandos para Windows que nos permite ejecutar comandos de Git.

> 💡 Bash significa Bourne Again Shell. Un bash es una aplicación usada para interactuar con el sistema operativo de una computadora a través de comandos.

<center>
<img src="https://www.freecodecamp.org/news/content/images/2023/01/image-387.png" alt="image-387" width="500">
</center>

### Comandos de Git más importantes

Aquí te dejo una lista de algunos de los comandos de Git más importantes que debes conocer:

* **git clone**: Este comando se utiliza para descargar el código fuente existente de un repositorio remoto, como GitHub. Básicamente, git clone hace una copia idéntica de la última versión de un proyecto en un repositorio y la guarda en tu computadora [5](https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/).
* **git branch**: Este comando se utiliza para crear, listar y eliminar ramas. Las ramas son muy importantes en el mundo de Git. Al usar ramas, varios desarrolladores pueden trabajar en paralelo en el mismo proyecto simultáneamente [5](https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/).
* **git checkout**: Este comando se utiliza para cambiar de una rama a otra. También se puede utilizar para verificar archivos y commits [5](https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/).
* **git status**: Este comando proporciona toda la información necesaria sobre la rama actual [5](https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/).
* **git commit**: Este comando se utiliza para guardar los cambios en el código. Una vez que llegamos a un cierto punto en el desarrollo, queremos guardar nuestros cambios [5](https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/).
* **git push**: Este comando se utiliza para enviar tus cambios al servidor remoto. Git push sube tus commits al repositorio remoto [5](https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/).

Estos comandos pueden mejorar drásticamente tu productividad en Git. No tienes que recordarlos todos, es por eso que he escrito esta hoja de trucos. Marca esta página para referencia futura o imprímela si te gusta [4](https://www.freecodecamp.org/news/git-cheat-sheet/).

## ¿Qué es GitHub?

GitHub es una plataforma de almacenamiento en la nube gratuita que proporciona alojamiento para repositorios de Git y facilita la colaboración entre desarrolladores. GitHub es una herramienta esencial para los desarrolladores para administrar eficientemente su código, colaborar con otros y contribuir a proyectos de código abierto [1](https://www.geeksforgeeks.org/git-cheat-sheet/).
