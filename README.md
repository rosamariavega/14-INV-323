# 14-INV-323
Evaluación de las Proteínas del Ciclo Celular en el Cáncer de Pene
\begin{document}
\maketitle

\section{Equipo de investigadores}
\subsection{Investigador principal}
El Investigador Principal (IP) del proyecto es el \textbf{Prof. Dr. Alcides Chaux}, Director de la Dirección de Investigación \& Divulgación Científica (DIDCI) de la Universidad del Norte. El IP estará a cargo del diseño y supervisión del proyecto, del análisis de datos, y de la redacción de informes de investigación y documentos relacionados.

\subsection{Asistente de investigación}
El Asistente de Investigación (AI) estará a cargo de la recolección y análisis de datos y redacción de informes de investigación y documentos relacionados. El AI tendrá una carga horaria de 15 (quince) horas semanales.

\section{Objetivos del proyecto}
\subsection{Objetivos principales}
Los objetivos principales de este proyecto pueden agruparse en 2 categorías:
\begin{enumerate}
\item Incrementar el conocimiento acerca de la biología molecular del cáncer de pene, con énfasis en la evaluación del ciclo celular.
\item Ofrecer un programa de entrenamiento efectivo en investigación científica, orientado a la adquisición de habilidades concretas para el diseño, gestión y ejecución de proyectos de investigación.
\end{enumerate}

\subsection{Objetivos principales específicos}
Los objetivos específicos de este proyecto pueden agruparse en 2 categorías:
\begin{enumerate}
\item Evaluar visual y digitalmente la expresión inmunohistoquímica de proteínas relacionadas al ciclo celular en carcinomas escamosos del pene, determinando su asociación con características histopatológicas y virales.
\item Entrenar efectivamente al AI en el diseño de proyectos de investigación, recolección de datos, morfología y biología molecular del cáncer de pene, análisis estadístico de datos, programación en R, utilización de RStudio, herramientas de ciencia de datos, interpretación de resultados, y redacción y publicación de informes de investigación.
\end{enumerate}

\section{Antecedentes}
Debido a factores aún no totalmente caracterizados el cáncer de pene presenta una alta incidencia en el Paraguay comparada con la observada en países desarrollados \cite{Chaux2013}. Esto permite la explotación de un nicho de investigación centrado en la patología del cáncer de pene en nuestro país. Tras varios años de estar realizando investigaciones en la morfología, características clínicas y epidemiológicas, y factores pronósticos patológicos \cite{Chaux2010b} hemos incursionado en el campo de la biología molecular del cáncer de pene \cite{Chaux2013a,Chaux2014,Bezerra2014,Faraj2015}. Uno de los problemas principales dentro de este tópico es la falta de información detallada y profunda acerca de la biología molecular del cáncer de pene. El conocimiento acabado acerca de la biología del cáncer de pene permitiría comprender cómo se origina y por qué presenta las particularidades epidemiológicas observadas. Más aún, este conocimiento podría ser útil para el desarrollo de estrategias clínicas más efectivas, con diagnósticos más significativos y tratamientos mejor orientados\cite{Gerber2008}.

Dentro de nuestro programa de investigación en cáncer de pene hemos recolectado a lo largo de dos décadas más de 100 muestras de tejido tumoral y construido a partir de estas muestras 4 microarrays tisulares (TMA, por \emph{tissue microarray}). Utilizando estos 4 TMA hemos iniciado hace 2 años nuestra investigación en la biología molecular del cáncer de pene, estudiando varias vías metabólicas tales como las de blanco de rapamicina en mamíferos y la del receptor epidérmico del factor de crecimiento \cite{Chaux2014,Chaux2013a}. Hemos estado publicando los resultados de estas investigaciones en revistas internacionales indexadas evaluadas por pares, estableciéndonos firmemente en el frente de avance de esta área de la Ciencia. Sin embargo, aún quedan muchas vías metabólicas por estudiar, sobre todo las directamente relacionadas con el control del crecimiento y diferenciación de las células tumorales.

Considerando la escasa tradición científica seria en el campo de la biología molecular del cáncer en nuestro país y la imperiosa necesidad de educar una generación de nuevos científicos, proponemos este proyecto denominado ``Evaluación de las Proteínas del Ciclo Celular en el Cáncer de Pene''. Mediante este proyecto se entrenará al AI en el diseño de estudios de investigación, recolección de datos, análisis estadístico y programación de paquetes informáticos, interpretación de resultados, y redacción y presentación de informes de investigación. Este entrenamiento estará centrado en la ejecución específica de este proyecto, por lo que se espera generar habilidades y capacidades efectivas para la investigación científica.

\section{Marco teórico}
El cáncer de pene es un tumor infrecuente en países desarrollados de Norteamérica y Europa, representando, sin embargo, un serio problema de salud pública en países en vías de desarrollo  \cite{Siegel2015,Bleeker2009}. La incidencia es particularmente alta en países como Brasil y Paraguay, donde las tasas son de hasta 4 veces mayores a las observadas en países del primer mundo \cite{Chaux2013}. No existen explicaciones satisfactorias para estas variaciones geográficas, pero factores de riesgo tales como la falta de circuncisión, fimosis, tabaquismo, antecedentes de desgarros peneanos, enfermedades inflamatorias crónicas, pobre higiene genital, y ciertas infecciones virales podrían tener alguna influencia en las regiones con mayor incidencia \cite{Bleeker2009,Chaux2013}.

La mayoría de los cánceres peneanos son carcinomas escamosos, reconociéndose un variado espectro de 12 subtipos histológicos distintos, cada uno con características clinicopatológicas y pronósticas particulares \cite{Chaux2012}. El desarrollo del cáncer de pene sigue una vía patogénica bimodal, una asociada con la infección por el virus del papiloma humano (HPV) y otra independiente de la infección viral \cite{Chaux2012a}. A pesar de que el cáncer de pene es más frecuentemente una enfermedad loco-regional, se observa diseminación sistémica y metástasis a distancia en hasta el 40\% de los pacientes. En este contexto, la muerte por cáncer diseminado aparece habitualmente dentro de los 2 a 3 años del diagnóstico inicial \cite{Pizzocaro2010}. Mientras que la cirugía y la radioterapia son las opciones de elección en pacientes con tumores localizados, la quimioterapia es la opción principal para aquellos con enfermedad diseminada. Desafortunadamente, las tasas de respuesta al tratamiento quimioterapéutico están lejos de ser aceptables \cite{Sonpavde2013}. Por lo tanto, se requieren de otros enfoques, especialmente aquellos que involucran el uso de terapias dirigidas \cite{Gerber2008}.

Las terapias dirigidas han cambiado significativamente el tratamiento del cáncer durante los últimos 10 años. Al involucrar mecanismos de acción distintos a los de la quimioterapia citotóxica tradicional, suelen ser mejor toleradas, asociándose con menos efectos secundarios adversos. Estos fármacos son parte hoy en día del tratamiento de muchos tumores malignos \cite{Gerber2008}. Sin embargo, no existen protocolos de tratamiento dirigido para pacientes con cáncer de pene diseminado, principalmente por dos razones. La primera está relacionada con la rareza de estos tumores en países desarrollados en los que estos fármacos están en evaluación o aprobados para su uso clínico. La segunda se relaciona con la escasez de reportes de investigación estudiando la biología molecular del cáncer de pene, buscando identificar alteraciones en vías metabólicas que sean de interés para el desarrollo de terapias dirigidas.

El propósito del presente proyecto es evaluar la expresión inmunohistoquímica de diversas proteínas involucradas en el control del ciclo celular en tumores peneanos, evaluando la asociación entre los niveles de expresión, las características histopatológicas y la presencia de HPV.

\section{Metodología y plan de trabajo}
El tiempo de duración del proyecto es de 12 meses, desde junio de 2015 a mayo de 2016. Se medirán los niveles de expresión inmunohistoquímica de 5 proteínas relacionadas con el ciclo celular (p53, Ki67, cyclin-D1, p16INK4a y MDM2) en 112 muestras tisulares de carcinomas escamosos. Las muestras tisulares fueron obtenidas de los casos de consulta del IP y consistieron en tejido tumoral fijado en formol al 10\% y embebido en parafina. A partir de estas muestras tisulares se confeccionaron 4 TMA en el TMA Lab Core de la Johns Hopkins University (Baltimore, MD), siguiendo un protocolo previamente publicado \cite{Fedor2005}. A partir de estos bloques de TMA se obtuvieron cortes tisulares que fueron teñidos con Hematoxilina \& Eosina (HE). Las tinciones inmunohistoquímicas fueron llevadas a cabo siguiendo protocolos previamente publicados \cite{Chaux2014a,Chaux2013c,Munari2015,Bezerra2015}. Los TMA correspondientes a las tinciones con HE e inmunohistoquímica se encuentran almacenadas en los archivos tisulares del IP.

La medición se realizará visualmente y mediante análisis digital de imágenes. Posteriormente se analizarán estos niveles de expresión, evaluando su rol en la alteración del ciclo celular de las células tumorales y su asociación con características morfológicas del tumor. Este proceso requerirá el uso intensivo de herramientas de ciencias de datos tales como R/RStudio, ImageJ, GitHub, MarkDown, y similares.

La hipótesis básica de trabajo es que existen alteraciones específicas de vías metabólicas particulares en las células tumorales del carcinoma escamoso que son evidenciables de una forma más objetiva mediante el análisis digital de imágenes. Asimismo, existen correlaciones entre las expresiones inmunohistoquímicas de ciertas proteínas relacionadas al ciclo celular y las características morfológicas del tumor, lo que sugeriría mecanismos oncogénicos particulares y posiblemente blancos terapéuticos específicos.

El uso de estos TMA para investigación fue aprobado por el Institutional Board Review (IBR) de la Johns Hopkins University (Baltimore, MD).

El Proyecto estará dividido en 5 fases: diagnóstico de las lesiones tumorales, evaluación de microarrays tisulares, confección de la base de datos, análisis estadístico, y redacción del informe de investigación. Estas fases se describen a continuación.

\subsection{Diagnóstico de las lesiones tumorales}
\subsubsection{Descripción}
Primeramente se procederá a la clasificación de los 4 TMA disponibles conteniendo muestras tisulares de 112 casos de cáncer de pene. Se identificarán las láminas histológicas completas correspondientes a estos casos y se procederá a la clasificación histopatológica de las lesiones tumorales, usando criterios previamente establecidos \cite{Chaux2010b,Chaux2012}. El AI trabajará bajo la supervisión del IP para la correcta clasificación de las lesiones tumorales y la adecuada identificación de las características histopatológicas relevantes. Esta evaluación se realizará sobre muestras tisulares teñidas con hematoxilina \& eosina.

\subsubsection{Indicador de cumplimiento}
\begin{itemize}
	\item Caracterización morfológica de los tumores incluidos en los 4 TMA, incluyendo subtipo histológicos y grado histológico
\end{itemize}

\subsubsection{Meta mínima}
\begin{itemize}
	\item Identificación de los campos tumorales en los 4 TMA
\end{itemize}

\subsubsection{Medios de verificación}
\begin{itemize}
	\item Láminas histológicas, microfotografías de los campos TMA (H\&E), base de datos (parcial) y libro de código en repositorio
\end{itemize}

\subsubsection{Riesgos}
\begin{itemize}
	\item Tejido insuficiente para diagnóstico anatomopatológico apropiado
\end{itemize}

\subsubsection{Cronograma}
\begin{itemize}
	\item Julio 2015 -- Agosto 2015
\end{itemize}

\subsection{Evaluación de microarrays tisulares}
\subsubsection{Descripción}
Una vez que todas las lesiones tumorales hayan sido clasificadas se procederá a la evaluación visual de la expresión inmunohistoquímica de proteínas relacionadas con el ciclo celular, incluyendo p53, cyclin D1, Ki-67, p16INK4a, y MDM2. Esta evaluación se llevará a cabo en un microscopio Zeiss AxioLab 2. El AI estimará visualmente los niveles de expresión utilizando una escala semicuantitativa previamente desarrollada y  validada \cite{Chaux2013b}. Esta estimación será controlada por el IP.

Tras la evaluación visual se procederá a digitalizar los TMA, utilizando una técnica previamente descrita \cite{Chaux2014a}. Posteriormente se procederá al análisis de las imágenes utilizando un protocolo de análisis digital previamente desarrollado y publicado por el IP
\cite{Chaux2013a}. El AI trabajará activamente en la redacción de nuevos protocolos de análisis digital y en la programación de algoritmos para mejorar los protocolos ya existentes.

\subsubsection{Indicador de cumplimiento}
\begin{itemize}
	\item Medición de niveles de expresión inmunohistoquímica mediante evaluación visual y evaluación digital, en cada uno de los 112 casos, por cada una de las proteínas estudiadas
\end{itemize}

\subsubsection{Meta mínima}
\begin{itemize}
	\item Medición de niveles de expresión inmunohistoquímica de p53 y p16INK4a mediante evaluación visual y evaluación digital
\end{itemize}

\subsubsection{Medios de verificación}
\begin{itemize}
	\item Microfotografías de los campos de TMA (inmunohistoquímica), base de datos (parcial) y libro de código en repositorio
\end{itemize}

\subsubsection{Riesgos}
\begin{itemize}
	\item Protocolo de evaluación digital de la expresión inmunohistoquímica con calibración inadecuada
\end{itemize}

\subsubsection{Cronograma}
\begin{itemize}
	\item Septiembre 2015 -- Diciembre 2015
\end{itemize}

\subsection{Confección de la base de datos}
Tras la recolección de datos visuales y digitales el AI confeccionará una base de datos en la que consignará toda la información recolectada hasta el momento, incluyendo los datos histopatológicos y la evaluación visual y digital de cada uno de los casos de cáncer de pene. Dentro de nuestra consigna de libertad de información haremos que esta base de datos esté disponible gratuitamente para todos los investigadores a través de repositorios digitales internacionales.

\subsubsection{Indicador de cumplimiento}
\begin{itemize}
	\item Base de datos finalizada, incluyendo datos histopatológicos, microfotografías, y datos de medición
\end{itemize}

\subsubsection{Meta mínima}
\begin{itemize}
	\item Base de datos conteniendo información sobre p53 y p16INK4a, incluyendo datos histopatológicos, microfotografías, y datos de medición
\end{itemize}

\subsubsection{Medios de verificación}
\begin{itemize}
	\item Microfotografías de los campos de TMA (H\&E, inmunohistoquímica), base de datos (completa) y libro de código en repositorio
\end{itemize}

\subsubsection{Riesgos}
\begin{itemize}
	\item Base de datos incompleta con datos/casos perdidos en número suficiente como para comprometer la calidad del análisis
\end{itemize}

\subsubsection{Cronograma}
\begin{itemize}
	\item Enero 2016 -- Febrero 2016
\end{itemize}

\subsection{Análisis estadístico}
El AI procederá al análisis estadístico de los datos bajo la supervisión del IP. El análisis de datos se realizará utilizando el lenguaje de programación R \cite{RCoreTeam}. El AI aprenderá las habilidades necesarias para la programación en R y la utilización de RStudio como interfaz de usuario. Se espera además que el AI adquiera conceptos y habilidades para la aplicación de técnicas estadísticas avanzadas, centradas principalmente en la construcción de modelos matemáticos predictivos. Asimismo, dentro de nuestra política de investigación reproducible, el AI utilizará GitHub (\url{https://github.com/}) para publicar el código de su análisis estadístico, y pondrá a disposición de la comunidad científica global sus resultados a través de repositorios digitales internacionales.

\subsubsection{Indicador de cumplimiento}
\begin{itemize}
	\item Análisis de datos concluido, incluyendo el protocolo detallado de análisis de datos y los modelos estadísticos utilizados
\end{itemize}

\subsubsection{Meta mínima}
\begin{itemize}
	\item Análisis descriptivo de datos concluido
\end{itemize}

\subsubsection{Medios de verificación}
\begin{itemize}
	\item Resultados del análisis de datos y el código en R utilizado publicado en un repositorio internacional
\end{itemize}

\subsubsection{Riesgos}
\begin{itemize}
	\item Modelos estadísticos inconsistentes
\end{itemize}

\subsubsection{Cronograma}
\begin{itemize}
	\item Marzo 2016 -- Abril 2016
\end{itemize}

\subsection{Redacción de informes de investigación}
Como fase final el AI redactará el informe de investigación reportando los resultados del proyecto. Este informe se enviará para publicación en una revista internacional indexada con evaluación por pares. El AI redactará además todos los materiales para ser utilizados en simposios, congresos, talleres, y conferencias en las cuales se divulguen los hallazgos del proyecto. El IP supervisará todo el proceso de redacción.

\subsubsection{Indicador de cumplimiento}
\begin{itemize}
	\item Informe de investigación finalizado, enviado para evaluación y publicado. Divulgación de los resultados de la investigación a la comunidad académica
\end{itemize}

\subsubsection{Meta mínima}
\begin{itemize}
	\item Informe de investigación finalizado
\end{itemize}

\subsubsection{Medios de verificación}
\begin{itemize}
	\item Artículo publicado en una revista internacional indexada. Documentación (certificados, fotografías, videos) del trabajo presentado en eventos científicos
\end{itemize}

\subsubsection{Supuestos/riesgos}
\begin{itemize}
	\item Artículo no finalizado o rechazado para publicación
\end{itemize}

\subsubsection{Cronograma}
\begin{itemize}
	\item Mayo 2016 -- Junio 2016
\end{itemize}

\section{Relevancia}
\subsection{Relevancia social}
La implementación de este proyecto sobre ``Evaluación de las proteínas del ciclo celular en el cáncer de pene'' permitirá obtener un conocimiento más acabado y preciso acerca de la biología molecular del cáncer. Este proyecto ayudará no sólo a comprender mejor cómo se origina y progresa la enfermedad sino también dará pistas acerca de cómo ofrecer mejores opciones terapéuticas a los pacientes afectos. Considerando que el Paraguay es uno de los países con la incidencia más alta de cáncer de pene en el mundo, la importancia social de este conocimiento es evidente. Más aún, considerando que las muestras de tejido tumoral corresponden a pacientes paraguayos, esto permitirá que los resultados sean aplicables directamente a los pacientes afectos, ya que no se trataría de información importada o llevada a cabo en otras poblaciones.

\subsection{Relevancia científica}
Debido a la rareza del cáncer de pene en países desarrollados el conocimiento disponible acerca de su biología molecular es escaso. Este proyecto sobre la ``Evaluación de las proteínas del ciclo celular en el cáncer de pene'' permitirá estudiar los niveles de expresión inmunohistoquímica de proteínas relacionadas al ciclo celular, investigando alteraciones metabólicas en células tumorales y evaluando su asociación con características histopatológicas y virales. Todo esto permitirá incrementar el conocimiento científico disponible acerca de la enfermedad. Además, este proyecto permitirá continuar con nuestra línea de investigación en el cáncer de pene, dentro de un programa de iniciación científica, ofreciendo un entrenamiento formal en ciencia de datos e incrementando por lo tanto el capital humano disponible para realizar investigación.

\subsection{Relevancia contemporánea}
El conocimiento puramente morfológico o clínico ya no es suficiente hoy en día para comprender una enfermedad, mucho menos para su adecuado diagnóstico y tratamiento. Actualmente se requiere un conocimiento más profundo acerca de la biología molecular de las enfermedades, buscando mejores modelos teóricos mediante los cuales desarrollar estrategias más efectivas para el manejo de los pacientes. Dentro de esta línea, este proyecto sobre la ``Evaluación de las proteínas del ciclo celular en el cáncer de pene'' evaluará uno de los aspectos más importantes de la biología molecular del cáncer, el control del ciclo celular.

\section{Estrategia de divulgación}
Este proyecto acerca de la ``Evaluación de las proteínas del ciclo celular en el cáncer de pene'' incrementará el conocimiento que se tiene acerca de la biología molecular del cáncer de pene. Este proyecto permitirá una mejor comprensión de la relación existente entre las características morfológicas y virales de las células tumorales y el control del ciclo celular. Mediante esto, este proyecto permitirá evaluar y validar estudios similares que se han o se están llevando a cabo centrados en el área de investigación del cáncer de pene. Todos estos resultados serán puestos a disposición de la comunidad científica nacional e internacional y del público en general interesado de manera abierta y gratuita.

Se buscará la difusión de los resultados de esta investigación mediante canales académicos y no académicos. En el ámbito académico, los resultados se divulgarán mediante Congresos y Simposios, ya sea organizados por la Universidad del Norte u otras instituciones académicas, y el reporte de investigación final será enviado para publicación a una revista científica internacional indexada evaluada por pares y con opción de acceso libre al artículo publicado. En el ámbito no académico, estos resultados se divulgarán al público en general mediante entrevistas radiales y televisivas, además de medios impresos y digitales, y redes sociales.

\bibliographystyle{unsrt}
\bibliography{Bibliografia}

\end{document}





