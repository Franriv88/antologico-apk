# Antológico — Aplicación Híbrida Android

**Package ID:** `app.antologico.android`  
**Versión:** 1.0  
**Plataforma:** Android 7.0+ (API 24+)

## Qué es

Antológico es una plataforma SaaS para profesionales que publican talleres y usuarios que los descubren, reservan y pagan. Esta aplicación Android es la interfaz móvil para usuarios finales.

La app es una **aplicación híbrida Android** que combina una capa nativa con una interfaz web de alto rendimiento, validada mediante el estándar Digital Asset Links de Google para integración segura con el dominio `www.antologico.app`.

## Instalación del APK

1. En tu dispositivo Android, activá **"Fuentes desconocidas"** en Ajustes → Seguridad.
2. Descargá el archivo `Antológico.apk` desde la sección [Releases](../../releases) de este repositorio.
3. Abrí el archivo descargado e instalá.

> Requiere Android 7.0 o superior.

## URLs de la plataforma

| Superficie | URL |
|---|---|
| App Mobile | Ver sección [Releases](../../releases) |
| Panel Web (Profesionales) | https://www.antologico.app |
| Super Admin | https://admin.antologico.app |

## Estructura del repositorio

```
antologico-apk/
├── .well-known/
│   └── assetlinks.json   # Digital Asset Links (verificación de dominio)
├── docs/
│   └── Readme.html        # Documentación técnica
└── README.md
```

## Tecnología

- **Arquitectura:** Aplicación híbrida Android (capa nativa + interfaz web)
- **SDK:** Android Jetpack
- **Interfaz:** React (Vite) + Tailwind CSS
- **Backend:** Firebase (Auth, Firestore, Cloud Functions)
- **Pagos:** Mercado Pago SDK

## Repositorio web

El código fuente de la web app está en: https://github.com/Franriv88/ANTOLOGICO
