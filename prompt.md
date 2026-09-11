# Prompt · Información estructurada

Este archivo contiene una instrucción base para utilizar IA como apoyo
en la investigación, organización y transformación de información.

La idea no es pedir directamente una página terminada.

El flujo de trabajo es:

```text
INFORMACIÓN
↓
MARKDOWN
↓
HTML SEMÁNTICO
↓
CSS
```

---

# Prompts

** Quiero construir un archivo markdown sobre los libros de Agatha Christie de la colección que salió del 2023 al 2025 de la editorial del Planeta de agostini; utiliza esta liga como base para obetener toda esa información https://www.planetadeagostini.com.mx/mx/culturales/agatha-christie. Antes de tener los libros me gustaria que utilizaras un titulo y tagline pensado en el tema de misterio de la autora. Estructura también este test: Título secundario: ¿Qué misterio eres? 

Descripción del test: 
Haz este pequeño test para descubrir qué historia de Agatha Christie podría esconderse detrás de tu forma de pensar. 

Estructura para las preguntas del test:
Subtítulo 01: 
Pregunta 1: Cuando llegas a un lugar desconocido…

Lista de opciones 01:

1. Observo todo antes de hablar.
2. Empiezo a hacer preguntas.
3. Me dejo llevar por la situación.
4. Busco a alguien que parezca sospechoso. 

Quiero mostrarle a la gente sobre cuáles son los tomos que salieron; es decir, saber cuál es el titulo del libro, su número de libro y cuándo salieron. utiliza igual esta información como parte para crear la estructura:  No obstante me gustaría que estos esten ordenados por las fechas en que salieron y quiero utilizar la misma estructura que usa Agatha Christie en sus libros como empezando por el título del libro, la presentación de los personajes enfocado a la autora y  luego a la historia. Como son libros porfavor me gustaría que busques las imagenes de estos libros y las descargues en formato no mayor a 1920 por 1080. - Organiza la información de manera consistente.
- No inventes datos, porfavor consulta fuentes vibles y agregalas al documento.
- Si un dato no está disponible, indícalo y busca alternativas de páginas donde podrían hablar sobre el tema o que sean relevantes.
- Mantén una jerarquía clara.
- Utiliza títulos, subtítulos, negritas, comillas, citas y referencias cuando sea necesario.
- Utiliza listas cuando exista información repetitiva o cuándo se deban enlistar libros, películas o series.
- Si se repite información que este ordenada dependiendo de la base de los elementos.
- Conserva enlaces a fuentes o recursos relevantes cuando corresponda.
- Prioriza fuentes confiables.
- No agregues diseño.
- No agregues CSS.
- No agregues JavaScript.
- Entrega el resultado en formato Markdown.
**

Necesito organizar información sobre:

**[ ]**

Antes de generar HTML, investiga y estructura la información.

## Objetivo

Construye un documento de información estructurada que pueda utilizarse para la información de libros de una colección especial que salió hace unos años y la diseñadora del sitio de la página web ha comprado no todos pero una parte de ellos y porque también conoce las novelas de Agatha Cristhie una de sus autoras favoritas. 

## Estructura

Cada elemento debe incluir los siguientes campos:

- [Libros]
- [Estilo]
- [Precio]
- [Autora]

Todos los elementos deben mantener exactamente la misma estructura.

## Reglas

- Organiza la información de manera consistente.
- No inventes datos, porfavor consulta fuentes vibles y agregalas al documento.
- Si un dato no está disponible, indícalo y busca alternativas de páginas donde podrían hablar sobre el tema o que sean relevantes.
- Mantén una jerarquía clara.
- Utiliza títulos, subtítulos, negritas, comillas, citas y referencias cuando sea necesario.
- Utiliza listas cuando exista información repetitiva o cuándo se deban enlistar libros, películas o series.
- Si se repite información que este ordenada dependiendo de la base de los elementos.
- Conserva enlaces a fuentes o recursos relevantes cuando corresponda.
- Prioriza fuentes confiables.
- No agregues diseño.
- No agregues CSS.
- No agregues JavaScript.
- Entrega el resultado en formato Markdown.

---

# Addon 01 · Orden y jerarquía

Agrega estas instrucciones cuando el contenido necesite un orden específico.

```text
Ordena los elementos utilizando el siguiente criterio:

[CRITERIO DE ORDEN]

Ejemplos:

- cronológico;
- por categoría;
- por color; 
- por título; 
- por fecha de entrega;
- por número de publicación.

Define claramente:

1. título principal;
2. introducción;
3. grupos o secciones;
4. elementos individuales;
5. información secundaria;
6. fuentes o enlaces.
```

---

# Addon 02 · Markdown → HTML

Utiliza este addon después de revisar y aprobar el archivo Markdown.

```text
Utiliza `base.html` como estructura base del documento.

Utiliza `[ARCHIVO].md` como única fuente de contenido.

Convierte la información a HTML semántico.

Reglas:

- Conserva la estructura general de `base.html`.
- Mantén `header`, `main` y `footer`.
- Organiza el contenido dentro de `main`.
- Utiliza `section` para grupos temáticos.
- Utiliza `article` cuando exista una unidad de contenido independiente.
- Utiliza encabezados de acuerdo con su jerarquía.
- Utiliza `p` para párrafos.
- Utiliza listas cuando corresponda.
- Utiliza `a` para enlaces.
- Utiliza `img` para imágenes.
- Conserva la información y el orden definidos en Markdown.
- No inventes contenido.
- No agregues CSS nuevo.
- No agregues JavaScript.
- No agregues estilos inline.
- Conserva el enlace a `style.css`.
- Devuelve un documento HTML completo y válido.
```

---

# Ejemplo de definición de estructura

Antes de investigar podemos definir la forma de los datos.

```text
COLECCIÓN
│
├── ELEMENTO
│   ├── título
│   ├── fecha
│   ├── descripción
│   ├── imagen
│   └── enlace
│
├── ELEMENTO
│   └── ...
│
└── ELEMENTO
    └── ...
```

El tema puede cambiar.

La estructura debe ser consistente.

---

# Regla de trabajo

No pedir:

> Hazme una página sobre [Libros de Agatha Christie-Colección que salió del 2023-2025].

Separar el problema:

1. definir qué información necesitamos;
2. estructurarla;
3. revisar el Markdown;
4. transformar esa estructura a HTML;
5. aplicar CSS después.

La IA ayuda a procesar y transformar información.

La estructura y las decisiones del proyecto siguen siendo responsabilidad
de quien diseña.
