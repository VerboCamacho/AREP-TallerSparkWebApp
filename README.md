# INTRODUCTION TO COMPLEX SYSTEMS, HEROKU, JAVA, MVN, AND GIT (AREP)
En este taller se implemento una aplicacion Web que realiza los cálculos de media y desviación estándar a partir de una tabla con n números,se realizo la implementación propia de una Linkedlist en un proyecto realizado con `maven java`.

## informe

El informe se encuentra en este [LINK](Informe.pdf)

## Link Heroku

El despliegue de la aplicacion esta en este [LINK](https://protected-sea-96271.herokuapp.com)

### Requerimentos

Se necesita tener el siguiente software en el computador:

```
$ Java 1.8
$ Maven 3.6.3
$ Git
$ IDLE (de su preferencia)
$ Heroku
```

### Instalacion

Algunos de los comandos utilizados para la realización del taller fueron los siguientes.

## Creación del proyecto `maven java`.
```
$ mvn archetype:generate -DgroupId=edu.escuelaing.arem.ASE.app -DartifactId=miprimera-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```

## Entrar al directorio de clases.

```
$ cd mi-primera-app/
```

## Construir el proyecto.

```
$ mvn package
```
## Construir el Deploy.

```
$ heroku create
```

## Realizar Despligue
```
$ git push heroku HEAD:master
```

## Ejecutar Pruebas.
```
$ mvn test
```



## Autor

Verbo Julian Camacho Villamarin

## Herramientas

* [Intellij IDEA](https://www.jetbrains.com/es-es/idea/) - IDLE
* [Heroku](https://protected-sea-96271.herokuapp.com) - Deployer
* [Maven](https://maven.apache.org/) - Dependency Management
* [Github](https://github.com/VerboCamacho/AREP-TallerSparkWebApp) - Repository



## Licencia

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details

