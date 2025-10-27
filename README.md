<p align="center">
    <img src="https://github.com/ISCOUTB/AS_savioapp/blob/savio-app/src/assets/img/login_logo.png" height="100"/>
</p>

# SAVIO App
#### Versión adaptada (Fork) de [moodleapp](https://github.com/moodlehq/moodleapp) para la [Universidad Tecnológica de Bolívar (UTB)](https://www.utb.edu.co)

> **Disponibilidad:**
> Actualmente, La **app de SAVIO** está disponible **solo para dispositivos Android**.
> La versión para iOS se encuentra en evaluación y no está aún disponible para descarga.

SAVIO es una aplicación móvil desarrollada a partir del código base de Moodle App, adaptada para incorporar la identidad institucional de la UTB y añadir funcionalidades específicas que optimizan la experiencia de aprendizaje y el acceso a recursos educativos digitales.

La app de Savio trae consigo:
* **Integración total con SAVIO web**: acceso directo a cursos, calificaciones, foros, tareas y recursos.
* **Identidad institucional UTB**: colores, logotipo, tipografía y estilo visual coherente con la marca UTB.


Instalación y configuración
--------

> Tener en cuenta el [Development environment setup](https://moodledev.io/general/app/development/setup) proporsionado por los desarrolladores de Moodle.

1. Clonar el repositorio
```bash
git clone https://github.com/ISCOUTB/AS_savioapp
cd AS_savioapp
```

2. Instalar dependencias
```bash
npm install
```

3. Compilar la app en producción
```bash
npm run prod:android
```


License
-------

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)
