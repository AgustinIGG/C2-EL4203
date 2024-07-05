Procesamiento de Archivos de Texto con Python

Este repositorio contiene funciones en Python para realizar diversas operaciones de procesamiento de archivos de texto, utilizando conceptos de algoritmos de Programación Dinámica (DP). Estas funciones permiten realizar las siguientes tareas en archivos de texto .txt y .docx:

1. Lectura de Archivos: Leer el contenido de archivos de texto y documentos Word.

2. Operaciones de DP:
    -Longest Common Substring: Encontrar el substring común más largo entre dos partes de un texto.
    -Word Break: Determinar si un texto puede segmentarse en palabras válidas según un diccionario dado.
    -Word Wrap: Ajustar el texto para que cada línea contenga como máximo un número dado de caracteres, justificando las líneas completas excepto la última.

3. CRUD en Archivos: Operaciones básicas de Crear, Leer, Actualizar y Eliminar archivos de texto.

Detalles de Implementación
Lectura y Escritura de Archivos
-read_text(file_path): Lee el contenido de un archivo de texto o documento (txt o doc).
write_file(path_file, content): Escribe contenido en un archivo especificado.
-delete_file(path_file): Elimina un archivo del sistema.
-create_file(path_file): Crea un nuevo archivo vacío en la ruta especificada.
Procesamiento de Texto
-common_substring_search(str1, str2): Encuentra la subcadena común más larga entre dos cadenas.
-word_break(s, word_dict): Determina si una cadena puede segmentarse en palabras válidas usando un diccionario dado.
-word_wrap_dp(text, max_length): Ajusta el texto en líneas con una longitud máxima utilizando programación dinámica.
-format_text(text, max_length): Formatea el texto en líneas justificadas con una longitud máxima especificada.