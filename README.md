# Organigrama GAD Sureste (versión web)

Sitio estático: un solo archivo `index.html` más las carpetas `img/` y `docs/`. No necesita instalación.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio y sube todo el contenido de esta carpeta (`index.html`, `img/`, `docs/`).
2. En el repositorio entra a **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`.
3. En unos minutos el sitio queda disponible en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

> Importante: GitHub Pages es público aunque el repositorio sea privado (salvo planes empresariales). El sitio contiene psicometría, FODA, observaciones y evaluaciones de personas. Confirma con Recursos Humanos si puede publicarse así.

## Cómo editar datos

Todo el contenido está al inicio del bloque `<script>` de `index.html`, en `PLAZAS`:

- Cada persona es un objeto `{id, k (número de empleado), n (nombre), r (puesto)}`.
- `team:[...]` agrega a sus subordinados (admite un nivel más dentro de otro `team`).
- `perfil:{...}` agrega psicometría, FODA, observaciones, mapa estratégico, parrilla y proyectos.
- Para ocultar los números de empleado, pon `SHOW_CLAVE = false`.
- El selector de transiciones (abajo a la izquierda) se quita borrando la etiqueta `<label class="trsel">` y el bloque marcado como TRANSICIONES si ya elegiste una; el modo por defecto está en `trMode`.

## Fotos de personas (`img/<id>.jpg`, cuadradas)

Mientras falte una foto se muestran las iniciales.

| Archivo | Persona |
|---|---|
| `img/raul.jpg` | Raúl Martínez Vázquez |
| `img/darwin.jpg` | Darwin Palacios Rodríguez |
| `img/nicolas.jpg` | Nicolás Carrasco Solano |
| `img/flor.jpg` | Flor P. Hernández T. |
| `img/julio-cruz.jpg` | Julio Cruz Rivero |
| `img/juana.jpg` | Juana Santiago Gómez |
| `img/david.jpg` | David A. Saviñón Velázquez |
| `img/itzel.jpg` | Itzel V. Santos Martínez |
| `img/lilia.jpg` | Lilia Pinacho Pinacho |
| `img/luis.jpg` | Luis Hernández Velázquez |
| `img/guadalupe.jpg` | Guadalupe Cruz Cabrera |
| `img/isis.jpg` | Isis Mariana Gómez Crisanto |
| `img/zayda.jpg` | Zayda Natalia Sánchez Maya |
| `img/kristell.jpg` | Kristell Yamileth Gómez Fuentes |
| `img/andres.jpg` | Andrés Armando Ortiz Revilla |
| `img/veronica.jpg` | Verónica Gómez Morales |
| `img/leonides.jpg` | Leonides Campañ Velázquez |
| `img/carla.jpg` | Carla María Hernández |
| `img/joel.jpg` | Joel Hernández Morales |
| `img/gabriela.jpg` | Gabriela Ovando Sánchez |
| `img/argelia.jpg` | Argelia Pérez Arias |
| `img/guadalupe-valencia.jpg` | Guadalupe Valencia Hernández |
| `img/juana-ovando.jpg` | Juana Ovando Contreras |
| `img/cristian.jpg` | Cristian Alejandro Hernández Díaz |
| `img/azucena.jpg` | Azucena del Carmen Silva Ramos |
| `img/jaime.jpg` | Jaime Díaz Rodríguez |
| `img/ricardo.jpg` | Ricardo González Escobar |
| `img/julio.jpg` | Julio César Hernández Gómez |
| `img/johnny.jpg` | Johnny Alonso de Paz Vázquez |
| `img/jazmin.jpg` | Jazmín Elizabeth Montoya Maza |
| `img/paola.jpg` | Paola Arguello Hernández |
| `img/adolfo.jpg` | Adolfo Cuevas de la Cruz |
| `img/montserrat.jpg` | Montserrat Borges López |
| `img/brenda.jpg` | Brenda Janeth Ramos Gómez |
| `img/maria-carmen.jpg` | María del Carmen Hernández Carrasco |
| `img/carlos.jpg` | Carlos Alejandro Gómez González |
| `img/miguel.jpg` | Miguel Ángel Sánchez Ovando |
| `img/anna.jpg` | Anna Esperanza López Flores |

## Otras imágenes

| Archivo | Uso |
|---|---|
| `img/integracion.jpg` | Pantallas del mapa estratégico |
| `img/linkedin.jpg` | Pantallas del mapa estratégico |
| `img/erp.jpg` | Pantallas del mapa estratégico |
| `img/office365.jpg` | Pantallas del mapa estratégico |
| `img/evaluacion-desempeno.png` | Pantallas del mapa estratégico |
| `img/anna-1er-trimestre.png` | Formato de evaluación (EDI) trimestral |
| `img/anna-2do-trimestre.png` | Formato de evaluación (EDI) trimestral |
| `img/juana-1er-trimestre.png` | Formato de evaluación (EDI) trimestral |
| `img/juana-2do-trimestre.png` | Formato de evaluación (EDI) trimestral |
| `img/julio-cruz-1er-trimestre.png` | Formato de evaluación (EDI) trimestral |
| `img/julio-cruz-2do-trimestre.png` | Formato de evaluación (EDI) trimestral |
| `img/nicolas-1er-trimestre.png` | Formato de evaluación (EDI) trimestral |
| `img/nicolas-2do-trimestre.png` | Formato de evaluación (EDI) trimestral |
| `img/proyectos/control-gate.png` | Carátula del proyecto Control Gate |
| `img/proyectos/semaforo-cia.png` | Carátula del proyecto Semáforo CIA |
| `img/proyectos/happy-moments.png` | Carátula del proyecto Happy Moments |
| `img/proyectos/concil-ia.png` | Carátula del proyecto Concil.IA |
| `img/proyectos/admin-bus360.png` | Carátula del proyecto Admin Bus360 |
| `img/proyectos/digital-formats.png` | Carátula del proyecto Digital Formats |
| `img/proyectos/alerta-gerencial.png` | Carátula del proyecto Alerta Gerencial |
| `img/proyectos/monitor-pistas-efectivo.png` | Carátula del proyecto Monitor de pistas en efectivo |
| `img/camion-ado.png` | Autobús de la transición (incluido) |

## Documentos (`docs/`, PDF)


- `docs/evaluacion-desempeno.pdf`
- `docs/parrilla-darwin.pdf`
- `docs/parrilla-julio.pdf`
- `docs/parrilla-leonides.pdf`
- `docs/parrilla-lilia.pdf`
- `docs/parrilla-miguel.pdf`
- `docs/parrilla-reemplazo.pdf`
