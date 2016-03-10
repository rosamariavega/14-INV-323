# 14-INV-323
#Evaluación de las Proteínas del Ciclo Celular en el Cáncer de Pene



#1.Equipo de investigadores

##1.1 Investigador principal

El Investigador Principal (IP) del proyecto es el Prof. Dr. Alcides Chaux, Director de la Dirección de Investigación y Divulgación Científica (DIDCI) de la Universidad del Norte. El IP estará a cargo del diseño y supervisión del proyecto, del análisis de datos, y de la redacción de informes de investigación y documentos relacionados.

###1.2 Asistente de investigación

El Asistente de Investigación (AI) estará a cargo de la recolección y análisis de datos y redacción de informes de investigación y documentos relacionados. El AI tendrá una carga horaria de 15 (quince) horas semanales.


#2.Objetivos del proyecto

#2.1 Objetivos principales

Los objetivos principales de este proyecto pueden agruparse en 2 categorías:

Incrementar el conocimiento acerca de la biología molecular del cáncer de pene, con énfasis en la evaluación del ciclo celular.

Ofrecer un programa de entrenamiento efectivo en investigación científica, orientado a la adquisición de habilidades concretas para el diseño, gestión y ejecución de proyectos de investigación.

#2.2 Objetivos principales específicos

Los objetivos específicos de este proyecto pueden agruparse en 2 categorías:

Evaluar visual y digitalmente la expresión inmunohistoquímica de proteínas relacionadas al ciclo celular en carcinomas escamosos del pene, determinando su asociación con características histopatológicas y virales.

Entrenar efectivamente al AI en el diseño de proyectos de investigación, recolección de datos, morfología y biología molecular del cáncer de pene, análisis estadístico de datos, programación en R, utilización de RStudio, herramientas de ciencia de datos, interpretación de resultados, y redacción y publicación de informes de investigación.


#3.Antecedentes

Debido a factores aún no totalmente caracterizados el cáncer de pene presenta una alta incidencia en el Paraguay comparada con la observada en países desarrollados (Chaux2013). Esto permite la explotación de un nicho de investigación centrado en la patología del cáncer de pene en nuestro país. Tras varios años de estar realizando investigaciones en la morfología, características clínicas y epidemiológicas, y factores pronósticos patológicos (Chaux2010) hemos incursionado en el campo de la biología molecular del cáncer de pene (Chaux2013,Chaux2014,Bezerra2014,Faraj2015). Uno de los problemas principales dentro de este tópico es la falta de información detallada y profunda acerca de la biología molecular del cáncer de pene. El conocimiento acabado acerca de la biología del cáncer de pene permitiría comprender cómo se origina y por qué presenta las particularidades epidemiológicas observadas. Más aún, este conocimiento podría ser útil para el desarrollo de estrategias clínicas más efectivas, con diagnósticos más significativos y tratamientos mejor orientados(Gerber2008).

Dentro de nuestro programa de investigación en cáncer de pene hemos recolectado a lo largo de dos décadas más de 100 muestras de tejido tumoral y construido a partir de estas muestras 4 microarrays tisulares (TMA, por tissue microarray). Utilizando estos 4 TMA hemos iniciado hace 2 años nuestra investigación en la biología molecular del cáncer de pene, estudiando varias vías metabólicas tales como las de blanco de rapamicina en mamíferos y la del receptor epidérmico del factor de crecimiento (Chaux2014,Chaux2013). Hemos estado publicando los resultados de estas investigaciones en revistas internacionales indexadas evaluadas por pares, estableciéndonos firmemente en el frente de avance de esta área de la Ciencia. Sin embargo, aún quedan muchas vías metabólicas por estudiar, sobre todo las directamente relacionadas con el control del crecimiento y diferenciación de las células tumorales.

Considerando la escasa tradición científica seria en el campo de la biología molecular del cáncer en nuestro país y la imperiosa necesidad de educar una generación de nuevos científicos, proponemos este proyecto denominado ``Evaluación de las Proteínas del Ciclo Celular en el Cáncer de Pene''. Mediante este proyecto se entrenará al AI en el diseño de estudios de investigación, recolección de datos, análisis estadístico y programación de paquetes informáticos, interpretación de resultados, y redacción y presentación de informes de investigación. Este entrenamiento estará centrado en la ejecución específica de este proyecto, por lo que se espera generar habilidades y capacidades efectivas para la investigación científica.


#4.Marco teórico

El cáncer de pene es un tumor infrecuente en países desarrollados de Norteamérica y Europa, representando, sin embargo, un serio problema de salud pública en países en vías de desarrollo (Siegel2015,Bleeker2009). La incidencia es particularmente alta en países como Brasil y Paraguay, donde las tasas son de hasta 4 veces mayores a las observadas en países del primer mundo (Chaux2013). No existen explicaciones satisfactorias para estas variaciones geográficas, pero factores de riesgo tales como la falta de circuncisión, fimosis, tabaquismo, antecedentes de desgarros peneanos, enfermedades inflamatorias crónicas, pobre higiene genital, y ciertas infecciones virales podrían tener alguna influencia en las regiones con mayor incidencia (Bleeker2009,Chaux2013).

La mayoría de los cánceres peneanos son carcinomas escamosos, reconociéndose un variado espectro de 12 subtipos histológicos distintos, cada uno con características clinicopatológicas y pronósticas particulares (Chaux2012). El desarrollo del cáncer de pene sigue una vía patogénica bimodal, una asociada con la infección por el virus del papiloma humano (HPV) y otra independiente de la infección viral (Chaux2012). A pesar de que el cáncer de pene es más frecuentemente una enfermedad loco-regional, se observa diseminación sistémica y metástasis a distancia en hasta el 40% de los pacientes. En este contexto, la muerte por cáncer diseminado aparece habitualmente dentro de los 2 a 3 años del diagnóstico inicial (Pizzocaro2010). Mientras que la cirugía y la radioterapia son las opciones de elección en pacientes con tumores localizados, la quimioterapia es la opción principal para aquellos con enfermedad diseminada. Desafortunadamente, las tasas de respuesta al tratamiento quimioterapéutico están lejos de ser aceptables (Sonpavde2013). Por lo tanto, se requieren de otros enfoques, especialmente aquellos que involucran el uso de terapias dirigidas (Gerber2008).

Las terapias dirigidas han cambiado significativamente el tratamiento del cáncer durante los últimos 10 años. Al involucrar mecanismos de acción distintos a los de la quimioterapia citotóxica tradicional, suelen ser mejor toleradas, asociándose con menos efectos secundarios adversos. Estos fármacos son parte hoy en día del tratamiento de muchos tumores malignos (Gerber2008). Sin embargo, no existen protocolos de tratamiento dirigido para pacientes con cáncer de pene diseminado, principalmente por dos razones. La primera está relacionada con la rareza de estos tumores en países desarrollados en los que estos fármacos están en evaluación o aprobados para su uso clínico. La segunda se relaciona con la escasez de reportes de investigación estudiando la biología molecular del cáncer de pene, buscando identificar alteraciones en vías metabólicas que sean de interés para el desarrollo de terapias dirigidas.

El propósito del presente proyecto es evaluar la expresión inmunohistoquímica de diversas proteínas involucradas en el control del ciclo celular en tumores peneanos, evaluando la asociación entre los niveles de expresión, las características histopatológicas y la presencia de HPV.


#5.Metodología y plan de trabajo

El tiempo de duración del proyecto es de 12 meses, desde julio de 2015 a junio de 2016. Se medirán los niveles de expresión inmunohistoquímica de 5 proteínas relacionadas con el ciclo celular (p53, Ki67, cyclin-D1, p16INK4a y MDM2) en 112 muestras tisulares de carcinomas escamosos. Las muestras tisulares fueron obtenidas de los casos de consulta del IP y consistieron en tejido tumoral fijado en formol al 10% y embebido en parafina. A partir de estas muestras tisulares se confeccionaron 4 TMA en el TMA Lab Core de la Johns Hopkins University (Baltimore, MD), siguiendo un protocolo previamente publicado (Fedor2005). A partir de estos bloques de TMA se obtuvieron cortes tisulares que fueron teñidos con Hematoxilina & Eosina (HE). Las tinciones inmunohistoquímicas fueron llevadas a cabo siguiendo protocolos previamente publicados (Chaux2014a,Chaux2013c,Munari2015,Bezerra2015). Los TMA correspondientes a las tinciones con HE e inmunohistoquímica se encuentran almacenadas en los archivos tisulares del IP.

La medición se realizará visualmente y mediante análisis digital de imágenes. Posteriormente se analizarán estos niveles de expresión, evaluando su rol en la alteración del ciclo celular de las células tumorales y su asociación con características morfológicas del tumor. Este proceso requerirá el uso intensivo de herramientas de ciencias de datos tales como R/RStudio, ImageJ, GitHub, MarkDown, y similares.

La hipótesis básica de trabajo es que existen alteraciones específicas de vías metabólicas particulares en las células tumorales del carcinoma escamoso que son evidenciables de una forma más objetiva mediante el análisis digital de imágenes. Asimismo, existen correlaciones entre las expresiones inmunohistoquímicas de ciertas proteínas relacionadas al ciclo celular y las características morfológicas del tumor, lo que sugeriría mecanismos oncogénicos particulares y posiblemente blancos terapéuticos específicos.

El uso de estos TMA para investigación fue aprobado por el Institutional Board Review (IBR) de la Johns Hopkins University (Baltimore, MD).

El Proyecto estará dividido en 5 fases: diagnóstico de las lesiones tumorales, evaluación de microarrays tisulares, confección de la base de datos, análisis estadístico, y redacción del informe de investigación. Estas fases se describen a continuación.


#5.1 Diagnóstico de las lesiones tumorales

#5.1.1 Descripción

Primeramente se procederá a la clasificación de los 4 TMA disponibles conteniendo muestras tisulares de 112 casos de cáncer de pene. Se identificarán las láminas histológicas completas correspondientes a estos casos y se procederá a la clasificación histopatológica de las lesiones tumorales, usando criterios previamente establecidos (Chaux2010b,Chaux2012). El AI trabajará bajo la supervisión del IP para la correcta clasificación de las lesiones tumorales y la adecuada identificación de las características histopatológicas relevantes. Esta evaluación se realizará sobre muestras tisulares teñidas con hematoxilina & eosina.

#5.1.2 Indicador de cumplimiento

Caracterización morfológica de los tumores incluidos en los 4 TMA, incluyendo subtipo histológicos y grado histológico

#5.1.3 Meta mínima

Identificación de los campos tumorales en los 4 TMA

#5.1.4 Medios de verificación

Láminas histológicas, microfotografías de los campos TMA (H\&E), base de datos (parcial) y libro de código en repositorio

#5.1.5 Riesgos

Tejido insuficiente para diagnóstico anatomopatológico apropiado

#5.1.6 Cronograma

Julio 2015 -- Agosto 2015

#5.2 Evaluación de microarrays tisulares

#5.2.1 Descripción

Una vez que todas las lesiones tumorales hayan sido clasificadas se procederá a la evaluación visual de la expresión inmunohistoquímica de proteínas relacionadas con el ciclo celular, incluyendo p53, cyclin D1, Ki-67, p16INK4a, y MDM2. Esta evaluación se llevará a cabo en un microscopio Zeiss AxioLab 2. El AI estimará visualmente los niveles de expresión utilizando una escala semicuantitativa previamente desarrollada y  validada (Chaux2013). Esta estimación será controlada por el IP.

Tras la evaluación visual se procederá a digitalizar los TMA, utilizando una técnica previamente descrita (Chaux2014). Posteriormente se procederá al análisis de las imágenes utilizando un protocolo de análisis digital previamente desarrollado y publicado por el IP (Chaux2013). El AI trabajará activamente en la redacción de nuevos protocolos de análisis digital y en la programación de algoritmos para mejorar los protocolos ya existentes.

#5.2.2 Indicador de cumplimiento

Medición de niveles de expresión inmunohistoquímica mediante evaluación visual y evaluación digital, en cada uno de los 112 casos, por cada una de las proteínas estudiadas

#5.2.3 Meta mínima

Medición de niveles de expresión inmunohistoquímica de p53 y p16INK4a mediante evaluación visual y evaluación digital

#5.2.4 Medios de verificación

Microfotografías de los campos de TMA (inmunohistoquímica), base de datos (parcial) y libro de código en repositorio

#5.2.5 Riesgos

Protocolo de evaluación digital de la expresión inmunohistoquímica con calibración inadecuada

#5.2.6 Cronograma

Septiembre 2015 -- Diciembre 2015

#5.3 Confección de la base de datos

Tras la recolección de datos visuales y digitales el AI confeccionará una base de datos en la que consignará toda la información recolectada hasta el momento, incluyendo los datos histopatológicos y la evaluación visual y digital de cada uno de los casos de cáncer de pene. Dentro de nuestra consigna de libertad de información haremos que esta base de datos esté disponible gratuitamente para todos los investigadores a través de repositorios digitales internacionales.

#5.3.1 Indicador de cumplimiento

Base de datos finalizada, incluyendo datos histopatológicos, microfotografías, y datos de medición.

#5.3.2 Meta mínima

Base de datos conteniendo información sobre p53 y p16INK4a, incluyendo datos histopatológicos, microfotografías, y datos de medición.

#5.3.3 Medios de verificación

Microfotografías de los campos de TMA (H&E, inmunohistoquímica), base de datos (completa) y libro de código en repositorio

#5.3.4 Riesgos

Base de datos incompleta con datos/casos perdidos en número suficiente como para comprometer la calidad del análisis

#5.3.5 Cronograma

Enero 2016 -- Febrero 2016

#5.4 Análisis estadístico

El AI procederá al análisis estadístico de los datos bajo la supervisión del IP. El análisis de datos se realizará utilizando el lenguaje de programación R \cite{RCoreTeam}. El AI aprenderá las habilidades necesarias para la programación en R y la utilización de RStudio como interfaz de usuario. Se espera además que el AI adquiera conceptos y habilidades para la aplicación de técnicas estadísticas avanzadas, centradas principalmente en la construcción de modelos matemáticos predictivos. Asimismo, dentro de nuestra política de investigación reproducible, el AI utilizará GitHub (\url{https://github.com/}) para publicar el código de su análisis estadístico, y pondrá a disposición de la comunidad científica global sus resultados a través de repositorios digitales internacionales.

#5.4.1 Indicador de cumplimiento

Análisis de datos concluido, incluyendo el protocolo detallado de análisis de datos y los modelos estadísticos utilizados

#5.4.2 Meta mínima

Análisis descriptivo de datos concluido

#5.4.3 Medios de verificación

Resultados del análisis de datos y el código en R utilizado publicado en un repositorio internacional

#5.4.4 Riesgos

Modelos estadísticos inconsistentes

#5.4.5 Cronograma

Marzo 2016 -- Abril 2016

#5.5 Redacción de informes de investigación

Como fase final el AI redactará el informe de investigación reportando los resultados del proyecto. Este informe se enviará para publicación en una revista internacional indexada con evaluación por pares. El AI redactará además todos los materiales para ser utilizados en simposios, congresos, talleres, y conferencias en las cuales se divulguen los hallazgos del proyecto. El IP supervisará todo el proceso de redacción.

#5.5.1 Indicador de cumplimiento

Informe de investigación finalizado, enviado para evaluación y publicado. Divulgación de los resultados de la investigación a la comunidad académica

#5.5.2 Meta mínima

Informe de investigación finalizado

#5.5.3 Medios de verificación

Artículo publicado en una revista internacional indexada. Documentación (certificados, fotografías, videos) del trabajo presentado en eventos científicos

#5.5.4 Supuestos/riesgos

Artículo no finalizado o rechazado para publicación

#5.5.5 Cronograma

Mayo 2016 -- Junio 2016

#6.Relevancia

#6.1 Relevancia social

La implementación de este proyecto sobre ``Evaluación de las proteínas del ciclo celular en el cáncer de pene'' permitirá obtener un conocimiento más acabado y preciso acerca de la biología molecular del cáncer. Este proyecto ayudará no sólo a comprender mejor cómo se origina y progresa la enfermedad sino también dará pistas acerca de cómo ofrecer mejores opciones terapéuticas a los pacientes afectos. Considerando que el Paraguay es uno de los países con la incidencia más alta de cáncer de pene en el mundo, la importancia social de este conocimiento es evidente. Más aún, considerando que las muestras de tejido tumoral corresponden a pacientes paraguayos, esto permitirá que los resultados sean aplicables directamente a los pacientes afectos, ya que no se trataría de información importada o llevada a cabo en otras poblaciones.

#6.2 Relevancia científica

Debido a la rareza del cáncer de pene en países desarrollados el conocimiento disponible acerca de su biología molecular es escaso. Este proyecto sobre la ``Evaluación de las proteínas del ciclo celular en el cáncer de pene'' permitirá estudiar los niveles de expresión inmunohistoquímica de proteínas relacionadas al ciclo celular, investigando alteraciones metabólicas en células tumorales y evaluando su asociación con características histopatológicas y virales. Todo esto permitirá incrementar el conocimiento científico disponible acerca de la enfermedad. Además, este proyecto permitirá continuar con nuestra línea de investigación en el cáncer de pene, dentro de un programa de iniciación científica, ofreciendo un entrenamiento formal en ciencia de datos e incrementando por lo tanto el capital humano disponible para realizar investigación.

#6.3 Relevancia contemporánea

El conocimiento puramente morfológico o clínico ya no es suficiente hoy en día para comprender una enfermedad, mucho menos para su adecuado diagnóstico y tratamiento. Actualmente se requiere un conocimiento más profundo acerca de la biología molecular de las enfermedades, buscando mejores modelos teóricos mediante los cuales desarrollar estrategias más efectivas para el manejo de los pacientes. Dentro de esta línea, este proyecto sobre la ``Evaluación de las proteínas del ciclo celular en el cáncer de pene'' evaluará uno de los aspectos más importantes de la biología molecular del cáncer, el control del ciclo celular.

#7.Estrategia de divulgación

Este proyecto acerca de la ``Evaluación de las proteínas del ciclo celular en el cáncer de pene'' incrementará el conocimiento que se tiene acerca de la biología molecular del cáncer de pene. Este proyecto permitirá una mejor comprensión de la relación existente entre las características morfológicas y virales de las células tumorales y el control del ciclo celular. Mediante esto, este proyecto permitirá evaluar y validar estudios similares que se han o se están llevando a cabo centrados en el área de investigación del cáncer de pene. Todos estos resultados serán puestos a disposición de la comunidad científica nacional e internacional y del público en general interesado de manera abierta y gratuita.

Se buscará la difusión de los resultados de esta investigación mediante canales académicos y no académicos. En el ámbito académico, los resultados se divulgarán mediante Congresos y Simposios, ya sea organizados por la Universidad del Norte u otras instituciones académicas, y el reporte de investigación final será enviado para publicación a una revista científica internacional indexada evaluada por pares y con opción de acceso libre al artículo publicado. En el ámbito no académico, estos resultados se divulgarán al público en general mediante entrevistas radiales y televisivas, además de medios impresos y digitales, y redes sociales.

#Referencias

[1] Alcides Chaux, George J Netto, Ingrid M Rodr ́ıguez, Jos ́e E Barreto, Judith Oertell, Sandra Ocampos, Hugo Boggino, Ricardo Codas, F Xavier Bosch, Silvia de Sanjose, Nubia Muñoz, Allan Hildesheim, and Antonio L Cubilla. Epidemiologic profile, sexual history, pathologic features, and human papillomavirus status of 103 patients with penile carcinoma. World J.
Urol., 31(4):861–867, August 2013.

[2] Alcides Chaux, Elsa F Velazquez, Ferran Algaba, Gustavo Ayala, and Antonio L Cubilla. Developments in the pathology of penile squamous cell carcinomas. Urology, 76(2 Suppl 1):S7–S14, August 2010.

[3] Alcides Chaux, Enrico Munari, Betina Katz, Rajni Sharma, Kristen Lecksell, Antonio L Cubilla, Arthur L Burnett, and George J Netto. The epidermal growth factor receptor is frequently overexpressed in penile squamous cell carcinomas: A tissue microarray and digital image analysis study of 112 cases. Hum. Pathol., 44(12):2690–2695, December 2013.

[4] Alcides Chaux, Enrico Munari, Antonio L Cubilla, Jessica Hicks, Kristen Lecksell, Arthur L Burnett, and George J Netto. Immunohistochemical expression of the mammalian target of rapamycin pathway in penile squamous cell carcinomas: A tissue microarray study of 112 cases. Histopathology, 64(6):863–871, May 2014.

[5] Stephania M Bezerra, Alcides Chaux, Mark W Ball, Sheila F Faraj, Enrico Munari, Nilda Gonzalez-Roibon, Rajni Sharma, Trinity J Bivalacqua, Arthur L Burnett, and George J Netto. Human papillomavirus infection and immunohistochemical p16INK4a expression as predictors of outcome in penile squamous cell carcinomas. Hum. Pathol., 46(4):532–40, April 2014.

[6] Sheila F Faraj, Alcides Chaux, Nilda Gonzalez-Roibon, Enrico Munari, Antonio L Cubilla, Ie-Ming Shih, and George J Netto. Immunohistochemical expression of ARID1A in penile squamous cell carcinomas: a tissue microarray study of 112 cases. Hum. Pathol., 46(5):761–766, February 2015.

[7] David E Gerber. Targeted therapies: A new generation of cancer treatments, February 2008.

[8] Rebecca L Siegel, Kimberly D Miller, and Ahmedin Jemal. Cancer statistics, 2015. CA Cancer J. Clin., 65(1):5–29, January 2015.

[9] M C G Bleeker, D A M Heideman, P J F Snijders, S Horenblas, J Dillner, and C J L M Meijer. Penile cancer: Epidemiology, pathogenesis and prevention, April 2009.

[10] Alcides Chaux and Antonio L Cubilla. Advances in the pathology of penile carcinomas, June 2012.

[11] Alcides Chaux and Antonio L Cubilla. The role of human papillomavirus infection in the pathogenesis of penile squamous cell carcinomas. Semin. Diagn. Pathol., 29(2):67–71, May 2012.

[12] Giorgio Pizzocaro, Ferran Algaba, Simon Horenblas, Eduard Solsona, Silvia Tana, Hein Van Der Poel, and Nicholas A Watkin. EAU penile cancer guidelines 2009. Eur. Urol., 57(6):1002–1012, June 2010.

[13] G Sonpavde, L C Pagliaro, C Buonerba, T B Dorff, R J Lee, and G Di Lorenzo. Penile cancer: Current therapy and future directions, May 2013.

[14] Helen L Fedor and Angelo M De Marzo. Practical methods for tissue microarray construction. Methods Mol. Med., 103:89–101, January 2005.

[15] Alcides Chaux, Antonio L Cubilla, Michael C Haffner, Kristen L Lecksell, Rajni Sharma, Art-hur L Burnett, and George J Netto. Combining routine morphology, p16INK4a immunohis-tochemistry, and in situ hybridization for the detection of human papillomavirus infection in penile carcinomas: A tissue microarray study using classifier performance analyses, February 2014.

[16] Alcides Chaux, Jeong S Han, Stephen Lee, Nilda Gonzalez-Roibon, Rajni Sharma, Arthur LBurnett, Antonio L Cubilla, and George J Netto. Immunohistochemical profile of the penile urethra and differential expression of GATA3 in urothelial versus squamous cell carcinomas of the penile urethra. Hum. Pathol., 44(12):2760–7, December 2013.

[17] Enrico Munari, Alcides Chaux, Leonel Maldonado, Eva Comp ́erat, Justine Varinot, Trinity J Bivalacqua, Mohammad O Hoque, and George J Netto. Cyclin A1 expression predicts pro- gression in pT1 urothelial carcinoma of bladder: a tissue microarray study of 149 patients treated by transurethral resection. Histopathology, 66(2):262–9, January 2015.

[18] Stephania M Bezerra, Alcides Chaux, Mark W Ball, Sheila F Faraj, Enrico Munari, Nilda Gonzalez-Roibon, Rajni Sharma, Trinity J Bivalacqua, Arthur L Burnett, and George J Netto. Human papillomavirus infection and immunohistochemical p16(INK4a) expression as predictors of outcome in penile squamous cell carcinomas. Hum. Pathol., 46(4):532–40, April 2015.

[19] Alcides Chaux, Eva Comp ́erat, Justine Varinot, Jessica Hicks, Kristen Lecksell, Jason Solus, and George J Netto. High levels of phosphatase and tensin homolog expression are associated with tumor progression, tumor recurrence, and systemic metastases in pt1 urothelial carcinoma of the bladder: A tissue microarray study of 156 patients treated by transurethral resect.
In Urology, volume 81, pages 116–122, January 2013.

[20] R Core Team. R: A Language and Environment for Statistical Computing.












