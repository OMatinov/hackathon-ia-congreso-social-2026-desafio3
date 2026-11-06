# Diccionario de datos · Variante B · `b_leyes.csv`

Cada fila es **un artículo** de una ley publicada, con su texto literal tomado de la Biblioteca del Congreso Nacional (Ley Chile). Los textos legales son públicos. Se omitieron los encabezados y firmas (nombres de parlamentarios y autoridades) para cumplir la regla de no mencionar autores.

| Campo | Significado | Ejemplo |
|---|---|---|
| `id_ley` | Identificador de la ley | L21100 |
| `nombre_ley` | Número y título oficial de la ley | Ley 21.100 · Prohíbe la entrega de bolsas plásticas… |
| `articulo` | Número del artículo (puede ser "5 bis" o "transitorio") | 3 |
| `titulo_articulo` | Título breve del artículo (oficial o descriptivo) | Prohibición |
| `texto` | Texto literal del artículo | Prohíbese a los establecimientos… |
| `historia` | Cómo nació la ley, cuándo se publicó y desde cuándo rige | Ingresó como moción… |
| `url_oficial` | Enlace a la ley en la BCN | https://bcn.cl/2902q |
| `cobertura` | Si se incluyó la ley completa o solo algunos artículos | completa / artículos seleccionados |

**Leyes incluidas:** 21.100 (bolsas plásticas, completa), 20.606 (etiquetado de alimentos, completa), 21.020 (tenencia responsable de mascotas, 10 artículos seleccionados), 21.165 (jornada parcial alternativa para estudiantes trabajadores, completa: intro y letras a-h del art. 40 bis E del Código del Trabajo, arts. 2 a 4 y transitorios; en `articulo` las letras van como `40 bis E a` … `40 bis E h`), 21.091 (Sobre Educación Superior, artículos seleccionados: 1, 11, 13, 15, 16, 54, 55, 103, 104, 105, 106, 108 y 109; se omiten los transitorios y las notas de BCN).

**Para agregar una ley:** copien el texto desde bcn.cl/leychile, una fila por artículo, con un `id_ley` nuevo. No incluyan encabezados ni firmas.
