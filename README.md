Este proyecto contiene varias utilidades que desarrolle en mi tiempo libre durante los años que trabajé para ISBAN desarrollando procesos de BI en Powercenter.

Puesto que hace años que ya no trabajo para ISBAN y que no uso estas utilidades es posible que las mismas ya no sean útiles e incluso que no funcionen.

Si lo usas y tienes algún problema puedes probar a abrir un _issue_ con el mismo pero no aseguro que lo mire y que te pueda dar una solución.

# valida.html
Este archivo realiza validaciones de QA sobre uno o varios workflows de Powercenter exportados a XML.

**Uso:**
Subcódigo: campo opcional. Para proyectos que tienen subproyectos. Sería el código padre.
Proyecto: Campo obligatorio. Es el código del proyecto contra el que se validará la nomenclatura de los workflows. EJ: JM_7321
XML: Fichero xml con los uno o varios Workflows que se quieran validar. Todos los workflows deben pertener al mismo proyecto. Copiar el XML la misma carpeta que el archivo valida.html para evitar problemas.
