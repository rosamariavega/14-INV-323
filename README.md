# 14-INV-323
Evaluación de las Proteínas del Ciclo Celular en el Cáncer de Pene



1. Equipo de investigadores
1.1 Investigador principal
El Investigador Principal (IP) del proyecto es el Prof. Dr. Alcides Chaux, Director de la Dirección de Investigación y Divulgación Científica (DIDCI) de la Universidad del Norte. El IP estará a cargo del diseño y supervisión del proyecto, del análisis de datos, y de la redacción de informes de investigación y documentos relacionados.

1.2 Asistente de investigación
El Asistente de Investigación (AI) estará a cargo de la recolección y análisis de datos y redacción de informes de investigación y documentos relacionados. El AI tendrá una carga horaria de 15 (quince) horas semanales.


2. Objetivos del proyecto

2.1 Objetivos principales
Los objetivos principales de este proyecto pueden agruparse en 2 categorías:
     Incrementar el conocimiento acerca de la biología molecular del cáncer de pene, con énfasis en la evaluación del ciclo celular.
     Ofrecer un programa de entrenamiento efectivo en investigación científica, orientado a la adquisición de habilidades concretas para el diseño, gestión y ejecución de proyectos de investigación.

2.2 Objetivos principales específicos
Los objetivos específicos de este proyecto pueden agruparse en 2 categorías:
    Evaluar visual y digitalmente la expresión inmunohistoquímica de proteínas relacionadas al ciclo celular en carcinomas escamosos del pene, determinando su asociación con características histopatológicas y virales.
    Entrenar efectivamente al AI en el diseño de proyectos de investigación, recolección de datos, morfología y biología molecular del cáncer de pene, análisis estadístico de datos, programación en R, utilización de RStudio, herramientas de ciencia de datos, interpretación de resultados, y redacción y publicación de informes de investigación.


3. Antecedentes

Debido a factores aún no totalmente caracterizados el cáncer de pene presenta una alta incidencia en el Paraguay comparada con la observada en países desarrollados (Chaux2013). Esto permite la explotación de un nicho de investigación centrado en la patología del cáncer de pene en nuestro país. Tras varios años de estar realizando investigaciones en la morfología, características clínicas y epidemiológicas, y factores pronósticos patológicos (Chaux2010) hemos incursionado en el campo de la biología molecular del cáncer de pene (Chaux2013,Chaux2014,Bezerra2014,Faraj2015). Uno de los problemas principales dentro de este tópico es la falta de información detallada y profunda acerca de la biología molecular del cáncer de pene. El conocimiento acabado acerca de la biología del cáncer de pene permitiría comprender cómo se origina y por qué presenta las particularidades epidemiológicas observadas. Más aún, este conocimiento podría ser útil para el desarrollo de estrategias clínicas más efectivas, con diagnósticos más significativos y tratamientos mejor orientados(Gerber2008).

Dentro de nuestro programa de investigación en cáncer de pene hemos recolectado a lo largo de dos décadas más de 100 muestras de tejido tumoral y construido a partir de estas muestras 4 microarrays tisulares (TMA, por tissue microarray). Utilizando estos 4 TMA hemos iniciado hace 2 años nuestra investigación en la biología molecular del cáncer de pene, estudiando varias vías metabólicas tales como las de blanco de rapamicina en mamíferos y la del receptor epidérmico del factor de crecimiento (Chaux2014,Chaux2013). Hemos estado publicando los resultados de estas investigaciones en revistas internacionales indexadas evaluadas por pares, estableciéndonos firmemente en el frente de avance de esta área de la Ciencia. Sin embargo, aún quedan muchas vías metabólicas por estudiar, sobre todo las directamente relacionadas con el control del crecimiento y diferenciación de las células tumorales.

Considerando la escasa tradición científica seria en el campo de la biología molecular del cáncer en nuestro país y la imperiosa necesidad de educar una generación de nuevos científicos, proponemos este proyecto denominado ``Evaluación de las Proteínas del Ciclo Celular en el Cáncer de Pene''. Mediante este proyecto se entrenará al AI en el diseño de estudios de investigación, recolección de datos, análisis estadístico y programación de paquetes informáticos, interpretación de resultados, y redacción y presentación de informes de investigación. Este entrenamiento estará centrado en la ejecución específica de este proyecto, por lo que se espera generar habilidades y capacidades efectivas para la investigación científica.


4. Marco teórico

El cáncer de pene es un tumor infrecuente en países desarrollados de Norteamérica y Europa, representando, sin embargo, un serio problema de salud pública en países en vías de desarrollo (Siegel2015,Bleeker2009). La incidencia es particularmente alta en países como Brasil y Paraguay, donde las tasas son de hasta 4 veces mayores a las observadas en países del primer mundo (Chaux2013). No existen explicaciones satisfactorias para estas variaciones geográficas, pero factores de riesgo tales como la falta de circuncisión, fimosis, tabaquismo, antecedentes de desgarros peneanos, enfermedades inflamatorias crónicas, pobre higiene genital, y ciertas infecciones virales podrían tener alguna influencia en las regiones con mayor incidencia (Bleeker2009,Chaux2013).

La mayoría de los cánceres peneanos son carcinomas escamosos, reconociéndose un variado espectro de 12 subtipos histológicos distintos, cada uno con características clinicopatológicas y pronósticas particulares (Chaux2012). El desarrollo del cáncer de pene sigue una vía patogénica bimodal, una asociada con la infección por el virus del papiloma humano (HPV) y otra independiente de la infección viral (Chaux2012). A pesar de que el cáncer de pene es más frecuentemente una enfermedad loco-regional, se observa diseminación sistémica y metástasis a distancia en hasta el 40% de los pacientes. En este contexto, la muerte por cáncer diseminado aparece habitualmente dentro de los 2 a 3 años del diagnóstico inicial (Pizzocaro2010). Mientras que la cirugía y la radioterapia son las opciones de elección en pacientes con tumores localizados, la quimioterapia es la opción principal para aquellos con enfermedad diseminada. Desafortunadamente, las tasas de respuesta al tratamiento quimioterapéutico están lejos de ser aceptables (Sonpavde2013). Por lo tanto, se requieren de otros enfoques, especialmente aquellos que involucran el uso de terapias dirigidas (Gerber2008).

Las terapias dirigidas han cambiado significativamente el tratamiento del cáncer durante los últimos 10 años. Al involucrar mecanismos de acción distintos a los de la quimioterapia citotóxica tradicional, suelen ser mejor toleradas, asociándose con menos efectos secundarios adversos. Estos fármacos son parte hoy en día del tratamiento de muchos tumores malignos (Gerber2008). Sin embargo, no existen protocolos de tratamiento dirigido para pacientes con cáncer de pene diseminado, principalmente por dos razones. La primera está relacionada con la rareza de estos tumores en países desarrollados en los que estos fármacos están en evaluación o aprobados para su uso clínico. La segunda se relaciona con la escasez de reportes de investigación estudiando la biología molecular del cáncer de pene, buscando identificar alteraciones en vías metabólicas que sean de interés para el desarrollo de terapias dirigidas.

El propósito del presente proyecto es evaluar la expresión inmunohistoquímica de diversas proteínas involucradas en el control del ciclo celular en tumores peneanos, evaluando la asociación entre los niveles de expresión, las características histopatológicas y la presencia de HPV.


5. Metodología y plan de trabajo

El tiempo de duración del proyecto es de 12 meses, desde julio de 2015 a junio de 2016. Se medirán los niveles de expresión inmunohistoquímica de 5 proteínas relacionadas con el ciclo celular (p53, Ki67, cyclin-D1, p16INK4a y MDM2) en 112 muestras tisulares de carcinomas escamosos. Las muestras tisulares fueron obtenidas de los casos de consulta del IP y consistieron en tejido tumoral fijado en formol al 10% y embebido en parafina. A partir de estas muestras tisulares se confeccionaron 4 TMA en el TMA Lab Core de la Johns Hopkins University (Baltimore, MD), siguiendo un protocolo previamente publicado \cite{Fedor2005}. A partir de estos bloques de TMA se obtuvieron cortes tisulares que fueron teñidos con Hematoxilina & Eosina (HE). Las tinciones inmunohistoquímicas fueron llevadas a cabo siguiendo protocolos previamente publicados (Chaux2014a,Chaux2013c,Munari2015,Bezerra2015). Los TMA correspondientes a las tinciones con HE e inmunohistoquímica se encuentran almacenadas en los archivos tisulares del IP.

La medición se realizará visualmente y mediante análisis digital de imágenes. Posteriormente se analizarán estos niveles de expresión, evaluando su rol en la alteración del ciclo celular de las células tumorales y su asociación con características morfológicas del tumor. Este proceso requerirá el uso intensivo de herramientas de ciencias de datos tales como R/RStudio, ImageJ, GitHub, MarkDown, y similares.

La hipótesis básica de trabajo es que existen alteraciones específicas de vías metabólicas particulares en las células tumorales del carcinoma escamoso que son evidenciables de una forma más objetiva mediante el análisis digital de imágenes. Asimismo, existen correlaciones entre las expresiones inmunohistoquímicas de ciertas proteínas relacionadas al ciclo celular y las características morfológicas del tumor, lo que sugeriría mecanismos oncogénicos particulares y posiblemente blancos terapéuticos específicos.

El uso de estos TMA para investigación fue aprobado por el Institutional Board Review (IBR) de la Johns Hopkins University (Baltimore, MD).

El Proyecto estará dividido en 5 fases: diagnóstico de las lesiones tumorales, evaluación de microarrays tisulares, confección de la base de datos, análisis estadístico, y redacción del informe de investigación. Estas fases se describen a continuación.


5.1 Diagnóstico de las lesiones tumorales

5.1.1 Descripción
Primeramente se procederá a la clasificación de los 4 TMA disponibles conteniendo muestras tisulares de 112 casos de cáncer de pene. Se identificarán las láminas histológicas completas correspondientes a estos casos y se procederá a la clasificación histopatológica de las lesiones tumorales, usando criterios previamente establecidos (Chaux2010b,Chaux2012). El AI trabajará bajo la supervisión del IP para la correcta clasificación de las lesiones tumorales y la adecuada identificación de las características histopatológicas relevantes. Esta evaluación se realizará sobre muestras tisulares teñidas con hematoxilina & eosina.
5.1.2 Indicador de cumplimiento
Caracterización morfológica de los tumores incluidos en los 4 TMA, incluyendo subtipo histológicos y grado histológico
5.1.3 Meta mínima
Identificación de los campos tumorales en los 4 TMA
5.1.4 Medios de verificación
Láminas histológicas, microfotografías de los campos TMA (H\&E), base de datos (parcial) y libro de código en repositorio
5.1.5 Riesgos
Tejido insuficiente para diagnóstico anatomopatológico apropiado
5.1.6 Cronograma
Julio 2015 -- Agosto 2015










