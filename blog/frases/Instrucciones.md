<!--
╔══════════════════════════════════════════════════════════════════╗
║  PLANTILLA — Cómo agregar una frase nueva                        ║
║                                                                  ║
║  Las frases NO tienen páginas individuales. Todas viven en       ║
║  frases.json. Este archivo es solo una guía de referencia.       ║
║                                                                  ║
║  PASOS PARA AGREGAR UNA FRASE NUEVA:                             ║
║                                                                  ║
║  1. Abre blog/frases/frases.json                                 ║
║  2. Agrega una entrada nueva al inicio del array (o al final)    ║
║  3. Guarda el archivo                                            ║
║  4. La frase aparecerá automáticamente en el índice              ║
║                                                                  ║
║  ESTRUCTURA DE UNA ENTRADA:                                      ║
║                                                                  ║
║  {                                                               ║
║    "slug":      "palabras-del-titulo-con-guiones",               ║
║    "texto":     "El texto completo de la frase.",                ║
║    "autor":     "Nombre del autor (deja vacío "" si es tuya)",   ║
║    "fecha":     "2025-01-15",    ← formato YYYY-MM-DD            ║
║    "destacado": false            ← true para aparecer primero   ║
║  }                                                               ║
║                                                                  ║
║  EJEMPLOS:                                                       ║
║                                                                  ║
║  Frase de otro autor:                                            ║
║  {                                                               ║
║    "slug":      "einstein-imaginacion",                          ║
║    "texto":     "La imaginación es más importante que el         ║
║                  conocimiento.",                                 ║
║    "autor":     "Albert Einstein",                               ║
║    "fecha":     "2025-01-20",                                    ║
║    "destacado": false                                            ║
║  }                                                               ║
║                                                                  ║
║  Frase propia:                                                   ║
║  {                                                               ║
║    "slug":      "sobre-los-errores",                             ║
║    "texto":     "Un error que entiendes vale más que un          ║
║                  resultado correcto que no puedes explicar.",    ║
║    "autor":     "",                                              ║
║    "fecha":     "2025-01-18",                                    ║
║    "destacado": true                                             ║
║  }                                                               ║
║                                                                  ║
║  NOTAS:                                                          ║
║  - El slug es solo un identificador único. Usa palabras          ║
║    del texto separadas por guiones, sin acentos.                 ║
║  - Si "autor" está vacío (""), no aparece ningún crédito.        ║
║  - Las frases con "destacado": true aparecen primero.            ║
║  - El orden dentro de cada grupo (destacadas / no destacadas)    ║
║    es el mismo que en el JSON — pon las más nuevas arriba.       ║
╚══════════════════════════════════════════════════════════════════╝
-->
