# Vigilante8Rebirth

## English

This is an attempt to preserve the Vigilante 8 port made in Unity.

This project attempts to preserve the port of Vigilante 8 Second Offense, made by Stefan Vranjes. The original author, although he has his own source code (outdated), has not provided updates regarding the source code like his compiled version for Windows. We try to preserve his port as he originally conceived it, but it will change and adapt to the needs of the community and fans of Vigilante 8.

My intention is to make this port 100% modifiable, where the community can contribute to its development.

### Development Plan

#### First Step:
1. Reverse engineer the Vigilante 8 Unity port and restore the source code to the latest version distributed by the author (currently 2.3.0).
2. Restore the project in Unity and make the compilation 100% functional.
   - Restore Shaders.
3. Restore Networking.

#### Second Step:
1. Migrate to a more modern version of Unity.
2. Migrate Networking Photon to an alternative (like Mirror).
3. Unlink Paid Assets for open-source versions (get rid of PSXEffect, Rewired, etc.) if their license does not allow sharing as open-source.

#### Third Step:
1. Integrate plugins for Mods (XLua or some other framework) in Maps, Vehicles, Events.

### Dependencies / Requirements

- **Engine**: Unity 2021.2.19f1
- **Assets**: PSXEffect, Rewired
- **Source File Game**: Vigilante 8 Second Offense (USA) Playstation

#### Unity Packages:
- Unity UI
- Mathematics
- Visual Studio Editor (Alternative)
- [UnitySimplePatchTool](https://github.com/yasirkula/UnitySimplePatchTool)
- [SoftMaskForUGUI](https://github.com/mob-sakai/SoftMaskForUGUI)
- [UIEffect](https://github.com/mob-sakai/UIEffect)
- [unity-camera-viewport-rect](https://github.com/gilzoide/unity-camera-viewport-rect.git#1.0.1)

### How to Build

To build this project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/Otak-Productions/Vigilante8Rebirth.git
    ```

2. Open the project in Unity:
    - Ensure you have the correct version of Unity installed (the version used in the original project or the version you plan to migrate to).
    - Open Unity Hub, click on "Add", and select the cloned project directory.

3. Resolve dependencies:
    - Make sure all necessary packages and dependencies are installed via the Unity Package Manager.

4. Build the project:
    - Go to `File > Build Settings`.
    - Select your target platform and configure build settings as needed.
    - Click on "Build" to generate the executable.

### Contributing

We welcome contributions from the community! Please feel free to fork this repository, make your changes, and submit a pull request. Make sure to follow the contribution guidelines outlined in the CONTRIBUTING.md file.

### License

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. See the LICENSE file for more details.

### Disclaimer

This project is not affiliated with, endorsed by, or in any way connected to the original creators of Vigilante 8 or its licensors. All trademarks and copyrights are the property of their respective owners.

### Credits

Original project by Stefan Vranjes. Visit the [Vigilante2Unity](https://github.com/stefanvranjes/Vigilante2Unity) for more information.

---

## Español

Este proyecto intenta preservar el puerto de Vigilante 8 Second Offense, hecho por Stefan Vranjes. El autor original, aunque tenga su propio código fuente (desactualizado), no ha proporcionado avances respecto al código fuente como su versión compilada para Windows. Intentamos preservar su puerto tal y como lo concibió desde el principio, pero que irá cambiando y adaptándose a las necesidades de la comunidad y fans de Vigilante 8.

Mi intención es poder hacer que este puerto sea 100% modificable, en donde la comunidad pueda contribuir en su desarrollo.

### Plan de Seguimiento

#### Primer Paso:
1. Realizar ingeniería inversa al puerto Vigilante 8 Unity y restaurar el código fuente a la última versión distribuida por el autor (actualmente 2.3.0).
2. Restaurar el proyecto en Unity y la compilación sea 100% funcional.
   - Restaurar Shaders.
3. Restaurar el Networking.

#### Segundo Paso:
1. Migrar a una versión de Unity más moderna.
2. Migrar Networking Photon a alguna alternativa (como Mirror).
3. Desvincular Assets de Pago por versiones de Código Abierto (deshacerse de PSXEffect, Rewired, etc.) si su licencia no permite compartirlo como código abierto.

#### Tercer Paso:
1. Integrar complementos para Mods (XLua o algún otro framework) en Mapas, Vehículos, Eventos.

### Dependencias / Requisitos

- **Engine**: Unity 2021.2.19f1
- **Assets**: PSXEffect, Rewired
- **Source File Game**: Vigilante 8 Second Offense (USA) Playstation

#### Paquetes de Unity:
- Unity UI
- Mathematics
- Visual Studio Editor (Alternative)
- [UnitySimplePatchTool](https://github.com/yasirkula/UnitySimplePatchTool)
- [SoftMaskForUGUI](https://github.com/mob-sakai/SoftMaskForUGUI)
- [UIEffect](https://github.com/mob-sakai/UIEffect)
- [unity-camera-viewport-rect](https://github.com/gilzoide/unity-camera-viewport-rect.git#1.0.1)

### Cómo Construir

Para construir este proyecto, sigue estos pasos:

1. Clona el repositorio:
    ```sh
    git clone https://github.com/Otak-Productions/Vigilante8Rebirth.git
    ```

2. Abre el proyecto en Unity:
    - Asegúrate de tener instalada la versión correcta de Unity (la versión utilizada en el proyecto original o la versión a la que planeas migrar).
    - Abre Unity Hub, haz clic en "Add" y selecciona el directorio del proyecto clonado.

3. Resuelve las dependencias:
    - Asegúrate de que todos los paquetes y dependencias necesarios estén instalados a través del Unity Package Manager.

4. Construye el proyecto:
    - Ve a `File > Build Settings`.
    - Selecciona tu plataforma de destino y configura los ajustes de compilación según sea necesario.
    - Haz clic en "Build" para generar el ejecutable.

### Contribuir

¡Damos la bienvenida a las contribuciones de la comunidad! No dudes en hacer un fork de este repositorio, realizar tus cambios y enviar un pull request. Asegúrate de seguir las pautas de contribución descritas en el archivo CONTRIBUTING.md.

### Licencia

Este proyecto está licenciado bajo la Licencia Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International. Consulta el archivo LICENSE para más detalles.

### Aviso Legal

Este proyecto no está afiliado, respaldado ni de ninguna manera relacionado con los creadores originales de Vigilante 8 o sus licenciantes. Todas las marcas comerciales y derechos de autor son propiedad de sus respectivos dueños.

### Créditos

Proyecto original por Stefan Vranjes. Visita la [Vigilante2Unity](https://github.com/stefanvranjes/Vigilante2Unity) para más información.