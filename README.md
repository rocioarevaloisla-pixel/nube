# Cloud Computing — Registro de Flores

Sistema de la asignatura Computación en la Nube (IP Santo Tomás) para registrar flores con un CRUD completo. Ofrece dos modos de almacenamiento.

## Funcionalidades
- CRUD de flores: Nombre, Color, Temporada, Precio y Stock.
- Almacenamiento en localStorage del navegador.
- Almacenamiento en la nube con Firebase Firestore.

## Estructura
- `index.html` — portada con acceso a ambos modos.
- `css/style.css` — estilos.
- `img/logo.png` — logo del instituto.
- `html/tabla-local.html` — CRUD con localStorage.
- `html/tabla-firebase.html` — CRUD con Firebase Firestore.

## Ejecutar localmente
Abre `index.html` en tu navegador (doble clic) o usa:
- `firebase serve` (con Firebase CLI).

## Desplegar en Firebase Hosting
1. `firebase login`
2. `firebase deploy` (el proyecto activo es `nube-4b69e`)

Web: https://nube-4b69e.web.app

## Config adicional
- `firestore.rules` — reglas de Firestore (modo demo): permiten lectura/escritura pública.
