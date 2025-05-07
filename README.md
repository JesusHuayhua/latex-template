# 📁 Plantillas LaTeX - Reportes, Presentaciones y más

Colección de plantillas profesionales en LaTeX para reportes, presentaciones (beamer), documentos académicos y otros formatos útiles.

## 📦 Contenido

- **📄 Reportes**: 
  - Plantilla para informes técnicos/académicos
  - Versión con diseño moderno/clásico
  - Incluye ejemplos de tablas, figuras y ecuaciones

- **🎤 Presentaciones (Beamer)**: 
  - Plantilla para presentaciones académicas
  - Versión minimalista y corporativa
  - Incluye diagramas y transiciones

## 🚀 Cómo usar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   ```
2. Compila los archivos `.tex` con tu distribución LaTeX favorita (TeXLive, MikTeX, etc.)
3. Modifica los archivos según tus necesidades

## ✨ Ejemplo de la Estructura propuesta

```lua
proyecto/
│── main.tex                    -- Archivo principal (incluye/configura módulos)
├── configuraciones/            -- ⚙️ Configuraciones centralizadas
│   ├── paquetes.tex           -- 📦 Todos los paquetes y configuraciones globales
│   ├── configuraciones.tex    -- ⚙️ Todos las configuraciones personales de los paquetes
│   ├── estilos_personalizados.tex -- ✨ Comandos/\newenvironments personalizados
│   └── colores.tex            -- 🎨 Paleta de colores (RGB/HEX/Corporativos)
│
├── figuras/                    -- 🖼️ Assets visuales (organizados por tipo)
│   ├── diagramas/              -- 📊 Diagramas técnicos (TikZ/Inkscape)
│   │   ├── diagrama1.pdf       -- - Exportados como PDF para máxima calidad
│   │   └── flujo.svg           -- - SVG para edición futura
│   ├── fotos/                  -- 📷 Fotografías/ilustraciones
│   │   ├── experimento1.jpg    -- - JPEG para fotos
│   │   └── montaje.png         -- - PNG para gráficos simples
│   └── graficos/               -- 📈 Gráficos generados (Python/MATLAB)
│       ├── resultados1.pdf     -- - Vectorial (PDF/EPS)
│       └── comparacion.eps     -- - PostScript encapsulado
│
├── portada/                    -- 🏛️ Material preliminar
│   ├── caratula.tex            -- - Portada oficial (con logos institucionales)
│   ├── resumen.tex             -- - Abstract (ES/EN)
│   └── agradecimientos.tex     -- - Dedicatorias/agradecimientos
│
├── capitulos/                   -- 📚 Capítulos, Secciones(depende del tipo de documento que este realizando)
│   ├── 01_primer_capitulo/     -- - Cada capítulo en directorio separado
│   │   ├── main.tex            --   Archivo maestro del capítulo
│   │   └── 01_primera_subseccion.tex -- Subsecciones incluidas via \input
│   ├── 02_segundo_capitulo/    -- - Numeración consistente
│   │   ├── main.tex            --   (02_*, 03_*, etc.)
│   │   ├── 01_primera_subseccion.tex  
│   │   └── 02_segunda_subseccion.tex   
│
├── contraportada/              -- 📜 Material final
│   ├── conclusiones.tex        -- - Conclusiones y trabajo futuro
│   └── anexos/                 -- 📑 Anexos técnicos
│       ├── anexo_a.tex         -- - Códigos fuente largos
│       └── anexo_b.tex         -- - Datos adicionales
│
└── bibliografia.bib            -- 🧠 Base de datos de referencias (Zotero/JabRef)
```

## 📝 Licencia

Este proyecto está bajo [Licencia MIT](LICENSE) - siéntete libre de usar y modificar estas plantillas.

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si quieres añadir tu plantilla:
1. Haz fork del repositorio
2. Crea una rama con tu plantilla (`git checkout -b mi-plantilla`)
3. Haz commit de tus cambios (`git commit -m 'Añadí plantilla para X'`)
4. Haz push a la rama (`git push origin mi-plantilla`)
5. Abre un Pull Request

---

⭐ Si te gusta este proyecto, dale una estrella en GitHub para apoyar su desarrollo.
```