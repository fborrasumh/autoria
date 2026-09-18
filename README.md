# AutorIA

Coach de reescritura propia para manuscritos académicos, en un único HTML.

**App:** https://fborrasumh.github.io/autoria/

Muestra el manuscrito con un indicador de estilo en el margen de cada párrafo (variación de longitud de frase, expresiones comodín, arranques con conectores de relleno, enumeraciones de tres) para decidir dónde volver a escribir con tus palabras. Al elegir un párrafo, la IA solo formula preguntas sobre lo que quieres decir y, al terminar, comprueba si tu versión pierde o añade contenido; nunca propone frases. Mientras escribes contabiliza por separado lo tecleado y lo pegado, y el tiempo de escritura. Exporta el texto, un registro de autoría y un JSON que [ProcedencIA](https://github.com/fborrasumh/procedencia) importa como punto de control.

- Vanilla JS, persistencia en IndexedDB, clave de OpenAI en el navegador (`ia_openai_key`), gpt-4o-mini por defecto y selector con los modelos de la cuenta.
- Lee PDF, DOCX, TXT, MD y TEX.

**Nota:** no reescribe el texto ni sirve para eludir detectores de IA; el indicador de estilo no predice el resultado de ningún detector. Su propósito es que el texto final sea realmente del autor y que quede constancia de ello. No exime de declarar el uso de IA.

Autor: Fernando Borrás Rocher (UMH) · ORCID [0000-0002-5519-4573](https://orcid.org/0000-0002-5519-4573) · Licencia MIT
