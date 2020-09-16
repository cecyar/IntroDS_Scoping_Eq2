# Data Science Project Scoping Worksheet

## Integrantes Equipo 2

|              Nombre            |  Clave  |
| :----------------------------: | :-----: |
| Avilés Robles Cecilia          | 197817  |
| Bazo Pérez Edgar               |  |
| Fuentes Ortiz Octavio          |  |
| Gamboa Puente Karina Lizette   |  |
| Moreno Ortiz Eduardo           |  | 
| Salgado Velázquez Iván Oswaldo |  | 
| Torres Ramírez Ana Eréndira    |  | 

---

## 1. Project Name 

*High School Graduation*

## 2. Organization Name

Departamento de Educación de los Estados Unidos

## 3. Problem Description

### 3.0 Supuestos

El programa está enfocado a estudiantes de último año de los cuales se tiene información de su trayectoria previa.
Los datos contienen información de las escuelas, sus ex alumnos graduados y no graduados, alumnos actuales, su trayectoria académica así como información sociodemográfica y socioeconómica.

### 3.1 What is the problem you are facing?

Las escuelas tienen como desafío ayudar a sus estudiantes a graduarse a tiempo. Actualmente, la tasa de graduación que se tiene registrada es de aproximadamente el 65%. Es de interés, identificar a los estudiantes que corren el riesgo de no graduarse a tiempo.

### 3.2 Who/what is affected by this problem? (people of certain type, organizations, neighborhoods, environment)

Estudiantes de preparatoria.
Escuelas preparatoria de los distintos distritos escolares.

### 3.3 How many people/organizations/places/etc and how much are they affected? (e.g. mean wait time for surgery, number of students dropping out of school, cost due to tax fraud, etc.)

Los alumnos y alumnas son el sector más afectado, pues son ellos quienes culminan con los estudios del nivel sobre el cual se está realizando el estudio (high school). Según un estudio realizado en 2018, hay 15.3 millones de estudiantes que se encuentran cursando el nivel educativo high-school. Sin embargo, no se debe menospreciar los recursos que son invertidos en ellos para que puedan lograr este objetivo, los cuales son principalmente profesores y aulas, los cuales son aproximadamente 1.05 millones y 24 mil, respectivamente.

### 3.4 Why is solving this problem a priority for your organization?

Consideramos que la educación es uno de los factores más importantes y de influencia en el progreso y avance de las personas y sociedades. Esto conlleva a las escuelas no sólo a impartir educación sino a impulsar a los estudiantes a concluir con sus estudios en tiempo y forma. 
Al aumentar la tasa de graduados en los distintos distritos se busca reducir la deserción escolar y brechas sociales, aumentar el presupuesto que se tiene destinado a educación y generar un mayor bienestar social.

## 4. Goals

|  | Goal | Constraints |
|-|-|-|
| 1 | Aumentar la tasa de graduación en tiempo de los estudiantes de preparatoria. | Se asume que se tiene una población de estudio grande y se tiene que:<br/><br/> - Decidir si se quiere atacar a todas las escuelas (nacionalmente) o si se seleccionarán zonas particulares.<br/><br/>  - Verificar si existen zonas donde la tasa sea menor al 65%.<br/><br/> - Definir el presupuesto y el capital humano con el que contamos, para así conocer si  la población de estudiantes que podemos tratar es grande o tenemos que ser más específicos con la ayuda de acuerdo a las necesidades. |

## 5. Actions

|  | **Action 1** | **Action 2** | **Action 3** |
|-|:-:|:-:|:-:|
| **Action** | Mentoría | Seminario | Becas y materiales de apoyo |
| **Who is executing the action?** | Personal académico, estudiantes, personal externo y voluntario | Personal académico de la institución | Distrito escolar, ex-alumnos, padres de familia, gobierno local y federal |
| **Who/what is the action being taken on?** | Grupos de estudiantes con más alto riesgo (con necesidad de atención más personalizada) | Grupos de estudiantes con mediano riesgo | Estudiantes de grupos vulnerables |
| **How often is the decision to this action made?** | Semanalmente con apertura a más días por necesidad del alumno(a) | Semanalmente con apertura a quincenal dependiendo de la complejidad del curso | Las becas y apoyos materiales se otorgarán al inicio de mes y semestre respectivamente |
| **What channels are/can be used to take this action?** | Presencial u *online* | Presencial u *online* | Becas: presencial o digital (e.g. depósitos)<br/><br/> Materiales de apoyo: presencial |
| **Other useful information about the action** | La estrategia es llevar al alumno a un segmento de menor riesgo para reducir el costo.<br/><br/> Exclusivo para alumnos de último año. |  |  |

## 6. Data

### 6.A What data sources do you have internally?

|  | **Data Source 1** |
|-|-|
| **Name** | Base de datos del Departamento de Educación de Estados Unidos |
| **What does it contain?** | Información sociodemográfica, socioeconómica y académica de los alumnos y ex-alumnos  |
| **What level of granularity?** | Por materia, alumno, escuela y estado |
| **How frequently is it collected/updated after it’s captured?** | Por periodo de evaluación |
| **Does it have reliable and unique identifiers that can be linked to other data sources?** | - Matrícula del estudiante para bases internas <br/> - Código Postal de las escuelas |
| **Who’s the internal owner of the data?** | Departamento de Educación de Estados Unidos |
| **How is it stored?** | Bases de datos |
| **Additional comments** |  |

### 6.B What data can you get from external, private or public sources?  

|  | Data Source 1 | Data Source 2 |
|-|-|-|
| **Name** | *National Center for Education Statistics* | Base de delincuencia nacional |
| **What does it contain?** | Porcentaje de abandono de la preparatoria entre los alumnos de 16 a 24 años por raza / etnia y estado de los años 2013 al 2017 | Información relevante a la incidencia de actos delictivos |
| **What level of granularity?** | Por estado | Por estados, por distrito y por vecindario |
| **How frequently is it collected/updated after it’s captured?** | - Cada 5 años <br/> - Encuesta intercensal | Anualmente |
| **Does it have reliable and unique identifiers that can be linked to other data sources?** | Clave de estado | Clave de estado, de distrito y de vecindario |
| **Who’s the internal owner of the data?** | Departamento de Comercio de los EE. UU., Oficina del Censo, Encuesta sobre la comunidad estadounidense, estimación de 5 años, 2013-2017. (Datos preparados en el año 2019). | Departamento de Seguridad y Gobierno de los Estados Unidos |
| **How is it stored?** | Reportes en archivos planos (csv, JSON, database) | Reportes en archivos planos (csv, JSON, database) |
| **Additional comments** | Estos porcentajes representan el promedio de los 5 años de estudio. Se analizarán únicamente abandonos al programa escolar que sean meramente académicos y económicos (este último hasta cierto punto) | Esta información podría utilizarse para la creación de un índice de delincuencia pertinente a las zonas marcadas como escolares |

### 6.C In an ideal world, is there additional data you would want to get/gather that would be relevant to this problem?

- Información de rutas de transporte casa-escuela, si es público o privado, tiempos de traslado.
- Información socioeconómica (plusvalía, ingresos por hogar) de las zonas donde se encuentran las escuelas. (Encuesta de ingresos y gastos EEUU) 

## 7. Analysis

|  | **Analysis 1** | **Analysis 2** |
|-|-|-|
| **Analysis type** | Descripción | Clasificación |
| **Purpose of the analysis** | Obtener conocimientos generales de la estructura de los datos | Obtener la probabilidad/score de que un alumno se gradúe a tiempo y segmentar en grupos |
| **Which action will this analysis inform?** | Identificación de relaciones entre variables para los análisis posteriores | Decidir si se le aplica o no un tratamiento.<br/><br/>El modelo servirá para predecir en un corte del último año si el riesgo del alumno ha cambiado y poder cambiar el tratamiento (acción) aplicado. |
| **How will you validate this analysis using existing data? What methodology and what metrics will you use?** | Se validará con el cliente las distribuciones encontradas en sus datos tienen sentido para  negocio, si las categorías pequeñas pueden ser colapsadas, si existen agrupaciones naturales que se deban considerar etc. | Se preguntará al usuario/cliente si los segmentos y grupos definidos hacen sentido. Se hará un análisis sobre el tamaño de cada grupo (para observar si están desbalanceados y si esto tiene sentido) |

## 8. Ethical considerations

| **Privacy:** Are you working with personal and/or sensitive data that is individually identifiable? Mention them. | - Ingresos por hogares <br/>  - Domicilio <br/>  - Matrícula por estudiante |
|:-|:-|
| **Transparency:** Which stakeholders should know about which parts of the project? Stakeholders typically include policymakers, frontline workers, people who will be affected by the actions, etc. | - Departamento de Educación de Estados Unidos <br/>  - Comité directivo de cada escuela |
| **Discrimination/Equity:** Are there any specific groups for whom you want to ensure equity of outcomes?  eg. groups of interest defined by gender, age, localization, social class, educational level, urban/rural, ethnicity | - Raza <br/> - Sexo <br/> - Localización geográfica <br/> - Clases sociales |
| **Social License:** If the entire population of the country finds out about your project, will they be ok with it? Why? | Impulsar a estudiantes a concluir sus estudios a tiempo. Se considera que los proyectos relacionados con la educación de los jóvenes tienen impacto positivo en la sociedad. |
| **Accountability:** Who are the people responsible for all the things above? | - Departamento de Educación de Estados Unidos <br/> - Comité directivo de cada escuela <br/> |
| **Any other considerations such as consent, legal, etc.** | Firma de aviso de privacidad para el uso de datos de alumnos para la realización del proyecto |

## 9. What field trial or randomized controlled trial can you design to validate the project in the field? The outcomes you will measure should match your goals. Define the population in which the model will be tested. Define the duration of the trial. Specify the baseline. You should measure the impact in different population subgroups

Prueba piloto hacia los grupos identificados de un estado en específico con el objetivo de evaluar el desempeño de las acciones descritas en los puntos anteriores y medir el impacto de cada una de ellas sobre los grupos. Dicha prueba piloto tendría la duración de un ciclo escolar. 

La tasa de graduados en el ciclo escolar en las escuelas/estados/distritos/ que fueron tratadas vs la tasa de graduados en las mismas escuelas en el ciclo escolar anterior sin tratamiento. 

Dos escuelas con el mismo contexto sociodemográfico, socioeconómico con una tasa similar de graduados. Una escuela recibe el tratamiento y otra no. Medir la tasa de graduados en tiempo y medir si el cambio es significativo. 

## 10. Who are the external organizations and internal departments that will need to be involved?

NR

