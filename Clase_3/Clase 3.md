Clase 3
========================================================
author: Erick Cuevas Fernández
date: 05 septiembre 2019
autosize: true

Análisis exploratorio de datos
========================================================
*Paso 1. Conocer estructura de datos*

*Paso 2. Obtener y leer datos*

**Paso 3. ¿Qué me dicen mis datos?**


```r
# devtools::install_github("Erickcufe/seekerBio")

# cocaine <- seekerBio::seeker_gwas("Cocaine")

# write.csv(cocaine, "Clase_3/Cocaine.csv")

# paths <- seekerBio::seeker_gen_pathway(cocaine$GeneSymbol)

# write.csv(paths, "Clase_3/Paths_cocaine.csv")

# Freq <- seekerBio::seeker_snp_freq(cocaine$SNPS)

# write.csv(Freq, "Clase_3/Freq_cocaine.csv")
```

Para afianzar lo aprendido en la clase anterior:

- Lee/carga el archivo *Cocaine.csv*
- Lee/carga el archivo *Paths_cocaine.csv*
- Lee/carga el archivo *Freq_cocaine.csv*


Para calentar motores...  Missing Values
========================================================
Un vistazo a los datos




```
Error in file(file, "rt") : cannot open the connection
```