# Virus SARS-CoV-2 un análisis profundo

A finales de 2019 la ciudad de Wuhan, en la provincia de Hubei (una ciudad de China con más de 11 millones de habitantes), se convirtió en el centro de una epidemia de neumonía de causa desconocida con implicaciones globales.

Se sabe que las pruebas serológicas son una herramienta muy útil para confirmar la infección por un patógeno en la población y, combinadas con datos epidemiológicos y clínicos, permiten estimar la gravedad y la transmisibilidad del patógeno e identificar los grupos de población que han sido infectados, así como aquellos que siguen siendo susceptibles.  Por ello, cada vez más requerimos datos moleculares como las secuencias de ácidos nucleicos de los virus para conocer su origen y potencialidad epidemiológica.

![image](https://github.com/user-attachments/assets/03fb5207-2c9e-4ccc-831a-2e860812335d)

# Descripción del Proyecto
El estudio se centra en la comparación de secuencias genómicas de coronavirus en nueve especies, incluyendo la variante original del SARS-CoV-2 de Wuhan. Se obtuvieron datos del NCBI para analizar sus similitudes y diferencias mediante técnicas de alineamiento y visualización de datos.

Las especies analizadas incluyen:

Humano (SARS-CoV-2, Wuhan-HU-1)
Murciélago (RaTG13, BANAL-20-52, BANAL-20-247, RacCS203)
Pangolín (MP789)
Felino (FCoV C1Je)
Porcino (HKU15 - MI6148, HKU15 - NE3579)
Ganso (Cambridge_Bay_2017)
Se llevaron a cabo análisis filogenéticos y cálculos de similitudes para determinar las relaciones evolutivas entre estas variantes.

Metodología
El análisis se realizó utilizando R con las librerías:

seqinr
msa
Biostrings
ggplot2
Pasos del análisis:
Carga y procesamiento de secuencias en formato FASTA.
Cálculo de la longitud de cada secuencia.
Comparación de la composición de bases (A, C, G, T) entre las diferentes variantes.
Generación de un árbol filogenético para visualizar la cercanía evolutiva de los virus.
Interpretación de los resultados en términos de epidemiología y evolución del virus.
Resultados
Los datos obtenidos muestran una alta similitud genética entre el SARS-CoV-2 y ciertos coronavirus de murciélago y pangolín, lo que sugiere un posible origen zoonótico. Además, se detectaron pequeñas variaciones en la composición genética entre especies, lo que podría influir en la transmisibilidad y patogenicidad del virus.
