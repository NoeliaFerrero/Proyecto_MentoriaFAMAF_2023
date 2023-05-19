# ~ Mentoria FAMAF 2023 ~ 

# ***Big Data Bang: explosionando las rutas aéreas para predecir un caos en alto vuelo..!***

<div align="center">

<p align="center">
  <img src="https://github.com/NoeliaFerrero/Proyecto_MentoriaFAMAF_2023/blob/main/listo para el despegue en DS_1.png" width="500" height="300">
</p>
</div>

# Tabla de contenidos 📖
- [Introduccion](#introduccion)
- [Contexto Empresarial](#contexto_empresarial)
  - [Objetivo](#objetivo)
  - [Descripcion](#descripcion)
- [Contexto Analítico](#contexto_analítico)
  - [Diccionario de Datos](#diccionario_de_datos)
  - [Vista previa de los datos](#vista_previa_de_los_datos)
- [FAQs](#faqs)
  - [¿Qué te sumaría participar en este proyecto?](#faq1)
  - [Este proyecto es para vos si...](#faq2)

## Introduccion 

***De la misma manera que el Big Bang (o Gran Explosión en español), intenta interpretar el punto inicial en el que se formó la materia, el espacio y el tiempo, trabajaremos en las distintas etapas en el ciclo de vida del desarrollo de un proyecto de Ciencia de Datos, para generar valor en función de nuestros datos cualitativos (materia y espacio), vs. nuestros datos cuantitativos (tiempo). Aunque estos términos suenen similares, la investigación de datos, cualitativa y la cuantitativa son dos métodos significativamente diferentes. Entender esa diferencia puede tener un gran impacto a la hora de analizar el éxito de una solución/producto basado en datos.*** 

## Contexto_Empresarial 

### Objetivo

Gestión de los recursos Aeroportuarios, analizar y determinar puntos críticos de saturación en el Aeroparque Jorge Newbery.

### Descripcion 

Dada la excelente ubicación geográfica, el Aeropuerto Jorge Newbery es estratégico para la explotación de empresas aéreas tanto nacionales, como internacionales. Luego de la pandemia del Covid 2020 se decretó que el mismo volvería a ser un aeropuerto internacional (destinos del Mercosur y países de Sudamérica). Es por esto, que se han incrementado exponencialmente sus operaciones, pero su infraestructura para soportar este incremento no ha acompañado. Luego de la época de confinamiento, se reconstruyó la única pista que este aeródromo posee, pero esa obra no es suficiente, ya que la terminal de pasajeros ha permanecido prácticamente sin grandes incrementos de su capacidad.
Se realizará el estudio de los datos provistos por el explotador aéreo existente a fin de prever los picos de capacidad de todos los subsistemas que integran al aeropuerto en sí y así evitar saturaciones de los mismos, permitiendo una gestión soportada en datos.  

**[⬆ Volver al inicio](#introduccion)**

## Contexto_Analítico 

Registros de 120000+ vuelos de aerolíneas comerciales entre los años 2019 y septiembre del 2022 inclusive. Cada registro representa un solo vuelo, incluido el nombre de la aerolínea, el número de vuelo y el aeropuerto de origen / destino, así como los horarios de salida y llegada programados / reales.

Tipo de Archivo | Tamaño | Etiquetas | Estructura de Datos | N° Registros | N° Campos | Link |
|---|---|---|---|---|---|---|
| .CSV | 13,5 Mb| Series Temporales, Transporte, Geoespacial | Tabular | 127929 | 28 | [Link](https://raw.githubusercontent.com/NoeliaFerrero/Proyecto_MentoriaFAMAF_2023/main/DataSet%20Aeropuerto%20Jorge%20Newery.csv) |

### Diccionario_de_Datos

Nombre Campo | Breve descripcion | 
|---|---|
| Aero | Aerolínea | 
| Vuelo | Codigo de Vuelo | 
| Cshare | Código compartido (un vuelo puede ser realizado por empresas del mismo holding)| 
| Origen | Ruta del vuelo | 
| Via | Escala del vuelo | 
| STA | Horario programado de arribo | 
| Sug | Horario sugerido | 
| ETA | Estimated Time Arrival| 
| ATA | Actual Time Arrival | 
| Tipo | Codificación del tipo de vuelo | 
| Asignar |  | 
| Pos | Posición asignada al arribo| 
| Ter | Terminal en que opera el arribo | 
| Sec | Sector asociado a la terminal | 
| Rmk | Remark (Estado del vuelo) | 
| Cin | Cinta asignada para retirar equipajes| 
| L&F | Mostrador de reclamos de equipajes asignado al vuelo | 
| Pax | Cantidad de pasajeros | 
| Vip | si tiene o no pasajeros vip ese vuelo | 
| Mat | MAtricula de la aeronave| 
| Acft | Tipo de aeronave | 
| Obs. | Observaciones | 
| Aero | Empresa aerea asociada a la partida | 
| #Rot | Vuelo asociado a la partida| 
| Cabecera | Cabecera de pista donde operó el arribo | 
| año | Año de operación del vuelo | 
| mes | Mes de operación del vuelo | 
| Hora | Hora de operación del vuelo | 

### Vista_previa_de_los_Datos 

|Notebook | Descripción | Link |
|---|---|---|
| 🐍 Proyecto FAMAF Aeroparque Jorge Newbery | Demo de conexión al Set de datos | [Link](https://colab.research.google.com/drive/11ix1h6kQFJaYX3G78KJz68CCpWfgffML?usp=sharing) |
 
**[⬆ Volver al inicio](#introduccion)**

## FAQs

### Faq1 

***¿Qué te sumaría participar en este proyecto?***

El peor mito que me invadía, cuando comencé a conocer este “smart data”, es que la inspiración llega cuando quiere. Y digo esto, porque todos, en mayor ó menor medida, hemos tenido dudas al momento de encontrar esa GRAN idea que guie nuestro primer GRAN proyecto, pero si ponemos atención, podemos encontrar puntos de inspiración muy claros en nuestra vida y las cosas que nos llaman la atención, y entonces empiezan a surgir las preguntas interesantes…claro que, para poder responder esas preguntas, debemos tener algo que es muy necesario: **contexto**. El contexto lo podemos obtener de muchos lugares: de los que hacemos, de lo que queremos hacer, algunos también lo llaman **motivación** ó **propósito**. 

Te invito a explorar esas dimensiones construyendo juntos este proyecto para que puedas: 
-	Mejorar lo que ya haces en tu trabajo
-	Profesionalizar tu conocimiento sobre un tema del que quieras aprender
-	Solidificar los beneficios del trabajo en equipo. Un trabajo bien logrado, donde cada integrante, sea pieza fundamental

### Faq2 

***Este proyecto es para vos si...***

Este recurso ha sido pensado con la intención de brindarte la flexibilidad para encontrar tu propio camino...diseñar un viaje en el que puedas desarrollar e intercambiar habilidades del mundo real...
asique si ya comenzaste esa metamorfosis que te permite pensar como un verdadero Cientifico/a de datos y especialmente si te gusta volar con la imaginación (lease, hacer presentaciones anti-aburridas) podes sumarte a bordo, la hoja de ruta esta casi lista, solo falta agregar la pasión por los datos que cada uno quiera compartir!

**[⬆ Volver al inicio](#introduccion)**

Gracias por tu lectura. Espero que te lleves algo útil de tu paso por acá ;) 

By Noe Ferrero




