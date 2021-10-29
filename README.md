# Instalacion_git
Este repositorio esta dedicado a la instalación de git en kubunu

## 1.Introducción

Git es un sistema de control de versiones distribuido de código abierto desarrollado por Linus Torvalds, el creador de Linux. El control de versiones distribuido permite a los desarrolladores descargar un software, realizar cambios y subir la versión que han modificado. Esto permite una nueva manera de desarrollar software desde un  individuo hasta en un grupo muy grande de desarrolladores.

<div align="center">
<img width="60%" src="https://miro.medium.com/max/910/1*JZ2YCpyIOO3JfnXy264b_A.png">
</div>

## 2.Pasos

Yo Instalaré git con los paquetes predeterminados. Esto no me dará mucha personalización ni mucho control sobre la instalación, pero será rápido de instalar y sin muchas complicaciones.

### 2.1Comprobación de versiones existente

Lo primero comprobamos que no tengamos ninguna versión del git ya instaladas, en mi caso, lo compruebo con el comando 
```
git –version
```
<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1e1aMNiF8VU6qrZQq6zbfoZAMCfc6se54">
</div>
Como podemos comprobar, en mis sistema operativo no tengo ninguna versión del git

### 2.2Actualización de repositorios

Para empezar actualizamos los repositorios, con el comando 
```
sudo apt update
```

<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1hDTrRSnEkBG99hJfVMmaySDeGGbqzEHr">
</div>


### 2.3Instalación de git

Seguimos con la instalación del programa en sí con el comando
```
sudo apt install git
```

<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=17kGVjRp2lOK8DnUEkrRfgvotyUvkMU6k">
</div>


### 2.4Configuración de git

Ahora debemos configurar 2 aspectos del git para su correcto funcionamiento.


<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1782E6jsyR1FjaQy-PsRYVJ_KOyJKNpZv">
</div>
Tenemos que poner nuestro nombre de usuario y correo de nuestra cuenta de github.


### 2.5Últimas comprobaciones



Para acabar comprobamos que la configuración se ha guardado correctamente con “nano ~/.gitconfig”

Enseñando el fichero gitconfig

<div align="center">
<img width="70%" src="http://drive.google.com/uc?export=view&id=1Gq2ZKAkjRHZM1pFiBWWyybMO_F1Fs8n5">
</div>

Y Por último comprobamos la versión instalada 

<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1kSk2QJXGKUk7SpN0SbyptlbdNbD_Ovqu">
</div>

## 3.Conclusión

Git es una herramienta poderosa en en el entorno del desarrollo de aplicaciones, con grandes capacidades para almacenar y recuperar versiones antiguas de los archivos y un registro de ellos.


