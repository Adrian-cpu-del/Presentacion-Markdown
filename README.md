# Presentacion-Markdown
# 📝 Presentación: Markdown (Lenguaje de Marcas)

![Markdown Badge](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![DAM Badge](https://img.shields.io/badge/Grado-DAM-blue?style=for-the-badge)
![Ecosistema Badge](https://img.shields.io/badge/Entorno-GitHub%20Flavored%20Markdown-brightgreen?style=for-the-badge)

> **Asignatura:** Lenguaje de Marcas y Sistemas de Gestión de Información  
> **Ciclo:** Grado Superior en Desarrollo de Aplicaciones Multiplataforma (DAM)  
> **Grupo:** Grupo 3  

---

## 📌 Índice de la Presentación

1. [Introducción y Filosofía](#1-introducción-y-filosofía)
2. [Sintaxis Básica de Markdown](#2-sintaxis-básica-de-markdown)
3. [Ecosistema y Casos de Uso en DAM](#3-ecosistema-y-casos-de-uso-en-dam)
4. [Markdown Extendido (GFM)](#4-markdown-extendido-gfm)
5. [Conclusiones](#5-conclusiones)

---

## 1. Introducción y Filosofía

* **Creadores:** Creado por John Gruber y Aaron Swartz en 2004.
* **Objetivo:** Conseguir un lenguaje de marcado ligero con el principio *Human-Readable* (fácil de leer y escribir en texto plano sin procesar).
* **Comparativa de Legibilidad:**

### HTML tradicional:
```html
<p>Este es un texto en <b>negrita</b> y una <a href="https://github.com">link</a>.</p>
```

### Equivalente en Markdown:
```markdown
Este es un texto en **negrita** y una [link](https://github.com).
```

---

## 2. Sintaxis Básica de Markdown

### Encabezados
```markdown
# Encabezado H1
## Encabezado H2
### Encabezado H3
```

### Formato de Texto
* **Negrita:** `**texto**`
* *Cursiva:* `*texto*`
* ~~Tachado:~~ `~~texto~~`

### Listas y Enlaces
- Listas desordenadas usando `-` o `*`
1. Listas ordenadas numeradas
- Enlaces: `[Nombre](URL)`
- Imágenes: `![Texto Alternativo](URL_Imagen)`

---

## 3. Ecosistema y Casos de Uso en DAM

Markdown es el estándar de documentación en la industria del software:

* 🐙 **GitHub / GitLab / Bitbucket:** Archivos `README.md` como carta de presentación de proyectos.
* ⚡ **Generadores de Sitios Estáticos (SSG):** Astro, Docusaurus, Hugo, MkDocs.
* 📓 **Herramientas de Notas y Productividad:** Obsidian, VS Code, Notion.

---

## 4. Markdown Extendido (GFM)

GitHub Flavored Markdown (GFM) añade funcionalidades avanzadas para desarrolladores:

### Bloque de Código con Coloreado de Sintaxis (Syntax Highlighting)

```java
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("¡Hola desde Markdown!");
    }
}
```

### Tablas de Datos
| Función | Sintaxis | Ejemplo |
| :--- | :---: | ---: |
| Negrita | `**texto**` | **Ejemplo** |
| Código Inline | `` `código` `` | `System.out` |

### Listas de Tareas (Task Lists)
- [x] Crear repositorio en GitHub
- [x] Redactar la documentación en `README.md`
- [ ] Presentar en clase y obtener un 10

---

## 5. Conclusiones

* **Ligero y Portable:** No depende de un software propietario (como MS Word).
* **Control de Versiones Friendly:** Ideal para integrarse con Git.
* **Estándar en la Industria:** Es la herramienta diaria de cualquier desarrollador de software.

---

### 🌐 Código QR de la Presentación
*Escanea el siguiente código para acceder a este documento renderizado en GitHub en tiempo real:*

![QR Code Placeholder](https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://github.com)
