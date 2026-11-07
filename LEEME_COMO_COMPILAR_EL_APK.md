# Proyecto APK Nativo de PedroScan (Android)

Este paquete contiene la aplicación nativa de Android (**`ar.com.estudiodetitulos.pedroscan`**) con el puente nativo `PedroScanAndroid` (`FileProvider` + `Intent.ACTION_SEND`) que permite:
1. **Compartir archivos `.docx` (Word) directamente** a WhatsApp, Gmail, Google Drive, Microsoft Word, etc. sin la restricción de seguridad que aplica el navegador Chrome.
2. **Tener instaladas las 2 apps en el celular** sin ningún conflicto con `EstudioDeTitulos.com.ar`, ya que el APK tiene su propio identificador único de paquete (`ar.com.estudiodetitulos.pedroscan`).

## Cómo obtener el archivo `PedroScan.apk` (2 opciones gratuitas)

### Opción 1: Sin instalar nada en tu PC (vía GitHub en 2 minutos)
1. Creá un repositorio nuevo en [github.com](https://github.com) y subí el contenido de esta carpeta.
2. Entrá a la pestaña **Actions** del repositorio: automáticamente se ejecutará el flujo **"Compilar APK de PedroScan"** y en 2 minutos te dejará para descargar el archivo **`PedroScan-APK.zip`** con el `.apk` firmado listo para instalar en tu celular.

### Opción 2: Con Android Studio en tu PC
1. Abrí esta carpeta en **Android Studio**.
2. En el menú superior tocá **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
3. Se generará el archivo `.apk` listo para pasar al celular por WhatsApp o cable USB.
