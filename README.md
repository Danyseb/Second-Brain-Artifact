# Segundo Cerebro

Mapa cognitivo personal de Dany: notas por área de vida conectadas en un grafo, con un Entrevistador que guarda lo importante, un Terapeuta (Dr. Rogers: TCC, ACT y Esquemas) y análisis de patrones.

- **Artefacto en vivo:** https://claude.ai/artifact/Di3FhTcJv86q9eHhMKHBix (privado)
- **Skill:** `skill/segundo-cerebro/SKILL.md` escribe notas en el artefacto desde cualquier chat de Claude.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | Código del artefacto (HTML autocontenido) |
| `skill/segundo-cerebro/SKILL.md` | Skill de Claude que alimenta el artefacto |

## Funciones (v2)

- **Cerebro:** grafo por áreas (local, zoom con rueda o pellizco, encuadre automático), notas con formato y [[enlaces]] clicables, autoguardado, renombrar actualiza enlaces, deshacer al borrar.
- **+ Captura (Ctrl K):** texto suelto a la nota del día o repartido en notas por la IA, con vista previa.
- **Entrevistador y Terapeuta (Dr. Rogers):** buscan y leen notas completas, amplían notas sin borrar lo anterior, sesiones retomables, botón Detener y aviso de crisis.
- **Patrones:** resumen, peso por área, notas por semana, etiquetas, notas sin conectar, línea de tiempo e historial de análisis.
- **Ajustes:** meta-prompt, respaldo .json, vault de Obsidian .zip, importación (.json, .zip, .md), estado de conexión y atajos.
- Oculta números de tarjeta, cuenta o CURP y contraseñas, y guarda solo los últimos 4 dígitos. Fechas en hora de Ciudad de México.

## Cómo funciona

El artefacto corre dentro de claude.ai y usa tres capacidades:

- `db`: guarda notas (`nodes`), análisis (`insights`), sesiones de chat (`sessions`) y el meta-prompt (`config/therapist`). Solo el dueño puede leer y escribir.
- `sample`: el Entrevistador, el Terapeuta y "Analizar patrones" consultan a Claude.
- `downloads`: "Descargar vault" exporta un .zip compatible con Obsidian.

Las notas viven en la base del artefacto, no en este repo. Para respaldarlas, usa "Descargar vault" en Ajustes.

## Áreas

`mente`, `salud`, `familia`, `relaciones`, `trabajo`, `estudio`, `musica`, `finanzas`, `proyectos`, `habitos`, `valores`, `recuerdos`.

## Volver a publicar

`index.html` no funciona abierto directo en el navegador: necesita las capacidades de claude.ai. Para publicar una versión nueva, pídele a Claude que actualice el artefacto con la URL de arriba usando este archivo.

## Seguridad

No diagnostica ni receta. Ante señales de riesgo da la Línea de la Vida (800 911 2000, 24 h) y el 911. No guarda números de identificación, cuentas ni contraseñas.
