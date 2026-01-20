# Curso de Introducción a la Ingeniería Eléctrica y Electrónica - UPB

Material del curso de Introducción a la Ingeniería Eléctrica y Electrónica de la Universidad Pontificia Bolivariana.

## Contenido del Repositorio

### 📄 Archivos principales

1. **`plantilla_presentación.tex`** - Presentación completa en formato Beamer (LaTeX)
   - 17 diapositivas sobre la historia de la Ingeniería Eléctrica y Electrónica
   - Diseño con tema naranja personalizado de la UPB
   - Incluye logo de la universidad en todas las diapositivas

2. **`historia_ingenieria_IEE.md`** - Documento fuente en Markdown
   - Contenido completo de la presentación en formato de texto
   - Notas para el presentador
   - Referencias bibliográficas sugeridas

3. **`logo_UPB.jpg`** - Logo oficial de la Universidad Pontificia Bolivariana
   - Utilizado en la presentación Beamer

## 📊 Estructura de la Presentación

La presentación cubre los siguientes temas:

### Sección 1: Introducción a la Ingeniería (Diapositivas 1-5)
- ¿Qué es ingeniería?
- Historia general: desde la revolución agrícola hasta la Revolución Industrial
- De la técnica artesanal a la ciencia moderna

### Sección 2: Historia de la Ingeniería Eléctrica y Electrónica (Diapositivas 6-13)
- Fundamentos: de Gilbert a Faraday (1600-1831)
- Maxwell y las ecuaciones del electromagnetismo
- Guerra de corrientes: Edison vs Tesla
- Nacimiento de las redes eléctricas
- Era de las comunicaciones: telégrafo y radio
- Electrónica: tubos de vacío y semiconductores
- Era digital: transistor, circuito integrado y microprocesador
- Evolución de la seguridad eléctrica

### Sección 3: Lecciones de Fallos Históricos (Diapositivas 14-15)
- Fallos en infraestructura (Tacoma Narrows, apagones)
- Fallos de alto riesgo (Apollo 1, Therac-25, Chernóbil, Challenger, Ariane 5, Fukushima)

### Sección 4: Conclusiones (Diapositiva 16-17)
- Lecciones aprendidas para la Ingeniería Eléctrica y Electrónica
- La seguridad como parte integral del diseño

## 🚀 Cómo compilar la presentación

### Requisitos previos
Necesitas tener instalado:
- Una distribución de LaTeX (TeX Live, MiKTeX o MacTeX)
- Los siguientes paquetes LaTeX:
  - beamer
  - babel (con soporte para español)
  - tikz
  - hyperref
  - booktabs
  - natbib

### Compilación

#### En línea de comandos:
```bash
pdflatex plantilla_presentación.tex
pdflatex plantilla_presentación.tex  # Ejecutar dos veces para referencias
```

#### En editores LaTeX:
- **Overleaf**: Subir todos los archivos (.tex, .jpg) y compilar
- **TeXstudio, TeXworks, etc.**: Abrir el archivo .tex y compilar con pdfLaTeX

### Resultado
El proceso generará un archivo `plantilla_presentación.pdf` con la presentación lista para usar.

## 📚 Uso Educativo

Esta presentación está diseñada para:
- **Cursos introductorios** de Ingeniería Eléctrica y Electrónica
- **Duración**: Aproximadamente 30-35 minutos
- **Público**: Estudiantes universitarios de ingeniería
- **Nivel**: Introductorio

### Recomendaciones para el presentador:
1. Revisar las notas adicionales en `historia_ingenieria_IEE.md`
2. Agregar imágenes históricas y diagramas técnicos según disponibilidad
3. Adaptar el ritmo según el nivel de conocimiento de la audiencia
4. Usar los casos de fallos para generar discusión sobre ética y seguridad

## 🎨 Personalización

El diseño visual puede personalizarse modificando las siguientes líneas en el archivo `.tex`:

```latex
% Cambiar el color principal (actualmente naranja UPB)
\definecolor{MyOrange}{RGB}{230, 85, 10}

% Modificar información del título
\title[Historia IEE]{Título personalizado}
\subtitle{Subtítulo personalizado}
\author{Nombre del autor}
```

## 📖 Referencias

El documento incluye referencias bibliográficas sobre:
- Historia general de la ingeniería
- Historia de la ingeniería eléctrica
- Seguridad eléctrica
- Análisis de fallos en ingeniería

Consulte el archivo `historia_ingenieria_IEE.md` para la lista completa.

## 👥 Contribuciones

Este material es parte del curso de Introducción a la Ingeniería Eléctrica y Electrónica de la Universidad Pontificia Bolivariana.

## 📝 Licencia

Material educativo de la Universidad Pontificia Bolivariana.

---

**Universidad Pontificia Bolivariana**  
*Comprometidos con la excelencia académica*
