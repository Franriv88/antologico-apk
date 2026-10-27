# Antológico — Aplicación Híbrida Android

**Package ID:** `app.antologico.android`  
**Versión:** 1.0  
**Plataforma:** Android 7.0+ (API 24+)

## Qué es

Antológico es una plataforma SaaS para profesionales que publican talleres y usuarios que los descubren, reservan y pagan. Esta aplicación Android es la interfaz móvil para usuarios finales.

La app está construida como una **Trusted Web Activity (TWA)** — arquitectura híbrida que integra la Progressive Web App de Antológico dentro de un contenedor nativo Android, validada por el estándar Digital Asset Links de Google.

## Instalación del APK

1. En tu dispositivo Android, activá **"Fuentes desconocidas"** en Ajustes → Seguridad.
2. Descargá el archivo `Antológico.apk` desde la sección [Releases](../../releases) de este repositorio.
3. Abrí el archivo descargado e instalá.

> Requiere Android 7.0 o superior.

## URLs de la plataforma

| Superficie | URL |
|---|---|
| App Mobile (TWA) | Ver sección [Releases](../../releases) |
| Panel Web (Profesionales) | https://www.antologico.app |
| Super Admin | https://admin.antologico.app |

## Estructura del repositorio

```
antologico-apk/
├── .well-known/
│   └── assetlinks.json   # Digital Asset Links (validación TWA)
├── docs/
│   └── Readme.html        # Instrucciones originales de PWA Builder
└── README.md
```

## Tecnología

- **Contenedor nativo:** Trusted Web Activity (TWA) — Android Jetpack
- **Generación del APK:** PWA Builder
- **Web app embebida:** React (Vite) + Tailwind CSS
- **Backend:** Firebase (Auth, Firestore, Cloud Functions)
- **Pagos:** Mercado Pago SDK

## Repositorio web

El código fuente de la web app está en: https://github.com/Franriv88/ANTOLOGICO

---

*Desarrollado con [PWA Builder](https://www.pwabuilder.com/)*
