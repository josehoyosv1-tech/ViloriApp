<p align="center">
  <img src="assets/logo.png" alt="ViloriApp Logo" width="150"/>
</p>

<h1 align="center">🐄 ViloriApp</h1>
<h3 align="center">Control Ganadero Inteligente</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Dart-3.x-blue?logo=dart" alt="Dart"/>
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License"/>
  <img src="https://img.shields.io/badge/Platform-Android-green?logo=android" alt="Android"/>
  <img src="https://img.shields.io/badge/Status-Production-success" alt="Status"/>
</p>

<p align="center">
  <a href="#-características">Características</a> •
  <a href="#-tecnologías">Tecnologías</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-roadmap">Roadmap</a> •
  <a href="#-contacto">Contacto</a>
</p>

---

## 📝 Descripción

**ViloriApp** es una aplicación móvil desarrollada en **Flutter** que transforma la gestión tradicional de ganado bovino en un proceso **digital, inteligente y eficiente**. Diseñada especialmente para ganaderos que trabajan en zonas **sin conectividad a internet**, permitiendo llevar el control total de su rebaño desde su dispositivo móvil.

### 🎯 Problema que resuelve

Los ganaderos tradicionalmente llevan registros en libretas físicas, lo que genera:
- ❌ Pérdida de información
- ❌ Dificultad para acceder al historial
- ❌ Imposibilidad de generar estadísticas
- ❌ Olvido de fechas importantes (vacunas, partos, revisiones)
- ❌ Falta de trazabilidad genealógica

### 💡 Solución

Una aplicación **100% offline-first** que permite registrar, monitorear y analizar toda la información del rebaño con inteligencia automatizada.

---

## ✨ Características

### 🐄 Gestión Completa de Animales
- Registro detallado con más de 15 campos por animal
- **Fotografías con recortador integrado** (zoom y arrastre)
- Persistencia de fotos en almacenamiento permanente
- Visor de fotos a pantalla completa con zoom interactivo

### 🧬 Árbol Genealógico
- Vinculación madre/padre (registrado o externo)
- Linaje materno y paterno navegable
- Identificación automática del **toro más productivo**
- Contador de descendientes

### 🔔 Sistema Inteligente de Alertas
Motor que analiza automáticamente todos los animales y genera alertas en 3 niveles:
- 🚨 **Urgentes**: Partos inminentes, vacunas atrasadas, condición crítica
- ⚠️ **Importantes**: Vacunas próximas, servicios necesarios
- ℹ️ **Informativas**: Revisiones pendientes, novillas listas para servicio

### 📷 Modo Revisión en Campo
- 3 vistas configurables (Grid, Lista, Detallada)
- Marcado con doble-tap para máxima eficiencia
- **Reconocimiento de voz** en español (Colombia) con búsqueda fuzzy
- Sesión persistente (recuerda el progreso al cerrar la app)

### 💾 Sistema de Backup Completo
- Exportación a archivo **ZIP** (datos + fotos)
- Importación con validación y progreso visual
- Compartir backup por WhatsApp, email, etc.
- Versionado y compatibilidad con backups anteriores

### 📊 Dashboard y Estadísticas
- Estadísticas en tiempo real
- Gráficos de distribución (dueño, ubicación, estado)
- Métricas clave de productividad

### 📅 Recordatorios Inteligentes
- 5 categorías predefinidas (Pagos, Salud, Potreros, etc.)
- Sistema de recurrencia (semanal, mensual, anual)
- Auto-generación del próximo recordatorio

---

## 🛠️ Tecnologías

| Categoría | Tecnología |
|-----------|------------|
| **Framework** | Flutter 3.x |
| **Lenguaje** | Dart |
| **Base de datos** | SQLite (sqflite) |
| **Cámara** | image_picker |
| **Voz** | speech_to_text |
| **Permisos** | permission_handler |
| **Backup** | archive, file_picker, share_plus |
| **Arquitectura** | Service Layer Pattern |

---

## 📸 Screenshots

| Home | Agregar Animal | Ficha |
|:---:|:---:|:---:|
| ![Home](screenshots/home.png) | ![Agregar](screenshots/agregar.png) | ![Ficha](screenshots/ficha.png) |

| Ver Ganado | Modo Revisión | Dashboard |
|:---:|:---:|:---:|
| ![Ganado](screenshots/ganado.png) | ![Revisión](screenshots/revision.png) | ![Dashboard](screenshots/dashboard.png) |

| Alertas | Backup | Configuración |
|:---:|:---:|:---:|
| ![Alertas](screenshots/alertas.png) | ![Backup](screenshots/backup.png) | ![Config](screenshots/config.png) |

> 📌 *Nota: Los screenshots se agregarán próximamente*

---

## 🚀 Instalación

### Requisitos previos
- Flutter SDK 3.x o superior
- Android Studio / VS Code
- Dispositivo Android o emulador

### Pasos

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/viloriapp.git
   cd viloriapp
