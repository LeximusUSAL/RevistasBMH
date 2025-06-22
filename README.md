# Análisis Musical de Revistas Especializadas (1909-1917)

Una aplicación web interactiva para el análisis de contenido musical de dos revistas especializadas del período 1909-1917: **Revista Musical de Bilbao** y **Revista Musical Hispanoamericana**.

## 🌐 Demo en Vivo

[Ver análisis en GitHub Pages](https://mariapalaciosnieto.github.io/RevistasBMH/)

## 📊 Características

### Análisis Integral
- **78 números de revista** procesados con técnicas de procesamiento de lenguaje natural
- **11,085 personas identificadas** con análisis de género detallado
- **1,847 términos musicales únicos** extraídos del corpus
- **9 años de cobertura** (1909-1917)

### Secciones Interactivas

#### 📊 Resumen General
- Estadísticas globales del corpus analizado
- Visualizaciones de compositores, géneros e instrumentos más mencionados
- Datos comparativos entre ambas publicaciones

#### ⚖️ Análisis de Género
- **Ratio H:M de 0.78:1** - Primera evidencia de equilibrio en prensa musical especializada
- **Top 10 mujeres más mencionadas** con detalles de sus especialidades
- Comparativa con prensa generalista (18:1 en El Sol vs 0.78:1 en revistas)

#### 📈 Evolución Temporal
- Seguimiento año por año de menciones musicales
- Identificación de períodos de mayor actividad cultural
- Análisis de tendencias en gustos musicales

#### 🎵 Música y Compositores
- Rankings de compositores por número de menciones
- Distribución de géneros musicales dominantes
- Análisis de preferencias instrumentales

#### 📚 Léxico Musical
- **18.1% de densidad léxica musical** en el corpus
- Evolución temporal de terminología especializada
- Frecuencia de términos técnicos y formas musicales
- Análisis estadístico del vocabulario profesional

#### 🌍 Geografía Musical
- Mapeo de centros musicales mencionados
- Redes culturales España-Hispanoamérica
- Distribución geográfica de la actividad musical

#### 🔬 Metodología
- Descripción detallada del proceso de análisis
- Limitaciones y consideraciones técnicas
- Estadísticas de procesamiento

## 🛠️ Tecnologías Utilizadas

- **HTML5/CSS3** - Estructura y diseño responsivo
- **JavaScript ES6** - Lógica de interacción
- **Chart.js** - Visualizaciones de datos interactivas
- **Python** - Procesamiento de lenguaje natural para análisis de corpus
- **Expresiones regulares** - Extracción de entidades y patrones textuales

## 📈 Hallazgos Principales

### Representación de Género
- **Primera evidencia histórica** de equilibrio de género en prensa musical especializada
- **54.4% mujeres vs 45.6% hombres** - Contrasta con 94.7% hombres en prensa generalista
- **María Barrientos** como la figura femenina más mencionada (47 referencias)

### Landscape Musical
- **Beethoven** lidera las menciones de compositores (1,155 referencias)
- **Concierto** como género musical dominante (1,782 menciones)
- **Piano** como instrumento más frecuente (2,341 menciones, 15.0‰)

### Desarrollo Léxico
- **Período 1915-1916** con mayor riqueza léxica (21.3‰)
- **Cuarteto** experimentó el mayor crecimiento (+280% entre 1909-1917)
- **Armonía** como término técnico más estable (<3% variación)

## 📚 Contexto Académico

Este proyecto forma parte del corpus desarrollado por **"LexiMus, Léxico y ontología de la música en español"** (PID2022-139589NB-C33), con sede en la Universidad de Salamanca, en colaboración con el Instituto Complutense de Ciencias Musicales y la Universidad de La Rioja.

## 🎯 Relevancia Histórica

Las revistas analizadas representan un momento crucial en la profesionalización de la crítica musical en España:

- **Revista Musical de Bilbao (1909-1913)**: Primera publicación especializada del País Vasco
- **Revista Musical Hispanoamericana (1914-1917)**: Continuación en Madrid con proyección iberoamericana
- **Período de transición**: Del romanticismo tardío a las vanguardias musicales

## 📁 Estructura del Proyecto

```
/
├── web_revistas_musicales.html    # Aplicación web principal
├── LOGOS/                         # Logos institucionales
│   ├── Logo_USAL_Color_2012.png   # Universidad de Salamanca
│   └── Captura de pantalla...png   # Financiación del proyecto
└── README.md                      # Este archivo
```

## 🎨 Diseño y UX

- **Diseño responsivo** optimizado para desktop y móvil
- **Paleta de colores vibrante** para mejor legibilidad de datos
- **Navegación por pestañas** para organización lógica del contenido
- **Animaciones CSS** para transiciones suaves
- **Gráficos interactivos** con tooltips informativos

## 📊 Metodología de Análisis

### Procesamiento de Texto
- **40+ patrones de búsqueda** para extracción de entidades
- **Análisis contextual** de menciones para validación
- **Normalización** de variantes ortográficas históricas
- **Geolocalización** de referencias espaciales

### Validación de Datos
- **Precisión estimada: 90-95%** en identificación de entidades
- **Revisión manual** de casos ambiguos
- **Contexto histórico** para interpretación de resultados

## 🔍 Limitaciones

- **Calidad OCR**: Posibles errores en textos digitalizados históricos
- **Cobertura limitada**: Solo dos revistas especializadas
- **Sesgo editorial**: Refleja líneas editoriales específicas
- **Variaciones ortográficas**: Nombres con grafías diferentes pueden no consolidarse

## 📄 Licencia

Este proyecto está desarrollado para fines de investigación académica. Los datos utilizados pertenecen al dominio público (publicaciones 1909-1917).

## 👥 Contribución

Proyecto desarrollado en el marco de investigación musicológica. Para consultas académicas o colaboraciones, contactar con el equipo del proyecto LexiMus.

## Enlaces

Revistas alojadas en la Hemeroteca Digital de la Biblioteca Nacional de España. 
[Revista Musical de Bilbao](https://hemerotecadigital.bne.es/hd/es/card?sid=4122654)
[Revista Musical Hispanoamericana](https://hemerotecadigital.bne.es/hd/es/card?sid=3868950)


---

**🎼 "Analizando el pasado musical para comprender el presente"** • © 2024 Universidad de Salamanca
