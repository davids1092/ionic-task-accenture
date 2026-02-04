# 📱 Task Ionic Cordova

Aplicación móvil desarrollada con Ionic + Cordova, enfocada en la gestión de tareas.
El proyecto permite ejecutarse como aplicación web y compilarse como APK para Android.

---

# 🚀 Instalación

Clona el repositorio y entra en el directorio del proyecto:

git clone https://github.com/davids1092/ionic-task-accenture.git
cd taskIonicCordova
npm install

---

# 📋 Requisitos del sistema

Asegúrate de tener instaladas las siguientes herramientas:

Node.js >= 16

NPM >= 8

Ionic CLI 7.2.1

Cordova

Android SDK (para compilación Android)

---

# 🌐 Ejecutar en entorno web (local)

Para levantar la aplicación en el navegador:

ionic serve


Esto abrirá automáticamente la app en http://localhost:8100.

---

# 🤖 Ejecutar en emulador Android

Instala las dependencias necesarias y ejecuta el proyecto en un emulador:

npm install -g native-run
cordova platform add android
ionic build
cordova run android --emulator


Asegúrate de tener un emulador Android configurado o un dispositivo físico conectado.

---

# 📦 Generar APK (Android)

Para generar el APK en modo release:

cordova build android --release

---

# 📍 Ruta del APK generado:

platforms/android/app/build/outputs/apk/debug/app-debug.apk

🛠️ Tecnologías utilizadas

Ionic

Cordova

Angular

TypeScript

HTML / CSS

---

# 👨‍💻 Autor
David Stiven Pérez Desarrollador Frontend (Angular)

---
