#Definiendo CSS
CSS se puede definir mediante cuatro métodos:
_________________________________________________________________
1. En línea
Para definir un estilo CSS usando el método en línea, use el styleatributo HTML:

<p>This is the default serif font. It is commonly used in 
printed media for better readability, since letters
are more distinct in serif fonts.</p>

<p style="font-family: sans-serif">This is a sans-serif font. 
It is commonly used in screens because it is hard
for screens to render letters with such great detail.</p>

--------------------------------------------------------------------------------------------
2. Usando una etiqueta CSS
No se recomienda en absoluto definir CSS en línea, evítelo tanto como pueda.
 Siempre debes definir una hoja de estilo CSS y usar selectores para aplicar las hojas de estilo.
 El tutorial de Selectores brindará un tutorial detallado sobre cómo seleccionar elementos HTML usando selectores CSS.

--------------------------------------------------------------------------------------------------

3. Usar una hoja de estilo diferente
Puede definir una hoja de estilos CSS en un archivo externo (normalmente con la extensión .css) y cargarla.

A continuación se muestra un ejemplo para definir la misma clase CSS definida en el ejemplo anterior, pero en un archivo llamado "style.css".`
