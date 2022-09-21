<!--
Le Etiqueta (tag)  <> - es un elemento del lenguaje de marcado de hipertexto.
Estos son los bloques básicos mas pequeños de los que se compone cualquier pagina web.
Cada etiqueta representa una entidad: título, lista, párrafo de texto, imagen.
Para resaltar las etiquetas entre el texto del documento, se utilizan corchetes angulares 
 que especifican el nombre de la etiqueta y sus atributos.
       
 <nombre_de etiqueta>
  Va toda la información que queremos englobar dentro de la etiqueta 
</nombre de_ etiqueta> (etiqueta de cierre)
-->

ETIQUETAS
    se encuentran denro de <> 
    <nombre_de etiqueta> Se pone toda la informacion qeu podemos englobar dentro de la etiqueta</nombre_de etiqueta>
    
        EJEMPLO
    <a> "a" se usa para los links</a>
    <P> "p" Parrafo </P>
    <button> "b" botones </button>
    <section> "section" Secciones </section>
    <div> "div" secciones </div>

ATRIBUTOS
          
 Atributos de a pueden ser:
   
 * "href" atributo de referencia, para enviar al sitio que queramos, link de destino
   "class" - referencia al css

   <a href="https://developer.mozilla.org/es/docs/Web/HTML" id="1" class="Link a Developer Mozilla"> Documentacion de HTML</a>
    
   <a href="https://www.linkedin.com/in/nathaly-nar-paes-b6a483111/" id="1" class="web">
    Nathaly J Nar
    </a>
    -Atributo Atributo Target  <a href="https://www.linkedin.com/in/nathaly-nar-paes-b6a483111/" id="1" class="web" target="_blank"> Nathaly</a>

ETIQUETA UNICA: No  necesita etiqueta de cierre, son pocas, las identificamos por que no tienen texto
        es un atributo que esta ahí y lo que va a hacer es una referencia.

        ejemplo 
        * etiqueta "IMG" imagen, 
        - Atributo "src" source, trae algo, es de peicion, trabaja de 2 formas
         "img src= "pego el link"" ó "omg src="la carpeta""
        - atributo ALT Las imagenes pueden tener atributos "alt" da contexto de que es lo que contiene esa imagen, ayuda a personas con problemas visuales por que le dice que contiene laimagen
        

    link de imagen desde servidor <img src="https://previews.123rf.com/images/photodeti/photodeti2004/photodeti200400193/144696106-tres-cachorros-de-bichon-frise-mirando-a-la-cámara-sobre-un-fondo-del-árbol-de-navidad-.jpg" alt="Three bichon frise pupies looking at camera on a background of the christmas tree. - 144696106" title="Three bichon frise pupies looking at camera on a background of the christmas tree. - 144696106" class="ImageDisplayer__image" style="width: 144px; height: 105px; max-width: 144px; max-height: 105px; display: block;">
       
    link de imagen desde carpeta <img src="image/perritu.jpg" alt="perritu" />

        * Etiqueta INPUT sirve para crear controles de interaccion con el usuario
        Atributo TYPE con este puedo ingresar text=texto, date=fecha... 
        Atributo NAME similar al id, para poder identificar la informacion
        Atrubuto de texto <input type="texto" name="user_name" />
        Atributo de fecha <input type="date" name="Fecha"/>
        Atributo de file <input type="file" name="archivo" />
        Atributo de password <input type="password" name="contraseña" />
        
JERARQUIA nos da estructura visual, vemos que se abren como escaleras y se van cerrando, así podems identificar que etiquetas se encuentran anidadas
        cuales estan dentro de otras para poder hacer boques de cdigo con estructura predeterminada
<etiqueta1> (etiqueta mayor abre)
    <etiqueta2>
        <etiqueta4>...</etiqueta4>
    <etiqueta5>...</etiqueta5>
    </etiqueta2>
    <etiqueta3>
        <etiqueta6>...</etiqueta6>
    </etiqueta3>
</etiqueta1> (etiqueta mayor cierra)

ejemplo:
<section id="2"> ctrl d para seleccionar y cambiar el nombre de varias etiquetas
    nivel 1
    <section id="3">
        nivel 2
        <section id="5">
            nivel 3
        </section>
    </section>
    <section id="4">
        nivel 2
    </section>
</section>