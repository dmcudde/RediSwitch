# RediSwitch
NS HEKATE Redimensionador de imagenes Bootlogo Icons and Background
Descripción de la Aplicación
Nombre del Proyecto
Axeon Servicios Informáticos - Conversor de Imágenes BMP para Nintendo Switch

Descripción General
Esta aplicación de escritorio permite a los usuarios convertir imágenes a formatos específicos requeridos por la consola Nintendo Switch, ajustando automáticamente el tamaño, las dimensiones, y la orientación según el tipo de uso: ICONOS, BOOTLOGO, o BACKGROUND sin rotar. Además, incluye una interfaz intuitiva diseñada en Tkinter para facilitar el manejo de archivos de entrada y salida.

Características Principales
Interfaz Gráfica Amigable:

Diseñada con Tkinter para una experiencia simple e intuitiva.
Opciones claras y bien organizadas para cada tipo de conversión.
Tipos de Conversión Soportados:

ICONOS: Ajusta imágenes a 192x192 píxeles con un tamaño final exacto de 147,512 bytes.
BOOTLOGO: Redimensiona imágenes a 720x1280 píxeles y las rota automáticamente si están en orientación horizontal. Tamaño final: 3,686,470 bytes.
BACKGROUND sin rotar: Cambia el tamaño a 1280x720 píxeles sin rotación, con el mismo tamaño final que BOOTLOGO.
Compatibilidad Extensa de Formatos de Entrada:

Soporta imágenes en formato .bmp, .png, .jpg, .jpeg, y .gif.
Manipulación Automática de Tamaño:

Asegura que las imágenes de salida cumplan con el tamaño requerido mediante relleno de bytes.
Logo Personalizado y Marca:

Incluye un logotipo de marca y el nombre del desarrollador en la interfaz.
Soporte para Ejecución como Ejecutable:

Configurado para ser empaquetado como un ejecutable (.exe) utilizando PyInstaller, incluyendo recursos como el logo.
Requisitos Técnicos
Lenguaje: Python 3.9 o superior.
Librerías Necesarias:
Pillow para manipulación de imágenes.
tkinter (incluido por defecto en Python).
os y sys para gestión de archivos y recursos.
Compatibilidad:
Probado en sistemas Windows. Adaptable a otros sistemas operativos con ajustes mínimos.
Cómo Usar
Selección de Archivo de Entrada:

Haz clic en "Abrir archivo" y selecciona la imagen a procesar.
Selección de Carpeta de Salida:

Haz clic en "Guardar en" para elegir la carpeta donde se guardará la imagen convertida.
Elige el Tipo de Conversión:

Selecciona entre ICONOS, BOOTLOGO, o BACKGROUND sin rotar según tus necesidades.
Iniciar la Conversión:

Haz clic en el botón "CONVERTIR". La imagen procesada será guardada en la carpeta seleccionada con el tamaño y formato adecuado.
