📸 MiAppDeFotos - Aplicación de Cámara React Native

Una aplicación móvil para tomar fotos y guardarlas en la galería del dispositivo, desarrollada con React Native.



🚀 Funcionalidades

✅ Toma de fotos con cámara trasera



✅ Guardado automático en la galería del dispositivo



✅ Previsualización de la foto capturada



✅ Permisos automáticos para cámara y almacenamiento



✅ Interfaz intuitiva y fácil de usar



🛠️ Tecnologías Utilizadas

React Native v0.73+



React Native Vision Camera para acceso a cámara nativa



React Native Camera Roll para guardar en galería



Java JDK 11+ para Android



Gradle para build de Android



📋 Requisitos Previos

Node.js v18+ LTS



Java JDK 11, 17 o 21



Android Studio con SDK Android 33+



Dispositivo Android con API 21+ o emulador



🔧 Instalación y Configuración

1\. Clonar el repositorio
git clone https://github.com/tuusuario/mi-proyecto\_movil.git

cd mi-proyecto\_movil

2. Instalar dependencias

npm install

3. Configurar Android
   ===

Asegúrate de tener el Android SDK configurado



Las variables de entorno ANDROID\_HOME deben estar establecidas

4. Ejecutar en Android

Terminal 1: Iniciar Metro Bundler

===

npx react-native start



\# Terminal 2: Compilar e instalar

npx react-native run-Android

📱 Permisos Requeridos

La aplicación solicita automáticamente:



Cámara: Para tomar fotos



Almacenamiento: Para guardar fotos en la galería



🎯 Uso de la Aplicación

1. Abre la aplicación en tu dispositivo Android



2\. Permite los permisos cuando se soliciten



3\. Apunta la cámara hacia lo que quieres fotografiar



4\. Toca el botón "Tomar Foto"



5\. Visualiza la foto capturada



6\. Toca "Tomar otra foto" para continuar



📁 Estructura del Proyecto

mi-proyecto\_movil/

├── android/          # Configuración Android

├── src/

│   ├── components/  # Componentes React Native

│   └── utils/       # Utilidades

├── App.js           # Componente principal

└── package.json     # Dependencias

🔍 Troubleshooting

1. Error de permisos

   Limpiar build anterior

   ===

   cd android \&\& gradlew clean \&\& cd ..

2. ADB no reconocido
   ===

   Configurar variables de entorno:

   set ANDROID\_HOME=C:\\Users\\tuusuario\\AppData\\Local\\Android\\Sdk

   set PATH=%ANDROID\_HOME%\\platform-tools;%PATH%

   

   3\. Dispositivo no detectado

   adb devices

   adb reverse tcp:8081 tcp:8081

   📄 Licencia

   Este proyecto está bajo la Licencia MIT. Ver archivo LICENSE para más detalles.

   🤝 Contribuciones

   ¡Las contribuciones son bienvenidas! Por favor:

   

1. Fork el proyecto
2. Crea una rama para tu feature
3. &nbsp;Commit tus cambios
4. &nbsp;Push a la rama
5. &nbsp;Abre un Pull Request

   


   Desarrollado con ❤️ usando React Native

   

   🎥 Demostración

   La aplicación incluye funcionalidad completa de cámara:

   

   Vista previa en tiempo real

   

   Captura de fotos con un solo toque

   

   Guardado automático en galería

   

   Previsualización inmediata

   

   https://screenshots/app-demo.gif


   ## 🚀 \*\*PARA ACTUALIZAR EL README EN GIT:\*\*

   

   \### \*\*1. Crear el archivo README.md:\*\*

   ```cmd

   notepad README.md

   2. Copiar y pegar el contenido anterior

   3\. Guardar y cerrar

   4\. Agregar y subir a GitHub:

   git add README.md

   git commit -m "docs: add comprehensive README with installation and usage instructions"

   git push origin main

   5. Verificar en GitHub:

   Ve a tu repositorio en GitHub

   

   El README debería aparecer automáticamente

   

   Asegúrate de que el formato se vea bien

   

