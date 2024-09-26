# Introducción a Markdown - Daniel y José Luis
## Actividad de Investigación

### **1. ¿Qué es Markdown y para qué se utiliza?**


Markdown es un *lenguaje de marca* creado en 2004 por **John Gruber y Aaron Swartz**. Su diseño se centró en simplificar la escritura y la lectura de texto formateado, ofreciendo una alternativa más accesible que HTML, porque era más complicado para algunos usuarios. *Gruber y Swartz* querían que fuera sencillo de leer y escribir en su forma original, y fácil de convertir a **HTML**.

*Sus usos Principales:*

* **Documentación Técnica:** Utilizado en plataformas como GitHub para README y documentación de proyectos.
* **Blogs y Web:** Empleado en sistemas de gestión de contenido y plataformas de blogging para crear y publicar artículos.
* **Notas Personales:** Usado en aplicaciones de toma de notas para organizar y formatear textos.

* **Foros y Comunidades:** Permite formatear publicaciones y comentarios en muchas plataformas en línea.
* **Generación de Documentos:** Facilita la creación de informes y otros documentos que se pueden exportar a diversos formatos.
En resumen, 

### **2. ¿Cuáles son las características principales de Markdown que lo hacen diferente de otros lenguajes de marcas de presentación?**

Es lenguaje de marca con un *enfoque diferente* al HTML. Markdown destaca por su ***sintaxis simple y legibilidad***, siendo ideal para crear contenido rápidamente como documentación o blogs. Es **fácil de aprender y editar**, pero **tiene limitaciones en diseño y estilo**, requiriendo conversión a HTML para una visualización completa. En cambio, ***HTML ofrece un control detallado sobre la presentación y el diseño web***, permitiendo la integración con *CSS y JavaScript* para una personalización completa. Sin embargo, HTML puede ser más complejo y menos legible.
### **3. ¿Qué aplicaciones o plataformas utilizan Markdown?**

* **GitHub:** Es ampliamente conocido por su soporte para Markdown en README files, issues, pull requests y comentarios. Es una herramienta esencial para la colaboración en proyectos de desarrollo de software.

![Imagen](https://cdn.prod.website-files.com/5f5a53e153805db840dae2db/64e79ca5aff2fb7295bfddf9_github-que-es.jpg)

* **Slack:** Aunque no tiene un soporte completo de Markdown, permite formatear texto con elementos básicos como negritas, cursivas y enlaces, facilitando la comunicación en equipo.


![Imagen](https://d34u8crftukxnk.cloudfront.net/slackpress/prod/sites/6/slack-logo-slide.png)

* **Reddit:** Utiliza una versión personalizada de Markdown para formatear publicaciones y comentarios, lo que ayuda a los usuarios a crear contenido estructurado en las discusiones.

![Imagen](https://play-lh.googleusercontent.com/1LdWoV0Bn5RdgGGVx27FKrN0U7Gc7rZDGlynUy67fWhtrJvNxa43iz0PYGVbzLCdmJxZ)

* **Discord:** Ofrece soporte para Markdown en mensajes, lo que permite a los usuarios aplicar formato básico a su texto en chats.

![Imagen](https://www.internetmatters.org/wp-content/uploads/2020/07/discord-guide-app-image-1-600x315.png)

* **Jupyter Notebooks:** Soporta Markdown en celdas, permitiendo a los usuarios incluir explicaciones y anotaciones junto con el código, lo cual es útil para la documentación y la enseñanza.


![Imagen](https://lh4.googleusercontent.com/proxy/vy7ZYUBKUDZIxoJChOIJMerZN381mPIWngOS5Bb0LjXZRxaWYRqigm7teUaU08oST3HcSWMRDZ2t7ahcunxtXRxTJKTqA1qb878L4PgAzDSKrbJaRcmbXTkVpqEl-UkArJVloD-vuG2t8QPRJBi8zvhJ16xi)


* **Notion:** Ofrece un sólido soporte para Markdown en sus páginas y notas, permitiendo una edición flexible y estructurada de contenido.

![Imagen](https://miro.medium.com/v2/resize:fit:1400/1*Uz0Ax1Gk9Ju1a0qGSOIMqg.png)


### **4. ¿Cuáles son las etiquetas o símbolos más comunes que se utilizan en Markdown para dar formato a un texto?Proporciona ejemplos prácticos de:**

#### * **Párrafos**: Los parrafos se escriben normal basta con separar los parrafos con una linea en blanco para que markdown lo interprete como parrafos separados. 

#### * **Encabezados (de distintos niveles)**: 
  
    # Encabezado Nivel 1

    ## Encabezado Nivel 2 

    ### Encabezado Nivel 3

    #### Encabezado Nivel 4

    ##### Encabezado Nivel 5

    ###### Encabezado Nivel 6

#### * **Enlaces externos**: [Enlace](https://www3.gobiernodecanarias.org/medusa/edublog/ieselrincon/)

#### * **Imágenes**: ![Imagen](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT904XZ8kpOic417aETQDdVWE2u5LpQ6XJhNQ&s)

#### * **Texto en negrita**: **Este texto está en negrita**
  
#### * **Bloques o líneas de código**:

`Este es un código en línea`

#### * **Listas**:

1. Primero  
2. Segundo
    1. Sub Segundo
3. Tercero

#### * **Una tabla**:

| Prueba       | Prueba       |
|--------------|--------------|
| Prueba       | Prueba       |
| Prueba       | Prueba       |


#### * **Enlace que permita acceder a otro documento**:

[-Documento de Prueba-](OtroDocumento.md)


### **5. ¿Cómo se puede visualizar y convertir un archivo escrito en Markdown a otros formatos, como HTML o PDF? Busca herramientas o aplicaciones que permitan convertir Markdown a otros formatos, y explica cómo funcionan.**

* **Visual Studio Code (VS Code)**

    * Visualización: Puedes usar extensiones como "Markdown Preview Enhanced" para ver una vista previa en tiempo real de tus archivos Markdown.
    * Conversión:
        * HTML: Abre el archivo Markdown y usa el comando de vista previa para generar una vista previa en HTML. Puedes copiar el HTML desde la vista previa.
        * PDF: Usa extensiones como "Markdown PDF" para convertir el archivo Markdown a PDF directamente desde VS Code.

* **Pandoc**

    * Descripción: Pandoc es una herramienta de línea de comandos muy versátil que convierte archivos entre diferentes formatos, incluidos Markdown, HTML, PDF, y muchos más.
    * Cómo funciona:
        * Instalación: Puedes instalar Pandoc desde su sitio web.
        * Conversión: Usa comandos en la terminal. Por ejemplo, para convertir un archivo Markdown a HTML:
sh
Copiar código
pandoc archivo.md -o archivo.html
        * Para convertir a PDF (requiere LaTeX):
sh
Copiar código
pandoc archivo.md -o archivo.pdf

* **Typora**

    * Visualización: Typora es un editor de Markdown que proporciona una vista previa en tiempo real del documento.
    * Conversión:
        * HTML: Puedes exportar a HTML usando Archivo > Exportar > HTML.
        * PDF: Puedes exportar a PDF usando Archivo > Exportar > PDF.

* **Mark Text**

    * Visualización: Mark Text es un editor Markdown que ofrece vista previa en tiempo real.
    * Conversión:
        * HTML: Puedes exportar el archivo a HTML usando Archivo > Exportar > HTML.
        * PDF: Puedes exportar a PDF usando Archivo > Exportar > PDF.


* **Dillinger**


    * Descripción: Dillinger es un editor Markdown basado en web que ofrece capacidades de exportación.
    * Conversión:
        * HTML: Abre tu archivo Markdown en Dillinger y usa la opción de exportación a HTML.
        * PDF: Puedes exportar a PDF utilizando la opción correspondiente en el menú de exportación.


* **MarkdownPad**


    * Visualización: MarkdownPad es un editor para Windows que ofrece vista previa en tiempo real.
    * Conversión:
        * HTML: Usa la opción Guardar como HTML para exportar el documento.
        * PDF: Puedes usar una impresora PDF virtual para imprimir el archivo Markdown como PDF.


* **HackMD/Codimd**


    * Descripción: HackMD (ahora CodiMD) es una herramienta colaborativa en línea para editar Markdown.
    * Conversión:
        * HTML: Puedes exportar el archivo como HTML desde las opciones de exportación.
        * PDF: También puedes exportar a PDF desde las opciones de exportación.

* **Jupyter Notebook**
    * Conversión:
        * HTML: Puedes exportar notebooks a HTML desde el menú Archivo > Descargar como > HTML.
        * PDF: También puedes exportar a PDF usando Archivo > Descargar como > PDF (requiere una instalación adicional de LaTeX).

### 6. ¿Qué ventajas tiene escribir documentación o notas en Markdown frente a usar procesadores de texto como Microsoft Word o Google Docs? Analiza las diferencias y las ventajas que puede tener escribir en un lenguaje de marcas sencillo como Markdown en lugar de usar un procesador de texto tradicional.

Markdown es una herramienta buena para la creación de documentos que necesitan simplicidad, portabilidad y compatibilidad. En cambio, para trabajos donde el formato y la presentación visual son importantes, Word o Google Docs ofrecen más opciones.

* **Ventajas**

    * **Simplicidad**: Es un lenguaje de marcado fácil de aprender y usar

    * **Portabilidad**: Los archivos .md son ligeros, universales y compatibles con múltiples plataformas y editores.

    * **Fácil conversión a otros formatos**: Markdown se puede convertir fácilmente a otros formatos como HTML, PDF o Word sin perder la estructura del contenido, lo que facilita compartir y distribuir el documento en diferentes medios.

* **Desventajas**

    * **Capacidades de formato limitadas**: Markdown tiene opciones básicas de formato, lo que puede no ser suficiente para documentos complejos con gráficos avanzados, tablas detalladas o diseños personalizados.

    * **Curva de aprendizaje**: Aunque es sencillo, aprender las sintaxis puede ser un obstáculo para quienes no están familiarizados con los lenguajes de marca.

    * **Falta de herramientas avanzadas de edición**: A diferencia de Word o Google Docs, no ofrece funciones como corrección ortográfica avanzada, plantillas predefinidas, o revisión de cambios, lo que puede hacer falta en proyectos más formales.


### **7. ¿Existen diferentes "sabores" o variaciones de Markdown? Investiga si hay diferentes versiones o extensiones de Markdown, como GitHub Flavored Markdown (GFM). ¿En qué se diferencian de la versión estándar.**

#### Markdown tiene varios "sabores" que amplían sus funciones básicas:

**Markdown Estándar:** Básico, con encabezados, listas, enlaces, imágenes y bloques de código.

**GitHub Flavored Markdown (GFM):** Añade tablas, listas de tareas, enlaces automáticos, resaltado de sintaxis y tachado.

**Markdown Extra:** Incluye tablas, listas de definición, notas al pie y bloques de código avanzados.

**CommonMark:** Markdown con reglas claras.

**MultiMarkdown:** Ofrece tablas avanzadas, referencias cruzadas, metadatos y exportación a varios formatos.
Pandoc Markdown: Permite conversiones a múltiples formatos y añade citas y bibliografía.

**RMarkdown:** Combina texto y código ejecutable, como para análisis de datos.
Cada versión *añade características que no están en el Markdown original*, como tablas y notas al pie.


### **8. ¿Cómo puede ser útil Markdown en el trabajo colaborativo en proyectos de software? Investiga  cómo Markdown es utilizado en entornos de colaboración, como en la documentación de proyectos de software en GitHub o la creación de archivos README.**

Markdown es una herramienta muy útil en el trabajo colaborativo en proyectos de software, especialmente en plataformas como GitHub. 

**Documentación:** Clara y Concisa: Markdown permite crear documentación legible y estructurada.

**Archivos README:** El archivo README.md es esencial en los repositorios de GitHub. Proporciona una introducción al proyecto, instrucciones de instalación, ejemplos de uso y otros detalles importantes.

**Control de Versiones:** Markdown se almacena como texto plano, lo que permite un fácil seguimiento de cambios en sistemas de control de versiones como Git. 

**Integración con Herramientas:** Muchas plataformas y herramientas de desarrollo (como Jupyter Notebooks, foros, y sistemas de gestión de proyectos) admiten Markdown, lo que facilita su uso en diferentes contextos dentro de un mismo proyecto.

**Facilidad de Uso:** La curva de aprendizaje de Markdown es baja, lo que permite que los miembros del equipo, independientemente de su nivel técnico, puedan contribuir a la documentación sin necesidad de conocimientos avanzados de programación o diseño.

En resumen, Markdown es una herramienta fundamental en entornos colaborativos de software que mejora la comunicación, la organización de la información y la eficiencia en la gestión de proyectos.
