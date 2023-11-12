# CodeTranslator
translate C# to Java using Flex &amp; Byson

traductor/
|-- src/
|   |-- lexer_1.l       # Archivo de reglas léxicas para el primer lenguaje
|   |-- parser_1.y      # Archivo de reglas gramaticales para el primer lenguaje
|   |-- lexer_2.l       # Archivo de reglas léxicas para el segundo lenguaje
|   |-- parser_2.y      # Archivo de reglas gramaticales para el segundo lenguaje
|   |-- translator.c    # Código principal para la traducción entre los dos lenguajes
|
|-- include/
|   |-- translator.h    # Archivo de encabezado para definiciones y funciones comunes
|
|-- build/              # Carpeta para los archivos generados durante la compilación
|
|-- input/              # Carpeta para almacenar programas de entrada (primer lenguaje)
|   |-- input_program.txt
|
|-- output/             # Carpeta para almacenar programas traducidos (segundo lenguaje)
|   |-- output_program.txt
|
|-- scripts/
|   |-- run_translator.sh   # Script para ejecutar el traductor
|
|-- Makefile            # Archivo de configuración para compilar el traductor
|-- README.md           # Documentación del traductor y cómo usarlo
