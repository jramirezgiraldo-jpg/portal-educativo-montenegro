# 🌌 Actividades Juan Felipe Ramírez Giraldo | Instituto Montenegro

Bienvenido al repositorio oficial del **Portal Web de Recursos Educativos e Interactivos: Actividades Juan Felipe Ramírez Giraldo (Instituto Montenegro)**. Este proyecto centraliza, cataloga y despliega un conjunto de **101 actividades didácticas autónomas** (OVAs, laboratorios virtuales, desafíos, escape rooms y talleres guiados) diseñadas para fortalecer los procesos de aprendizaje en ciencias naturales, física, química, artes, ética y turismo regional.

Desarrollado bajo una arquitectura estática de alto rendimiento, **100% autónoma y sin dependencias externas**, garantizando tiempos de carga casi instantáneos y funcionamiento pleno fuera de línea (Offline-Ready) en cualquier dispositivo móvil o de escritorio.

---

## 🚀 Características Principales

* **Diseño UI/UX de Vanguardia (Bento Grid)**: Tarjetas modulares modernas con microinteracciones sutiles, código de color cromático según el área del conocimiento y tipografía nativa ultra-legible.
* **Experiencia Mobile-First Ergonómica**: Todos los botones y controles táctiles cuentan con un área accesible mínima de 48px, ideal para interacción en smartphones y tablets.
* **Buscador Instantáneo & Filtros Multifacéticos**:
  * Búsqueda en tiempo real por título, contenido pedagógico, conceptos clave y nombre de archivo.
  * Selector por áreas temáticas con contadores dinámicos.
  * Selector por tipo de dinámica (OVAs, Juegos/Retos, Sopas de Letras, Laboratorios y Guías).
* **Modo Oscuro / Modo Claro Nativo**: Detección automática de preferencia del sistema y selector manual con persistencia en `localStorage`.
* **Doble Modalidad de Interacción**:
  * **Iniciar en línea**: Abre la actividad seleccionada en una pestaña nueva con ejecución instantánea.
  * **Descargar (.html)**: Enlace con atributo `download` para guardar el archivo autónomo en el dispositivo y ejecutarlo en cualquier momento sin internet ni consumo de datos móviles.
* **Descarga Masiva en ZIP**: Paquete comprimido preconstruido (`actividades_completas.zip`, ~0.94 MB) con todas las actividades listo para ser distribuido a docentes o escuelas rurales en memorias USB.
* **100% Autónomo**: Sin llamadas a CDNs externas pesadas ni fuentes remotas; todos los iconos son vectores SVG nativos.

---

## 📂 Estructura del Repositorio

```text
Actividades ciencias naturales/
│
├── index.html                   # Portal principal interactivo (SPA estática)
├── actividades_data.js          # Catálogo estructurado de las 68 actividades (UTF-8)
├── actividades_data.json        # Respaldo JSON de metadatos pedagógicos
├── actividades_completas.zip    # Paquete comprimido offline (~0.94 MB)
├── render.yaml                  # Manifiesto de despliegue automatizado para Render Static
├── README.md                    # Documentación técnica y pedagógica
├── .gitignore                   # Exclusiones de control de versiones
│
└── actividades/                 # Repositorio de recursos didácticos (.html)
    ├── 4p 6 Fisica/             # Física Grado 6° (8 actividades)
    ├── 4p 7 Fisica/             # Física Grado 7° (8 actividades)
    ├── 4p 7 Turismo/            # Turismo y Paisaje Cultural Cafetero (9 actividades)
    ├── 4p Etica/                # Ética y Convivencia Humana (8 actividades)
    ├── 4p Musica/               # Educación Artística y Musical (8 actividades)
    ├── 4p Pensar Quimica/       # Pensar la Química (4 actividades)
    ├── Ciclo II/                # Nocturno Ciclo II - Ecosistemas y Biología (9 actividades)
    ├── Ciclo III/               # Nocturno Ciclo III - Biología Celular (8 actividades)
    ├── Ciclo IV/                # Nocturno Ciclo IV - Biología, Física y Química (26 actividades)
    │   ├── Biologia/            # Ciclo IV Biología (8 actividades)
    │   ├── Fisica/              # Ciclo IV Física (10 actividades)
    │   └── Quimica/             # Ciclo IV Química (8 actividades)
    └── Ciclo VI/                # Nocturno Ciclo VI - Física y Química (13 actividades)
        ├── Fisica/              # Ciclo VI Física (5 actividades)
        └── Quimica/             # Ciclo VI Química (8 actividades)
```

---

## 📊 Inventario de Actividades por Área

| Área / Dimensión | Grado / Nivel | Cantidad | Enfoque Pedagógico |
| :--- | :--- | :---: | :--- |
| **Física 6°** | Grado 6° | 8 | Fenómenos cotidianos de la estática, átomo, electrización por frotamiento, cargas eléctricas, conductores vs aislantes y electroscopio. |
| **Física 7°** | Grado 7° | 8 | Campo gravitacional, energía mecánica, energía potencial y altura, constante gravitatoria y revolución industrial. |
| **Turismo & PCC** | Grado 7° | 9 | Turismo local en Montenegro, atributos del Paisaje Cultural Cafetero (PCC), tipologías del turismo, impactos y mapeo de tesoros. |
| **Ética y Convivencia** | Formación Humana | 8 | Empatía hacia estudiantes nuevos, prejuicios y etiquetas, respeto en el disenso, comunicación asertiva y valor de la disculpa. |
| **Educación Musical** | Artes y Música | 8 | Geografía del piano y patrones de teclas, técnica pianística, solfeo rítmico, lectura en pentagrama y recital. |
| **Pensar la Química** | Secundaria / Media | 4 | Estados de agregación de la materia, clasificación de la materia, sustancias puras y mezclas homogéneas/heterogéneas. |
| **Nocturno Ciclo II** | CLEI II (4°-5°) | 9 | Ecosistemas terrestres y acuáticos, adaptaciones, factores bióticos/abióticos, niveles tróficos, redes tróficas y pirámides. |
| **Nocturno Ciclo III** | CLEI III (6°-7°) | 8 | Estructura celular, organelos celulares, respiración y división celular, niveles de organización, taxonomía y fotosíntesis. |
| **Nocturno Ciclo IV** | CLEI IV (8°-9°) | 26 | **Biología (8):** ADN, reproducción celular, genética, evolución, redes tróficas. <br>**Física (10):** Máquinas térmicas, transferencia de calor, trabajo y potencia. <br>**Química (8):** Tabla periódica, enlaces, reacciones y estequiometría. |
| **Nocturno Ciclo VI** | CLEI VI (10°-11°) | 13 | **Física (5):** Primera ley de Newton, ondas y luz, acústica agrícola y óptica. <br>**Química (8):** Química del carbono, hidrocarburos, biomoléculas y derivados del café. |

**Total de Actividades:** **101 recursos interactivos autónomos**.

---

## 🛠️ Flujo de Control de Versiones (Git y GitHub)

Sigue estos comandos desde la terminal dentro de esta carpeta para inicializar el repositorio y publicarlo en tu cuenta de GitHub:

```bash
# 1. Inicializar el repositorio Git local
git init

# 2. Agregar todos los archivos al control de versiones
git add .

# 3. Crear el primer commit con el mensaje de lanzamiento
git commit -m "feat: Portal web interactivo y catalogo de 68 actividades educativas - Instituto Montenegro"

# 4. Establecer la rama principal como 'main'
git branch -M main

# 5. Vincular el repositorio remoto en GitHub (reemplaza con tu URL de GitHub)
git remote add origin https://github.com/TU-USUARIO/portal-educativo-montenegro.git

# 6. Subir los archivos a GitHub
git push -u origin main
```

---

## 🌐 Despliegue en Render (Render Static Site)

El proyecto incluye el archivo `render.yaml` preconfigurado para despliegue automatizado continuo:

1. Ve a tu panel de control en [Render.com](https://dashboard.render.com).
2. Haz clic en **"New +"** y selecciona **"Static Site"** (o **"Blueprint"**).
3. Conecta tu repositorio de GitHub `portal-educativo-montenegro`.
4. Render detectará automáticamente el archivo `render.yaml` con los siguientes parámetros:
   * **Environment**: `Static`
   * **Build Command**: *(Vacío, no requiere transpilación)*
   * **Publish Directory**: `.` *(Raíz del repositorio)*
5. Haz clic en **"Create Static Site"**. En segundos, tu portal estará disponible en internet con certificado SSL gratuito (HTTPS) y URL personalizada (ejemplo: `https://portal-educativo-montenegro.onrender.com`).
6. Cada vez que realices un `git push` a la rama `main`, Render compilará y actualizará el portal automáticamente.

---

## 📱 Guía para Estudiantes: Uso 100% Fuera de Línea (Offline)

### En Teléfonos Android / iPhone / Tablets:
1. Conéctate a internet una sola vez para acceder al portal.
2. Encuentra la actividad que deseas desarrollar y presiona **"Descargar"**.
3. El archivo `.html` se guardará en tu carpeta de "Descargas".
4. Abre la aplicación de archivos de tu teléfono y toca el archivo `.html`.
5. Se abrirá automáticamente en tu navegador (Chrome, Safari, Samsung Internet, Edge) y funcionará perfectamente sin gastar datos ni tener Wi-Fi.

### Para Docentes y Aulas de Informática:
1. Haz clic en el botón superior **"Descargar Todo en ZIP"**.
2. Descomprime el archivo `actividades_completas.zip` en una memoria USB o en la carpeta pública de los computadores del colegio.
3. Abre el archivo `index.html` para navegar por todo el catálogo sin necesidad de conexión a internet.

---

## 📄 Autoría, Licencia y Reconocimientos

* **Docente y Desarrollador Pedagógico:** Juan Felipe Ramírez Giraldo
* **Institución:** Instituto Montenegro
* **Licencia:** Recurso educativo abierto de libre acceso, desarrollado con fines pedagógicos y no comerciales.
