#Printf - Implementación Personalizada de printf

Descripción:

Ft_printf es un proyecto en C que consiste en la creación de una librería personalizada llamada ftprintf.a, 
que replica la funcionalidad de la función printf() original de la libc.
El objetivo es implementar una versión simplificada de printf(),
soportando las conversiones %c, %s, %p, %d, %i, %u, %x, %X, y %% para imprimir diferentes tipos de datos.
No se gestiona el buffer de printf(), y la librería se compila en un archivo estático utilizando el comando ar.

📂 Estructura

ft_printf/
├── ftprintf.a        # Librería estática
├── ft_printf.c          # Implementación de ft_printf
├── ft_printf_utils.c    # Funciones auxiliares de ft_printf
├── Makefile             # Compilación
└── README.md            # Documentación
🛠️ Instalación
Compilar:
make
Limpiar archivos:
sh
Copiar
Editar
make clean
make fclean
🎯 Reglas
Implementación de la función ft_printf que imite el comportamiento de printf().
Soporte para las conversiones %c, %s, %p, %d, %i, %u, %x, %X y %%.
El archivo libftprintf.a debe ser creado con el comando ar.
El proyecto debe cumplir con las normas de la escuela, sin errores de memoria ni comportamientos indefinidos.
