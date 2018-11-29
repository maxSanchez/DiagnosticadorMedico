# Diagnosticador médico en español
Este proyecto propone un sistema que analiza los textos relacionados con una enfermedad, los cuales pueden ser los síntomas de ésta (este caso), y predice según un texto del usuario describiendo los síntomas, cual es la enfermedad cuya descripción se aproxima más.
# Corpus
Los corpus fueron obtenidos de páginas donde describian los síntomas de las enfermedades, fue posible obtener hasta 491 enfermedades con sus sintomas (última versión en Experimento4/datosLimpios.csv) los métodos que se usaron fueron Gensim, tf-idf y los embedding del corpus BWS (http://crscardellino.github.io/SBWCE/)
# Conclusiones
En general los experimentos fueron exítosos, sin embargo algo que se puede notar es que es necesario describir extensamente cuales son los síntomas que se tienen, una descripción de una 50 o más palabras es lo mejor, además que el sistema no reconoce cuales son las enfermedades que son más comunes, por lo que le parecerá igual de común una gripe o un cancer. Me parece importante aclarar que este proyecto es puramente académico y que su uso debe ser discreto y sin confiar mucho en los resultados, ya que no es un producto final, sino un experimento.