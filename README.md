# proyecto-Grp178
Poryecto en conjunto para practicas del grp.
Este proyecto se hace con el fin de practicar lo que hemos visto en modulo 2 de Argentina Programa.
La idea es llevar a la practica conceptos de html y css con el framework de Bootstrap. Ademas del manejo de Github
Todos los del grp estan invitados a participar. 
Para ellos vamos a realizar algo sencillo. Se dejan en una carpeta del mismo repositorio las imagenes que se van a utilizar. 
Para que haya trasnparencia dentro del grp y que no exista confusion se deja claro que es un proyecto sin fines de lucro. EL creador del mismo lo unico que busca es practicar en grp el manejo de github y simular lo que él supone un ambiente laboral.
Reglas a seguir.
1. Se asignaran las tareas para no pisarnos y respetar el trabajo del otro. Para ello debemos crear una nueva rama y trabajar en ella. Luego se hara el correspondiente commit y push.
2. Asegurese que este trabajando en la su rama. Por desconocimiento del autor del proyecto no habra mucha seguridad entre ramas asi que treatemos de no pisar el trabajo del otro.
El proyecto constara de secciones. En principio vamos hacer una cabacera con su menu, un footer y 6 secciones. Asi que seriamos 8 personas. Cada uno se encargara de hacer su parte. Por separado. Esto indica que en su rama solo debe estar hecha la seccion que eligio hacer. Luego se armara todo. 

Dejo una carpeta con el proyecto final a modo de guia. Veran que hay dos archivos pdf.Uno de ellos es el proyecto final y en el otro se separan mediante un recuadro las secciones de la pagina. 

La orden de trabajo seria la siguiente.

Tareas.

1. Barra de Navegacion: Nombre- nombreDeLaPersona.
2. Banner: Nombre- 
3. Procesadora: Nancy Echeverria
4. Batidora: Nombre-
5. Pisa Papas: Nombre-
6. Rallador-Rebanador: Nombre-         (En la foto esta rallador repetido (por error) pero seria "Rallador- Rebanador")
7. Servicio-Garantia: Nombre-
8. Pie de Pagina: Nombre- 

En un principio la participacion es de 8 personas. Cada seccion es muy sencilla. 

Participante:

Deje su nombre al costado de la secion que va a realizar. Ej. Banner: Nombre- Luis

Se debe crear una rama por la seccion que haya elegido hacer. Asegurese de que se encuentre en su rama cuando comience o retome el trabajo.

Dejo los link de bootstrap y google font para facilitar la tarea. Aunque dejare un archivo html con lo basico y los link en el.

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-                EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?    family=Kelly+Slab&family=PT+Serif&family=Poppins:wght@300;400;500&family=Raleway:wght@400;600&family=Roboto+Slab&display=swap" rel="stylesheet">

Reglas a seguir.

Colores a utilizar. #ea1c36.(rojo) ,# ffffff (blanco), #000000 (negro)

Font: Raleway. 
Tamaño de letra:1em

Line-height: 30px (parrafos)

La pagina estara contenida en una caja con la clase "container" de bootstrap.

Tamaño de seccion-grande: width:100% height:100vh;

La seccion mas chica se puede hacer a la mitad de la seccion grande

Como se nota en el pdf el contenedor de seccion esta tiene 2 columnas. la mas ancha para el texto y la otra para la imagen.

Caja imagen:col-md-6 

Caja texto: col-md-6

La paginas deben ser responsivas. Habra que aplicar los breakpoint para las secciones. Como hay mas de una seccion igual a otra dejo los mediaqueries.

           @media screen and (max-width:425px){
           
             .texto{
            height:50vh;
            
          }   
          
          .texto h1{
          margin-bottom: 10px;
           }
          }
          
          @media screen and (max-width:375px){
          
            .texto{
                height:50vh;
            }
            
            .texto h1{
              margin-bottom: 10px;;
            }
          }
          
          @media screen and (max-width:320px){
            .contenedor-imagen{
               margin-top:0px;

           }
            .texto{
                height:50vh;

            }
            .texto h1{
            margin-top: 10px;
            margin-bottom: 10px;;
            }
           }

Para el nav, banner, secciones chica usen los valores que crean relativos a la las medidas que se pasaron.
Aclaraciones: Esto es solo una pagina web de practica. No tiene ninguna rigurosidad o vinculo directo con el modulo y curso. Tampoco hay link de enlaces. Es solo u diseño.

Espero que les guste el desafio. Disculpen el diseño, se hizo lo que se pudo.
Los inconvenientes de diseño que surgan lo solucionaremos en el camino. 
