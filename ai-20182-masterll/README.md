# Inteligencia Artificial I 2018-2

_Regístrate [aquí](https://goo.gl/forms/VJRlUKah7DlMBLlf2)_. 
                                            
La máquina virtual puede descargarse [aquí](https://drive.google.com/file/d/1KxCUZlXDgyvJzfs6s7EfegMVS1HL_bXq/view?usp=sharing)


## Máquina Virtual

Usaremos esta máquina virtual que tiene instalado un entorno Python Anaconda con Jupyter Notebooks disponibles en  [localhost:8008/tree](http://localhost:8008/tree) una vez que la máquina arranca.

**Observa la configuración de la máquina**

- Si tu máquina física tiene al menos 4GB de memoria configura la máquina virtual **con 2GB de memoria**
- Aunque casi no necesitarás un terminal, el interfaz de Jupyter Notebooks tiene un terminal para acceder a través del navegador. En cualquier caso, la máquina virtual tiene un servidor SSH en el puerto 2222 con user/user como usuario y pwd. Si tu máquina física es mac o linux usa `ssh -p 2222 user@localhost` para conectarte. Si es windows, usa [putty](https://www.putty.org/)
- Si compartes una carpeta entre la física y virtual asegúrate que **el nombre cone el que se comparte** sea `share` (aunque el nombre de la carpeta en la máquina física puede ser distinto)

**Para montar la carpeta compartida** ejecuta lo siguiente en un terminal y la carpeta aparecerá en /home/user/share:

    sudo mount share


## Calificación
40% Talleres (Problemsets)<br/>
30% Parciales (Quizes) <br/>
30 % + [10% ,20 %, 30 %] Proyecto funcional IA <br/>
+10% Online courses (MOOC)

## Talleres (Problemsets)

Los talleres pretender ser una herramienta practica para afianzar los conocimientos desarrollados durante las clases. En general se presentan como un conjunto de ejercicios que serán desarrollados **individualmente** por los estudiantes. Cada taller esta escrito como un notebook para la validación automática. Se pueden hacer tantos intentos como se quieran y unicamente la última respuesta será tomada en cuenta. Cada uno de los talleres ser desarrollará en casa, dentro de las fechas establecidas en el cronograma. 


## Parciales (Quizes)

Son evaluaciones **individuales** basadas en notebooks sobre los temas tratados en las clases. Los estudiantes deben solucionarlo en el salón de clase, en un tiempo determinado. Los apuntes y notebooks del curso se pueden utilizar. 


## Proyecto funcional IA

- **Funcionamiento del proyecto**. El proyecto se debe realizar como un notebook.  

- **Prototipo [+10% - +20%]**:  En este item se considera como esta estructurado el proyecto. Los porcentajes extras tienen en cuenta importancia o relevancia de 
del proyecto y también la solución a problemas  reales.

- **Presentación (video y diapositivas) [+ 10%]**:  Se debe enviar un video corto (max 5 minutos) y un documento de máximo 5 páginas en donde se exponga: 

1. La motivación para el desarrollo del proyecto

2. El tema principal de inteligencia artificial abordado

3.  funcionamiento y simulación del proyecto


- **Preguntas**: Se realizarán preguntas cortas a los estudiantes unicamente relacionadas con el proyecto. 
 
Todos los items tienen el mismo porcentaje de evaluación. 


## Online Courses (MOOC) [Extra]

El avance vertiginoso de la tecnología nos obliga a adquirir destresas en el aprendizaje autónomo. Sobre todo en lo relacionado con tecnologias de la información, existen numerosos recursos virtuales que nos permiten estar actualizados con nuevos temas, estrategias y desarrollos. Teniendo en cuenta esta motivación, como parte complementaria del curo se tendrá en cuenta un porcentaje extra para los estudiantes que deseen realizar un MOOC online. El MOOC habrá de tratar un topico relacionado con la tecnología y ha de cubrir aproximadamente 15 horas de esfuerzo, que se evaluarán según la definición y dinámica de cada caso. Puedes hacerlo en cualquier plataforma existente, como por ejemplo: [Coursera](www.coursera.org), [EDX](www.edx.org), [Udacity](www.udacity.org),  [MiriadaX](https://miriadax.net/), etc.

Tendras que hacer un informe de tu seguimiento del MOOC. La entrega ha de constar de:

- Un archivo PDF llamado MOOC_descripcion.pdf donde se describa el MOOC (primera entrega)
- Un archivo PDF llamado MOOC_completado.pdf donde se incluya la evidencia de la realizacin del MOOC
- Un directorio llamado MOOC_materiales donde se incluyan los materiales pertinentes (scripts, datos, etc.) que apoyen la evidencia mostrada en el archivo PDF.

**TODA ENTREGA QUE NO CUMPLA CON ESTAS CONVENCIONES SERÁ CONSIDERADA COMO NO REALIZADA**

La calificación del curso vendrá dada por los siguientes criterios con el mismo peso cada uno:

- COMPLEJIDAD DEL MOOC
- CALIDAD DEL REPORTE 
- CLARIDAD DEL REPORTE

## Calendario y plazos

                       SESSION 1            SESSION 2           STUDENT DEADLINES

     W32 Aug07-Aug08    --------            0. Intro
     W33 Aug14-Aug15    1.PYTHON            2.PANDAS
     W34 Aug21-Aug22    3.STATS             3.STATS-PSETS         
     W35 Aug28-Aug29    4.BAYES             4.BAYES-PSETS         
     W35 Sep04-Sep05    QUIZPREP            QUIZ                Sep 6 PSETS 1, 2     
     W37 Sep11-Sep12    5.ML INTRO          6.ML METHODS        Sep 14 Registro primera calificación
     W38 Sep18-Sep19    7.NAIVE             7.NAIVE-PSETS     

       ...              ...                 ...
    

     W05 Jan29-Jan30    COMEBACK            COMEBACK             
     W06 Feb05-Feb06    8.IMGINTRO          9.IMGCLASS          Jornada de reflexión (Feb05)
     W07 Feb12-Feb13    QUIZPREP            QUIZ                Feb 16 PSETS 3, 4, 5            
     W08 Feb19-Feb20    PROJECT             PROJECT (DL)        Jornada de reflexión (Feb20)     
     W09 Feb26-Feb27    11.KMEANS		    11.KMEANS           
     W10 Mar05-Mar06    12.PLAN             12.PLAN-SETS	
     W11 Mar12-Mar13    13.GA               13.GA-PSETS        
     W12 Mar19-Mar20    14.SA               14.SA-PSET	        Mar10 PSETS 6 7 8 Jornada de reflexión (Mar19)
     W13 Mar26-Mar27    QUIZPREP            QUIZ		
     W14 Apr02-Apr03    PROJECT             PROJECT             Entrega y sustentación de proyectos Jornada de reflexión (Apr03)
     W15      -         15. Deep L           15.Deep L           ** Optional and free


     


    Sep14 -        -> Registro primera calificación
    Sep16 -        -> Último día cancelación materias

    Mar30 -        -> Finalización clase
    Apr01 - Apr06  -> Evaluaciones finales
    Apr07 -        -> Registro calificaciones finales



**CUALQUIER ENTREGA FUERA DE PLAZO SERÁ PENALIZADA CON UN 50%**
**LOS PROBLEMSETS ESTAN SUJETOS A CAMBIOS QUE SERÁN DEBIDAMENTE INFORMADOS%**
    
[Calendario academico](https://www.uis.edu.co/webUIS/es/rss/imagenes/noticia_1153_10288_2.pdf)

