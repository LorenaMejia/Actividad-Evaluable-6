# Flutter Camera App 📸

Una aplicación móvil simple y funcional desarrollada en Flutter para capturar fotografías utilizando la cámara del dispositivo.

## 📱 Capturas de Pantalla

<div align="center">
  
  <img width="250" alt="Pantalla inicial" src="https://github.com/user-attachments/assets/a10c5758-0170-41f2-a855-13f7f0895ec1" />
  <img width="250"  alt="Solicitud de permisos" src="https://github.com/user-attachments/assets/a435c948-566b-4944-8759-f0574be9670a" /> 
   <img width="250" alt="Captura dentro del celular" src="https://github.com/LorenaMejia/Actividad-Evaluable-6/blob/main/tatuaje2.jpg?raw=true" />
  
</div>



##  Características

- Captura de fotografías con la cámara del dispositivo
- Solicitud de permisos de cámara en tiempo de ejecución
- Vista previa de la foto capturada
- Interfaz simple e intuitiva
- Guardado de fotos en el almacenamiento del dispositivo

## Tecnologías y Librerías

Este proyecto fue desarrollado utilizando las siguientes dependencias:

```yaml
dependencies:
  flutter:
    sdk: flutter
  camera: ^0.10.5+9              # Acceso a la cámara del dispositivo
  path_provider: ^2.0.11          # Gestión de rutas de almacenamiento
  permission_handler: ^11.0.1     # Manejo de permisos en tiempo de ejecución
  cupertino_icons: ^1.0.8         # Iconos iOS
```

### Descripción de las librerías:

- **camera**: Proporciona acceso a la cámara del dispositivo para capturar fotos y videos
- **path_provider**: Permite obtener rutas de almacenamiento temporal y permanente en el dispositivo
- **permission_handler**: Facilita la solicitud y manejo de permisos del sistema (cámara, almacenamiento, etc.)
- **cupertino_icons**: Conjunto de iconos del estilo iOS para una interfaz consistente

## Instalación

1. **Clonar el repositorio**
```bash
git https://github.com/LorenaMejia/Actividad-Evauable-6.git
cd AppFotosFlutter
```

2. **Instalar dependencias**
```bash
flutter pub get
```

3. **Ejecutar la aplicación**
```bash
flutter run
```

## Requisitos Previos

- Flutter SDK (versión 3.0 o superior)
- Dart SDK
- Android Studio / VS Code con extensiones de Flutter
- Dispositivo físico o emulador con cámara

## Permisos

La aplicación solicita los siguientes permisos:

### Android (`android/app/src/main/AndroidManifest.xml`)
```xml
<uses-permission android:name="android.permission.CAMERA" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
```

### iOS (`ios/Runner/Info.plist`)
```xml
<key>NSCameraUsageDescription</key>
<string>Esta app necesita acceso a la cámara para tomar fotos</string>
<key>NSPhotoLibraryUsageDescription</key>
<string>Esta app necesita acceso a la galería para guardar fotos</string>
```

## Generar APK

Para generar el APK de la aplicación:

```bash
# APK de debug
flutter build apk --debug

# APK de release
flutter build apk --release

# APK dividido por arquitectura (menor tamaño)
flutter build apk --split-per-abi
```

El APK generado se encuentra en: `build/app/outputs/flutter-apk/`

## Autor

**Nicol Lorena Mejia**

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

## Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Añadir nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

---
