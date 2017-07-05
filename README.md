# Repositorio de archivos del proyecto de minería de secuencias

Este repositorio es de archivos utilizados para aplicar algoritmos de minería de secuencias, que forma parte de un trabajo de investigación que se desarrolla en el marco de una tesis de posgrado de la carrera Maestría en “Ingeniería de Software” de la Universidad Nacional de San Luis.
El conjunto de datos a minar (dataset) son datos de exámenes rendidos de las cátedras pertenecientes al Ciclo Común de Articulación -CCA, de las carreras de Ingeniería de la Facultad de Tecnología y Ciencias Aplicadas de la Universidad Nacional de Catamarca.
Al dataset se ha aplicado el algoritmo SPADE de Mohammed J. Zaki y el algoritmo propuesto por Yu Hirate y Hayato Yamana "Minería de patrones secuenciales generalizada con intervalos de ítems"
Los algoritmos utilizados se encuentran codificados en el proyecto open-source "SPMF" de Philippe Fournier-Viger.

## Archivos del repositorio


  - dataset.csv = dataset de todas los exámenes rendidos para analizar

**Hirate-Yamana**
  - dateset_rendimiento_BAJO.txt = subconjunto de dataset.csv con alumnos que poseen de 1 a 5 exámenes rendidos solamente. 
  - dateset_rendimiento_BUENO.txt = subconjunto de dataset.csv con alumnos que poseen de 6 a 8 exámenes rendidos solamente
  - dateset_rendimiento_REGULAR.txt = subconjunto de dataset.csv con alumnos que poseen de 9 a 11 exámenes rendidos solamente
  
Resultado:
  - HirateYamana_rendimiento_BAJO.txt
  - HirateYamana_rendimiento_BUENO.txt
  - HirateYamana_rendimiento_REGULAR.txt


**SPADE**
   - dateset_rendimiento_BAJO.txt = subconjunto de dataset.csv con alumnos que poseen de 1 a 5 exámenes rendidos solamente
  - dateset_rendimiento_BUENO.txt = subconjunto de dataset.csv con alumnos que poseen de 6 a 8 exámenes rendidos solamente
  - dateset_rendimiento_REGULAR.txt = subconjunto de dataset.csv con alumnos que poseen de 9 a 11 exámenes rendidos solamente
 
Resultado:
  - spade_rendimiento_BAJO.txt
  - spade_rendimiento_BUENO.txt
  - spade_rendimiento_REGULAR.txt

