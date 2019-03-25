# Práctica 2 TADS

Esta práctica consiste en maximizar la suma con las restricciones que se muestran [en este documento](https://drive.google.com/open?id=1_fxvdl2DDL7dacJgO8NqrcGakrd2jPsn).

## Chuletas de GIT

_En este apartado se muestra una serie de comandos para trabajar con el repositorio tanto en remoto con el local._

### Instalando GIT y clonando el proyecto en local
El primer paso para que podamos colaborar todos es obtener git. La forma de obtener git depende de nuestro sistema operativo. Para descargarlo hay que ir al siguiente [enlace](https://git-scm.com/downloads).

Una vez se ha instalado git, el siguiente paso consiste en clonar el proyecto. Para clonar el proyecto hay que realizar el siguiente comando en la terminal de git:

```
git clone https://github.com/antoniomira/Pruebas.git
```

Clonar el proyecto nos permite que cada integrante del grupo tenga una copia en local con la que poder trabajar. Este trabajo consiste en repartirnos las tareas y trabajar con las ramas que se nos propone, aunque podemos salirnos de los límites mientras trabajemos más cómodos y funcione.

## Trabajando con las ramas

### Comprobar actualizaciones del repositorio remoto

Una vez se ha clonado el repostorio del servidor, se tiene en local una copia idéntica de la última versión actual. Una forma de comprobar que es la versión actual es usando el siguiente comando:

```
$ git status
On branch master
Your branch is up to date with 'origin/master'.
```

Si la salida que se obtiene del comando es como la siguiente, la rama es actual. En cualquier caso se tendría que hacer el comando "git pull" para obtener la información nueva del repositorio.

### Descargar actualizaciones del repositiorio remoto

Para descargar las últimas actualizaciones realizadas por otra gente en tu rama o en otras ramas hay que usar el comando "git pull" mencionado en el apartado anterior. 

```
$ git pull
Already up to date.
```

Si el mensaje que se muestra: "Already up to date" significa que estás con la última versión. Si ocurre algo distinto tienes un error o se está descargando la última versión.

### Crear una rama
Una vez estamos en una rama y queremos crear otra por el motivo que sea hay que hacer el siguiente comando:

```
$ git branch <nombreRama>
```

También se puede hacer lo siguiente:

```
$ git checkout -b <nombreRama>
```

Si se usa este comando se crea la rama y se hace checkout a ella. Es mucho más rápido que hacer esto:

```
$ git branch <nombreRama>; git checkout <nombreRama>
```

El ";" sirve para lanzar dos comandos en la misma línea. De otra manera se tendrían que lanzar los comandos de uno a uno.




##

## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

### Pre-requisitos 📋

__

```
Da un ejemplo
```

### Instalación 🔧

_Una serie de ejemplos paso a paso que te dice lo que debes ejecutar para tener un entorno de desarrollo ejecutandose_

_Dí cómo será ese paso_

```
Da un ejemplo
```

_Y repite_

```
hasta finalizar
```

_Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo_

## Ejecutando las pruebas ⚙️

_Explica como ejecutar las pruebas automatizadas para este sistema_

### Analice las pruebas end-to-end 🔩

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

### Y las pruebas de estilo de codificación ⌨️

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

## Deployment 📦

_Agrega notas adicionales sobre como hacer deploy_

## Construido con 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS

## Contribuyendo 🖇️

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado 📌

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Andrés Villanueva** - *Trabajo Inicial* - [villanuevand](https://github.com/villanuevand)
* **Fulanito Detal** - *Documentación* - [fulanitodetal](#fulanito-de-tal)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) quíenes han participado en este proyecto. 

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 a alguien del equipo. 
* Da las gracias públicamente 🤓.
* etc.



---