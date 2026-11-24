# Portal Estudiantil – Universidad Tecnológica de Software

Portal web estático donde un estudiante de Ingeniería de Software (turno vespertino, ciclo 2026-2) puede consultar en un solo lugar su horario, sus calificaciones y sus trámites escolares.

> Proyecto académico. La universidad, el estudiante y todos los datos que aparecen son ficticios.

## Secciones

| Página | Descripción |
|---|---|
| `index.html` | Página de inicio con acceso a las tres secciones. |
| `horario.html` | Horario semanal de clases (lunes a viernes, 18:00 – 22:00) con materia y aula. |
| `calificaciones.html` | Calificaciones por materia, clave, estatus y promedio general. |
| `tramites.html` | Datos del estudiante, estatus de inscripción y estado de cuenta con pagos y saldo pendiente. |

## Tecnologías

- **HTML5**
- **Tailwind CSS**, cargado desde su CDN (`https://cdn.tailwindcss.com`)
- **Git y GitHub** para el trabajo en equipo con ramas y pull requests

No se necesita instalar dependencias, compilar ni usar un servidor.

## Cómo abrirlo

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Gberto777/portal-estudiantil-gpds.git
   cd portal-estudiantil-gpds
   ```
2. Abre `index.html` con doble clic en cualquier navegador.
3. Navega entre las secciones con los botones de la página de inicio.

> Se necesita conexión a internet para que carguen los estilos de Tailwind desde el CDN.

## Participantes

| Integrante | Aportación | Rama |
|---|---|---|
| Juan Gilberto ([@Gberto777](https://github.com/Gberto777)) | Estructura base, página de inicio y horario | `rama-juan` |
| Diego (RXLANDX) | Página de calificaciones | `rama-diego` |
| Uriel | Página de trámites | `rama-uriel` |
