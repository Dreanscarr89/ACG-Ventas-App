# ACG Ventas Pro 2.0

Proyecto Android listo para compilar como APK de ACG Ventas.

## Mejoras incluidas
- WebView configurado para JavaScript y almacenamiento local.
- Gestión real del selector de archivos/cámara para fotografías de productos.
- Compartir comprobantes mediante el selector nativo de Android, incluyendo imagen PNG.
- Guardado de comprobantes en almacenamiento de la aplicación.
- Apertura nativa de WhatsApp, enlaces telefónicos y correo cuando corresponde.
- Iconos de aplicación ACG.
- Orientación vertical optimizada para uso móvil.
- Descargas gestionadas por Android.
- Persistencia de clientes, productos y pedidos mediante localStorage.

## Nota importante
La aplicación conserva las bibliotecas web que ya utiliza el HTML original (Tailwind, Font Awesome, Chart.js y html2canvas). Por ello, algunas funciones visuales/gráficas requieren conexión a Internet hasta que esas dependencias se incorporen como recursos locales. Los datos guardados en la aplicación sí permanecen localmente.

## Compilación
Abrir el proyecto en Android Studio y ejecutar **Build > Generate App Bundles or APKs > Generate APKs**.

Application ID: `com.acgventas.mobile`
Version: `2.0`
