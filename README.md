![Version](https://img.shields.io/badge/version-1.0.0-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)
![Status](https://img.shields.io/badge/status-active-lightgrey.svg)

# LinkAudit for Obsidian

Este es un plugin de muestra para Obsidian https://obsidian.md

Audita enlaces internos y detecta carpetas vacías dentro de tu vault de Obsidian. Ideal para mantener tu sistema limpio, organizado y sin notas huérfanas.

## Características
- Identifica archivos **sin ninguna referencia interna**
- Muestra también archivos **con referencias** (opcional)
- Detecta **carpetas vacías** sin archivos Markdown
- Analiza progresivamente y muestra estado de escaneo
- Abre directamente los archivos encontrados desde la vista
- Interfaz con opciones dentro de los ajustes del plugin


## 🚀 Instalación

### Método manual (GitHub)

1. Descarga este repositorio como `.zip`
2. Extrae el contenido
3. Copia la carpeta `LinkAudit-plugin` dentro de: <tu-vault>/.obsidian/plugins/
4. Abre Obsidian → *Settings* → *Community plugins*
5. Activa **LinkAudit**

> Asegúrate de tener activados los *Community plugins*.

## 🧠 Uso

1. Ve a **Settings → LinkAudit**
2. Selecciona la carpeta a analizar
3. Haz clic en **Buscar**
4. Explora los resultados desde la vista lateral

### Opciones disponibles

| Opción | Función |
|-------|--------|
| Mostrar archivos referenciados | Lista también los archivos que sí tienen enlaces |
| Verificar carpetas vacías | Encuentra carpetas sin archivos Markdown |

## ¿Para quién es?
- Usuarios que quieren mantener su Obsidian ordenado
- Personas con vaults grandes que desean encontrar notas sueltas
- Quienes migran de otros sistemas y necesitan limpiar contenido

## Estructura del proyecto

```
LinkAudit-plugin/
├── main.js
├── manifest.json
└─ styles.css
```

## Licencia

Este proyecto está bajo licencia **MIT**.

## Contribuciones

Pull requests y mejoras son bienvenidas.

## Documentación de la API
Consulta https://github.com/obsidianmd/obsidian-api