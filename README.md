# Práctica 1: "Instalación y Funcionamiento de los Entornos Móviles"
**Nombre:** Tellez Giron Castro Angel Ricardo 
**Grupo:** 7CV4
**Profesor:** Hurtqado Áviles Gabriel 
**Materia:** Desarrollo de aplicaciones moviles nativas 
**Fecha de entrega:** 03/09/2026

## Ejercicio 1: Instalación de Herramientas
### Instalaciones 
Carpeta de Instalaciones:
En esta carpeta se encuentran las imágenes de las diferentes instalaciones que se requieren para este curso, así como las versiones que contienen cada uno de ellas:

**Herramientas instaladas**
- **Java / OpenJDK:** OpenJDK 25.0.4.1 LTS
- **Apache Maven:** 3.9.16
- **Git:** 2.55.0.windows.5
- **GitHub Desktop:** 3.6.4 (x64)
- **Flutter:** 3.47.2
- **Android SDK:** 36.0.0
- **Android Studio:** Quail 3 - 2026.1.3
- **Node.js:** v24.15.0
- **Docker:** 29.7.2, build a7dcaa6

**Sistema operativo**
- **Windows 10 Pro 64 bits**
- **Versión:** 22H2
- **Compilación:** 19045.6466

## Ejercicio 2: Aplicación "Hola Mundo" en tres enfoques

### 1. Android nativo con Jetpack Compose 
En la carpeta de Android nativo con Jetpack Compose se encuentra la imagen correspondiente en la cual se verifica que se realizó de manera correcta lo solicitado.

**Instrucciones de instalación y ejecución:**
1. Abre **Android Studio**.
2. Ve a `File > Open...` y navega hasta la carpeta específica del proyecto de Jetpack Compose.
3. Espera a que **Gradle** termine de sincronizar el proyecto y descargue las dependencias necesarias (podrás ver el progreso en la barra inferior).
4. Abre el **Device Manager** y lanza un emulador Android (AVD) previamente configurado, o conecta un dispositivo físico mediante USB con la "Depuración por USB" activada.
5. Selecciona el dispositivo en la barra superior de Android Studio.
6. Haz clic en el botón de **Run** (el ícono del triángulo verde) o presiona `Shift + F10`. La aplicación se compilará, se instalará en el dispositivo y se ejecutará automáticamente.

### 2. Android nativo con Views
En la carpeta de Android nativo con Views se encuentran las imágenes correspondientes en las cuales se verifica que se realizó de manera correcta lo solicitado.

**Instrucciones de instalación y ejecución:**
1. Abre **Android Studio**.
2. Ve a `File > Open...` y selecciona la carpeta del proyecto de Android con Views (XML).
3. Aguarda a que la sincronización de **Gradle** finalice.
4. Asegúrate de tener un emulador en ejecución o un dispositivo Android físico conectado.
5. En la barra de herramientas superior, verifica que el dispositivo correcto esté seleccionado.
6. Presiona el botón de **Run** (triángulo verde) o usa el atajo `Shift + F10`. Android Studio generará el APK, lo instalará y lanzará la aplicación mostrando la interfaz construida con XML.

### 3. Flutter  
En la carpeta de Flutter se encuentran las imágenes correspondientes en las cuales se verifica que se realizó de manera correcta lo solicitado.

**Instrucciones de instalación y ejecución:**
1. Abre una terminal (Símbolo del sistema, PowerShell o la terminal integrada de tu IDE como VS Code o Android Studio).
2. Navega hasta el directorio raíz del proyecto de Flutter utilizando el comando `cd`:
   ```bash
   cd ruta/hacia/tu/proyecto_flutter
3. Ejecuta el siguiente comando para descargar e instalar todas las dependencias del proyecto:
   ```bash
   flutter pub get
4. Inicia un emulador de Android/iOS o conecta tu dispositivo físico. Puedes verificar los dispositivos disponibles ejecutando:
   flutter devices
4. Para compilar, instalar y ejecutar la aplicación, corre el siguiente comando::
   flutter run

### Comparación
Las tres versiones permiten desarrollar una aplicación Android sencilla, pero cada una utiliza una tecnología y una forma diferente de construir la interfaz.

- **Android nativo con Views (XML):** La interfaz se diseña mediante archivos XML, utilizando componentes como `TextView`, `LinearLayout` o `ConstraintLayout`. Es una opción sencilla de entender para quienes están comenzando con Android, aunque requiere trabajar por separado con los archivos XML y Kotlin. La cantidad de código puede ser mayor cuando las interfaces son más complejas.
- **Android nativo con Jetpack Compose:** Permite crear la interfaz directamente mediante código Kotlin utilizando funciones `@Composable`. El desarrollo resulta más rápido y flexible, ya que no es necesario crear archivos XML para cada interfaz. Además, los componentes como `Column` y `Text` permiten organizar fácilmente los elementos y utilizar modificadores para aplicar estilos.
- **Flutter:** Utiliza Dart y permite crear interfaces mediante widgets. Con componentes como `MaterialApp`, `Scaffold`, `Column` y `Text`, es posible construir la interfaz de manera estructurada y reutilizable. Una de sus principales ventajas es que permite desarrollar aplicaciones para diferentes plataformas utilizando una misma base de código.

### Conclusiones
Esta primera práctica ha sido fundamental para establecer correctamente el entorno de trabajo, lo cual es el primer paso crítico en el desarrollo móvil. La correcta configuración de herramientas como Android Studio, el SDK de Android, Flutter y Java asegura que los futuros proyectos se puedan compilar y ejecutar sin problemas de dependencias o compatibilidad.

Adicionalmente, al desarrollar la misma aplicación utilizando tres enfoques distintos, se logró comprender de forma práctica la evolución de la creación de interfaces. Se observó el contraste entre el enfoque tradicional imperativo (usando XML con Views) y los paradigmas declarativos modernos (Jetpack Compose y Flutter), los cuales simplifican la estructura del código y aceleran el desarrollo. Tener experiencia con estas tres alternativas proporciona un panorama amplio para elegir la tecnología más adecuada según las necesidades específicas de futuros proyectos de desarrollo móvil.