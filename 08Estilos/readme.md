# CSS: Selectores # <!-- es la sustitución de class -->

- de etiqueta (tag selector)
- de id (id selector) de lo más especifico se le aplica una clase
- de clase (class selector) class=verde pues esos elementos que tenga verde serán verde

<!-- los pseudoelementos llevan :: -->
- agrupados (,)
- combinados 
    - selector de descendientes [descent selector] ( ) muy amplio da igual al distancia meintras esten dentro
    - selector de hijos [Child selector] (>)
    - selector de hermanos [next siblings selector] (~) siempre por delante de, nunca selectores por detrás 
    - selector de hermano adyacente [adjenct sibling selector] (+)
   <!--  los dos últimos selectores (~) y (+) no se suelen usar mucho pero los de ( ) y (>) se usan bastante -->
- selector de atributo ([])
- pseudoclases -> :hover... en vez de poner class son sus "circunstancias" las que pones para ser una clase
- pseudoelementos -> ::first-letter, ::first-line
- pseudoelementos con contenido -> ::after, ::before 
- pseudoclases posicionales -> :nth-of-type(), :nth-child() <!-- siempre tienen valor [número] para especificar cual seleccionamos -->