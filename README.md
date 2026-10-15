# ðŸŒŒ Actividades Juan Felipe RamÃ­rez Giraldo | Instituto Montenegro

Bienvenido al repositorio oficial del **Portal Web de Recursos Educativos e Interactivos: Actividades Juan Felipe RamÃ­rez Giraldo (Instituto Montenegro)**. Este proyecto centraliza, cataloga y despliega un conjunto de **124 actividades didÃ¡cticas autÃ³nomas** (OVAs, laboratorios virtuales, desafÃ­os, escape rooms, talleres de inclusiÃ³n y lectoescritura, y guÃ­as interactivas) diseÃ±adas para fortalecer los procesos de aprendizaje en ciencias naturales, fÃ­sica, quÃ­mica, biologÃ­a, artes, Ã©tica y turismo regional.

Desarrollado bajo una arquitectura estÃ¡tica de alto rendimiento, **100% autÃ³noma y sin dependencias externas**, garantizando tiempos de carga casi instantÃ¡neos y funcionamiento pleno fuera de lÃ­nea (Offline-Ready) en cualquier dispositivo mÃ³vil o de escritorio.

---

## ðŸš€ CaracterÃ­sticas Principales

* **DiseÃ±o UI/UX de Vanguardia (Bento Grid)**: Tarjetas modulares modernas con microinteracciones sutiles, cÃ³digo de color cromÃ¡tico segÃºn el Ã¡rea del conocimiento y tipografÃ­a nativa ultra-legible.
* **Cajones Disciplinares para Ciclos Multidisciplinares**: Ciclo IV y Ciclo VI organizados en carpetas/cajones independientes para BiologÃ­a, FÃ­sica y QuÃ­mica.
* **MÃ³dulos de Adaptaciones Curriculares e InclusiÃ³n**: Recursos pedagÃ³gicos especializados ("Mis Primeras Palabras") para estudiantes con necesidades formativas diversas y lectura asistida.
* **Experiencia Mobile-First ErgonÃ³mica**: Todos los botones y controles tÃ¡ctiles cuentan con un Ã¡rea accesible mÃ­nima de 48px, ideal para interacciÃ³n en smartphones y tablets.
* **Buscador InstantÃ¡neo & Filtros MultifacÃ©ticos**:
  * BÃºsqueda en tiempo real por tÃ­tulo, contenido pedagÃ³gico, conceptos clave y nombre de archivo.
  * Selector por Ã¡reas temÃ¡ticas con contadores dinÃ¡micos.
  * Selector por tipo de dinÃ¡mica (OVAs, Juegos/Retos, Sopas de Letras, Laboratorios y GuÃ­as).
* **Modo Oscuro / Modo Claro Nativo**: DetecciÃ³n automÃ¡tica de preferencia del sistema y selector manual con persistencia en `localStorage`.
* **Doble Modalidad de InteracciÃ³n**:
  * **Iniciar en lÃ­nea**: Abre la actividad seleccionada en una pestaÃ±a nueva con ejecuciÃ³n instantÃ¡nea.
  * **Descargar (.html)**: Enlace con atributo `download` para guardar el archivo autÃ³nomo en el dispositivo y ejecutarlo en cualquier momento sin internet ni consumo de datos mÃ³viles.
* **Descarga Masiva en ZIP**: Paquete comprimido preconstruido (`actividades_completas.zip`, ~1.38 MB) con todas las actividades listo para ser distribuido a docentes o escuelas rurales en memorias USB.
* **100% AutÃ³nomo**: Sin llamadas a CDNs externas pesadas ni fuentes remotas; todos los iconos son vectores SVG nativos con escalado responsivo seguro.

---

## ðŸ“‚ Estructura del Repositorio

```text
Actividades ciencias naturales/
â”‚
â”œâ”€â”€ index.html                   # Portal principal interactivo (SPA estÃ¡tica)
â”œâ”€â”€ actividades_data.js          # CatÃ¡logo estructurado de las 124 actividades (UTF-8)
â”œâ”€â”€ actividades_data.json        # Respaldo JSON de metadatos pedagÃ³gicos
â”œâ”€â”€ actividades_completas.zip    # Paquete comprimido offline (~1.38 MB)
â”œâ”€â”€ render.yaml                  # Manifiesto de despliegue automatizado para Render Static
â”œâ”€â”€ README.md                    # DocumentaciÃ³n tÃ©cnica y pedagÃ³gica
â”œâ”€â”€ .gitignore                   # Exclusiones de control de versiones
â”‚
â””â”€â”€ actividades/                 # Repositorio de recursos didÃ¡cticos (.html)
    â”œâ”€â”€ 4p 6 Fisica/                                 # FÃ­sica Grado 6Â° (8 actividades)
    â”œâ”€â”€ 4p Fisica 6 Adpataciones curriculares/       # FÃ­sica 6Â° InclusiÃ³n (8 actividades)
    â”œâ”€â”€ 4p 7 Fisica/                                 # FÃ­sica Grado 7Â° (8 actividades)
    â”œâ”€â”€ 4p 7 Turismo/                                # Turismo y Paisaje Cafetero (9 actividades)
    â”œâ”€â”€ 4p Etica/                                    # Ã‰tica y Valores (8 actividades)
    â”œâ”€â”€ 4p Musica/                                   # EducaciÃ³n Musical (8 actividades)
    â”œâ”€â”€ 4p Pensar Quimica/                           # Pensar la QuÃ­mica (4 actividades)
    â”œâ”€â”€ Ciclo II/                                    # Nocturno Ciclo II (9 actividades)
    â”œâ”€â”€ Ciclo II Adpataciones curriculares/          # Ciclo II InclusiÃ³n (6 actividades)
    â”œâ”€â”€ Ciclo III/                                   # Nocturno Ciclo III (8 actividades)
    â”œâ”€â”€ Ciclo IV/                                    # Nocturno Ciclo IV (26 actividades)
    â”‚   â”œâ”€â”€ Biologia/                                # Ciclo IV BiologÃ­a (8 actividades)
    â”‚   â”œâ”€â”€ Fisica/                                  # Ciclo IV FÃ­sica (10 actividades)
    â”‚   â””â”€â”€ Quimica/                                 # Ciclo IV QuÃ­mica (8 actividades)
    â””â”€â”€ Ciclo VI/                                    # Nocturno Ciclo VI (22 actividades)
        â”œâ”€â”€ Biologia/                                # Ciclo VI BiologÃ­a (9 actividades)
        â”œâ”€â”€ Fisica/                                  # Ciclo VI FÃ­sica (5 actividades)
        â””â”€â”€ Quimica/                                 # Ciclo VI QuÃ­mica OrgÃ¡nica (8 actividades)
```

---

## ðŸ“Š Inventario de Actividades por Ãrea

| Ãrea / DimensiÃ³n | Grado / Nivel | Cantidad | Enfoque PedagÃ³gico |
| :--- | :--- | :---: | :--- |
| **FÃ­sica 6Â°** | Grado 6Â° | 8 | FenÃ³menos cotidianos de la estÃ¡tica, Ã¡tomo, electrizaciÃ³n por frotamiento, cargas elÃ©ctricas, conductores vs aislantes y electroscopio. |
| **FÃ­sica 6Â° (Adaptaciones)** | Grado 6Â° (InclusiÃ³n) | 8 | Mis Primeras Palabras: vocabulario accesible, conceptos esenciales de estÃ¡tica, materia, cargas y frotamiento. |
| **FÃ­sica 7Â°** | Grado 7Â° | 8 | Campo gravitacional, energÃ­a mecÃ¡nica, energÃ­a potencial y altura, constante gravitatoria y revoluciÃ³n industrial. |
| **Turismo & PCC** | Grado 7Â° | 9 | Turismo local en Montenegro, atributos del Paisaje Cultural Cafetero (PCC), tipologÃ­as del turismo, impactos y mapeo de tesoros. |
| **Ã‰tica y Convivencia** | FormaciÃ³n Humana | 8 | EmpatÃ­a hacia estudiantes nuevos, prejuicios y etiquetas, respeto en el disenso, comunicaciÃ³n asertiva y valor de la disculpa. |
| **EducaciÃ³n Musical** | Artes y MÃºsica | 8 | GeografÃ­a del piano y patrones de teclas, tÃ©cnica pianÃ­stica, solfeo rÃ­tmico, lectura en pentagrama y recital. |
| **Pensar la QuÃ­mica** | Secundaria / Media | 4 | Estados de agregaciÃ³n de la materia, clasificaciÃ³n de la materia, sustancias puras y mezclas homogÃ©neas/heterogÃ©neas. |
| **Nocturno Ciclo II** | CLEI II (4Â°-5Â°) | 9 | Ecosistemas terrestres y acuÃ¡ticos, adaptaciones, factores biÃ³ticos/abiÃ³ticos, niveles trÃ³ficos, redes trÃ³ficas y pirÃ¡mides. |
| **Ciclo II (Adaptaciones)** | CLEI II (InclusiÃ³n) | 6 | Mis Primeras Palabras: ecosistemas, adaptaciones de seres vivos, factores biÃ³ticos/abiÃ³ticos, cadenas trÃ³ficas y cafÃ©. |
| **Nocturno Ciclo III** | CLEI III (6Â°-7Â°) | 8 | Estructura celular, organelos celulares, respiraciÃ³n y divisiÃ³n celular, niveles de organizaciÃ³n, taxonomÃ­a y fotosÃ­ntesis. |
| **Nocturno Ciclo IV** | CLEI IV (8Â°-9Â°) | 26 | **BiologÃ­a (8):** ADN, reproducciÃ³n celular, genÃ©tica, evoluciÃ³n, redes trÃ³ficas. <br>**FÃ­sica (10):** MÃ¡quinas tÃ©rmicas, transferencia de calor, trabajo y potencia. <br>**QuÃ­mica (8):** Tabla periÃ³dica, enlaces, reacciones y estequiometrÃ­a. |
| **Nocturno Ciclo VI** | CLEI VI (10Â°-11Â°) | 22 | **BiologÃ­a (9):** EcologÃ­a de poblaciones cafeteras, redes trÃ³ficas, ciclos de suelos, biodiversidad, fotosÃ­ntesis, fermentaciÃ³n y biotecnologÃ­a. <br>**FÃ­sica (5):** Primera ley de Newton, ondas y luz, acÃºstica agrÃ­cola y escape room de Ã³ptica. <br>**QuÃ­mica OrgÃ¡nica (8):** QuÃ­mica del carbono, hidrocarburos, biomolÃ©culas y derivados del cafÃ©. |

**Total de Actividades:** **124 recursos interactivos autÃ³nomos**.

---

## ðŸ› ï¸ Flujo de Control de Versiones (Git y GitHub)

```bash
# 1. Comprobar estado
git status

# 2. Agregar cambios
git add .

# 3. Crear commit descriptivo
git commit -m "feat: sincronizacion de 124 actividades, cajones de Ciclo VI y modulos de inclusion curricular"

# 4. Enviar a GitHub
git push origin main
```

---

## ðŸŒ Despliegue en Render y GitHub Pages

* **GitHub Pages**: `https://jramirezgiraldo-jpg.github.io/portal-educativo-montenegro/`
* **Render**: SincronizaciÃ³n continua conectada a la rama `main` mediante `render.yaml`.

---

## ðŸ“± GuÃ­a para Estudiantes: Uso 100% Fuera de LÃ­nea (Offline)

### En TelÃ©fonos Android / iPhone / Tablets:
1. ConÃ©ctate a internet una sola vez para acceder al portal.
2. Encuentra la actividad que deseas desarrollar y presiona **"Descargar"**.
3. El archivo `.html` se guardarÃ¡ en tu carpeta de "Descargas".
4. Abre la aplicaciÃ³n de archivos de tu telÃ©fono y toca el archivo `.html`.
5. Se abrirÃ¡ automÃ¡ticamente en tu navegador (Chrome, Safari, Samsung Internet, Edge) y funcionarÃ¡ perfectamente sin gastar datos ni tener Wi-Fi.

### Para Docentes y Aulas de InformÃ¡tica:
1. Haz clic en el botÃ³n superior **"Descargar ZIP"**.
2. Descomprime el archivo `actividades_completas.zip` en una memoria USB o en la carpeta pÃºblica de los computadores del colegio.
3. Abre el archivo `index.html` para navegar por todo el catÃ¡logo sin necesidad de conexiÃ³n a internet.

---

## ðŸ“„ AutorÃ­a, Licencia y Reconocimientos

* **Docente y Desarrollador PedagÃ³gico:** Juan Felipe RamÃ­rez Giraldo
* **InstituciÃ³n:** Instituto Montenegro
* **Licencia:** Recurso educativo abierto de libre acceso, desarrollado con fines pedagÃ³gicos y no comerciales.