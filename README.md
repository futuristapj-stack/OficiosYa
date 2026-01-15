<! DOCTYPE html>
<HTML Lang.="Es">
<cabeza>
  <meta  charset="UTF-8" />
  <meta  nombre="viewport" contenido="ancho = ancho de dispositivo, escala inicial = 1.0"/>
  <título>OficiosYa</título>
  <estilo>
   cuerpo  { 
 Margen: 0; 
       Font-Family: Arial, Helvetica, Sans-serif; 
 fondo: #ffff; 
 color: #222; 
 } 

    encabezado {
     text-align: centro; 
     relleno: 40px 20px 20px; 
    }

    encabezado h1 {
     Margen: 0; 
     Tamaño de fuente: 48px; 
     peso de fuente: 900; 
     color: #d60000; 
     Espaciado de letras: 1px; 
    }

    encabezado p {
     Margen-top: 10px; 
     Tamaño de fuente: 18px; 
    }

    .buscador {
     ancho máximo: 400px; 
     Margen: 40px auto; 
     relleno: 20px; 
     frontera: 1px sólido #eee; 
     Border-Radius: 8px; 
    }

    .buscador label {
     visualización: bloque; 
     margen-abajo: 5px; 
     peso de fuente: negrita; 
    }

    .buscador select {
     Anchura: 100%; 
     relleno: 10px; 
     margen-abajo: 20px; 
     Tamaño de fuente: 16px; 
    }

    .buscador button {
     Anchura: 100%; 
     relleno: 12px; 
     Tamaño de fuente: 18px; 
     peso de fuente: negrita; 
     antecedentes: #d60000; 
     color: #fff; 
     Frontera: Ninguna; 
     Border-Radius: 5px; 
     cursor: puntero; 
    }

    Botón .buscador:hover {
     antecedentes: #b80000; 
    }

    pie de página {
     text-align: centro; 
     relleno: 20px; 
     Tamaño de fuente: 14px; 
     color: #777; 
    }
  </estilo>
</cabeza>
<cuerpo>

  <cabeza>
    <H1>OficiosYa</H1>
    <P.>El oficio que buscas a solo un click</P.>
  </cabeza>

   <sección class="buscador"> 
    <etiqueta para="Rubro">Rubro</etiqueta>
    <seleccionar ID="Rubro">
 <opción>Sanitario</opción> 
       <opción>Electricista</opción> 
 <opción>Albañil</opción> 
    </seleccionar>

    <etiqueta para="zona">Zona</etiqueta>
    <seleccionar ID="zona">
       <option>Montevideo</option> 
     <opción>Canelones</opción> 
       <option>Maldonado</option> 
       <option>Interior del país</option> 
    </seleccionar>

    <botón>BUSCAR</botón>
   </sección> 

   <pie de página> 
     © OficiosYa 
   </pie de página> 

</cuerpo>
</HTML
