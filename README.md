# CSS-Selectors-con-CSS-Diner
Tarea de Prog. Web

## Selector de tipo: 
 - Descripción: Selecciona elementos por su tipo (etiqueta).
 - Ejemplo: h2 selecciona todos los elementos h2 (enlaces).
 - h1 { color: red; text-align: center;}
  
## Selector de identificación: 
 - Descripción:Selecciona elementos con un ID específico.
 - Ejemplo: #header selecciona el elemento con id="header".
 -  #header { background-color: #f8f9fa; color: #333; padding: 20px; text-align: center;font-family: Arial, sans-serif;}
    
## Selector de descendientes: 
  - Descripción: Selecciona un elemento dentro de otro elemento.
  - Ejemplo: ul li selecciona todos los elementos li que se encuentran dentro de cualquier  ul.
  - ul li { color: green; font-size: 18px; margin-bottom: 10px;}
  
## Combinación de selector de descendiente e ID: 
 - Descripción: Puede combinar cualquier selector con el selector descendiente.
 - Ejemplo: #menu ul selecciona todos los elementos ul que están dentro del elemento con id="menu".
 - #menu ul { background-color: #e0e0e0; border: 1px solid #ccc; padding: 10px; list-style-type: none;}
  
## Selector de clases: 
 - Descripción: Selecciona elementos por su clase.
 - Ejemplo: .destacado selecciona todos los elementos con class="destacado".
 - .destacado {background-color: #ffeb3b; color: #333; padding: 15px; border-radius: 5px; font-weight: bold;}
  
## Selector universal: 
 - Descripción:¡Puedes seleccionarlo todo!
- Ejemplo: * selecciona todos los elementos en el documento.
- * { margin: 0; padding: 0; box-sizing: border-box;}
  
## Selector de hermanos generales: 
  - Descripción: Selecciona elementos que siguen a otro elemento.
  - Ejemplo: h2 ~ p selecciona todos los elementos p que siguen a un elemento h2.
  - h2 ~ p {color: blue;}

## Selector de atributo comodín: 
  - Descripción: Selecciona todos los elementos con un valor de atributo que contiene caracteres específicos en cualquier lugar.
  - Ejemplo: [title*="tutorial"] selecciona todos los elementos con un atributo title que contenga la palabra "tutorial".
  - [title*="tutorial"] { background-color: yellow; color: black; padding: 5px;}

## Selector de atributo que termina con: 
  - Descripción: Selecciona todos los elementos con un valor de atributo que termina con caracteres específicos.
  - Ejemplo: [href$=".pdf"] selecciona todos los elementos con un atributo href que termine en ".pdf".
  - [href$=".pdf"] {color: blue; font-weight: bold;}

## Selector de atributo que empieza con:
  - Descripción: Selecciona todos los elementos con un valor de atributo que empieza con caracteres específicos.
  - Ejemplo: [src^="https://"] selecciona todos los elementos con un atributo src que empiece con "https://".
  - [src^="https://"] { border: 2px solid green; padding: 5px; background-color: #e6ffe6;}

## Selector de valor de atributo: 
  - Descripción: Selecciona todos los elementos que tienen un valor de atributo específico.
  - Ejemplo: [type="email"] selecciona todos los elementos con un atributo type igual a "email".
  - [type="email"] { border: 2px solid #007bff; /* Borde de color azul */  padding: 5px; /* Espaciado interior de 5 píxeles */}
  

  ![Capta](captura1.jpg)
  ![Capta]( Captura2.jpg)
