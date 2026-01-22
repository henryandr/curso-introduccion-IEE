# Curso de Introducción a la Ingeniería Eléctrica y Electrónica - UPB

Material del curso de Introducción a la Ingeniería Eléctrica y Electrónica de la Universidad Pontificia Bolivariana.

## Contenido del Repositorio

### 🎯 Talleres y Actividades

1. **`taller_resolucion_problemas.md`** - Taller completo: "Ingeniería al Servicio de la Sociedad"
   - Taller de 3 horas para aprendizaje activo
   - Metodología de resolución de problemas de ingeniería
   - 3 escenarios problemáticos reales
   - Estudio de caso guiado paso a paso
   - Actividades lúdicas y de debate
   - Rúbrica de evaluación completa
   - **Público:** Estudiantes de primer año
   - **Objetivo:** Comprender la diferencia entre ciencia, tecnología e ingeniería

2. **`guia_facilitador.md`** - Guía detallada para el docente
   - Instrucciones paso a paso para cada fase del taller
   - Cronogramas detallados y gestión del tiempo
   - Preguntas orientadoras para guiar a los estudiantes
   - Estrategias de facilitación y manejo de grupos
   - Recursos necesarios y preparación
   - Consejos prácticos de implementación

### 📄 Presentaciones

3. **`plantilla_presentación.tex`** - Presentación completa en formato Beamer (LaTeX)
   - 17 diapositivas sobre la historia de la Ingeniería Eléctrica y Electrónica
   - Diseño con tema naranja personalizado de la UPB
   - Incluye logo de la universidad en todas las diapositivas

4. **`historia_ingenieria_IEE.md`** - Documento fuente en Markdown
   - Contenido completo de la presentación en formato de texto
   - Notas para el presentador
   - Referencias bibliográficas sugeridas

5. **`logo_UPB.jpg`** - Logo oficial de la Universidad Pontificia Bolivariana
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

### Presentación sobre Historia de la IEE

Esta presentación está diseñada para:
- **Cursos introductorios** de Ingeniería Eléctrica y Electrónica
- **Duración**: Aproximadamente 30-35 minutos
- **Público**: Estudiantes universitarios de ingeniería
- **Nivel**: Introductorio

### Taller de Resolución de Problemas

Este taller está diseñado para:
- **Aprendizaje activo** mediante metodología ABP (Aprendizaje Basado en Problemas)
- **Duración**: 3 horas (adaptable a 2 horas)
- **Público**: Estudiantes de primer año de Ingeniería Eléctrica y Electrónica
- **Nivel**: Introductorio, sin conocimientos previos requeridos
- **Modalidad**: Presencial (con adaptaciones posibles para modalidad virtual)
- **Tamaño de grupo**: 20-30 estudiantes (4-6 grupos de 4-5 personas)

### Recomendaciones para el presentador:
1. Revisar las notas adicionales en `historia_ingenieria_IEE.md`
2. Agregar imágenes históricas y diagramas técnicos según disponibilidad
3. Adaptar el ritmo según el nivel de conocimiento de la audiencia
4. Usar los casos de fallos para generar discusión sobre ética y seguridad

### Recomendaciones para el facilitador del taller:
1. Leer completamente `taller_resolucion_problemas.md` y `guia_facilitador.md` antes de facilitar
2. Preparar materiales con anticipación (hojas de trabajo, marcadores, documentos impresos)
3. Organizar grupos de 4-5 estudiantes antes del taller
4. Ajustar tiempos según la dinámica del grupo
5. Enfatizar el proceso de pensamiento, no solo el resultado técnico
6. Fomentar la participación equitativa y el debate constructivo

## 🎨 Personalización

El diseño visual puede personalizarse modificando las siguientes líneas en el archivo `.tex`:

```latex
% Cambiar el color principal (actualmente naranja UPB: RGB 230, 85, 10)
\definecolor{MyOrange}{RGB}{230, 85, 10}

% Modificar información del título (valores actuales mostrados)
\title[Historia IEE]{Historia de la Ingeniería Eléctrica y Electrónica}
\subtitle{De los fundamentos a la era digital}
\author{Curso de Introducción a la IEE}
\institute[UPB]{Universidad Pontificia Bolivariana}
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
