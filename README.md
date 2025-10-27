# Flutter Camera App 📸

Una aplicación móvil simple y funcional desarrollada en Flutter para capturar fotografías utilizando la cámara del dispositivo.

## 📱 Capturas de Pantalla

<img width="250" alt="Pantalla inicial" src="https://github.com/user-attachments/assets/a10c5758-0170-41f2-a855-13f7f0895ec1" />
  <img width="250"  alt="Solicitud de permisos" src="https://github.com/user-attachments/assets/a435c948-566b-4944-8759-f0574be9670a" /> 
<p align="center">
  <img width="250" alt="Captura dentro del celular" src="https://github.com/LorenaMejia/Actividad-Evaluable-6/blob/main/tatuaje.jpg?raw=true" />
</p>

*Vista previa de la aplicación mostrando la funcionalidad de captura de imagen.*

---

## ✨ Características

- ✅ Captura de fotografías con la cámara del dispositivo  
- ✅ Solicitud de permisos de cámara en tiempo de ejecución  
- ✅ Vista previa de la foto capturada  
- ✅ Interfaz simple e intuitiva  
- ✅ Guardado de fotos en el almacenamiento del dispositivo  

---

## 🛠️ Tecnologías y Librerías

Este proyecto fue desarrollado utilizando las siguientes dependencias:

```yaml
dependencies:
  flutter:
    sdk: flutter
  camera: ^0.10.5+9              # Acceso a la cámara del dispositivo
  path_provider: ^2.0.11          # Gestión de rutas de almacenamiento
  permission_handler: ^11.0.1     # Manejo de permisos en tiempo de ejecución
  cupertino_icons: ^1.0.8         # Iconos iOS
