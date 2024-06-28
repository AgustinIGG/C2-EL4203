Procesamiento de Archivos de Texto con Python

Este repositorio contiene funciones en Python para realizar diversas operaciones de procesamiento de archivos de texto, utilizando conceptos de algoritmos de Programación Dinámica (DP). Estas funciones permiten realizar las siguientes tareas en archivos de texto .txt y .docx:

1. Lectura de Archivos: Leer el contenido de archivos de texto y documentos Word.

2. Operaciones de DP:
    -Longest Common Substring: Encontrar el substring común más largo entre dos      partes de un texto.
    -Word Break: Determinar si un texto puede segmentarse en palabras válidas según un diccionario dado.
    -Word Wrap: Formatear el texto para que cada línea contenga como máximo un número dado de caracteres, justificando las líneas completas excepto la última.

3. CRUD en Archivos: Operaciones básicas de Crear, Leer, Actualizar y Eliminar archivos de texto.

Detalles de Implementación
  -get_file_extension(ruta_archivo): Función para obtener la extensión de un archivo a partir de su ruta.
  -create_file(ruta_archivo, contenido): Función para crear un nuevo archivo en la ruta especificada y escribe el contenido proporcionado.
  -read_file(ruta_archivo): Función para leer el contenido de un archivo de texto o documento Word.
  -update_file(ruta_archivo, nuevo_contenido): Función para actualizar el contenido de un archivo existente en la ruta especificada.
  -delete_file(ruta_archivo): Función que elimina un archivo especificado por la ruta del archivo.
  -longest_common_substring(X, Y): Función para encontrar el substring común más largo entre dos cadenas.
  -word_break(s, word_dict): Función para determinar si un texto puede segmentarse en palabras válidas según un diccionario.
  -word_wrap(words, maxWidth): Función para formatear el texto para que se ajuste a líneas de longitud máxima especificada, justificando las líneas completas.
  -format_text(text, maxWidth): Función que utiliza word_wrap para formatear el texto completo.