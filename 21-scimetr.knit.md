# El paquete scimetr {#scimetr}




Package `scimetr` implements tools for quantitative research in scientometrics and bibliometrics. 
It provides routines for importing bibliographic data from Thomson Reuters' Web of Science (http://www.webofknowledge.com) and performing bibliometric analysis. For more information visit https://rubenfcasal.github.io/scimetr/articles/scimetr.html. 


Instalaci�n
-----------

Para instalar el paquete ser�a recomendable en primer lugar instalar las dependencias:


```r
install.packages(c('dplyr', 'lazyeval', 'stringr', 'ggplot2', 'openxlsx', 'tidyr'))
```

Como de momento no est� disponible en CRAN, 
habr�a que instalar la versi�n de desarrollo en GitHub.
En Windows bastar�a con instalar la versi�n binaria del paquete *scimetr_X.Y.Z.zip*
(disponible [aqui](https://github.com/rubenfcasal/scimetr/tree/master/docs)), 
alternativamente se puede instalar directamente de GitHub:

```r
# install.packages("devtools")
devtools::install_github("rubenfcasal/scimetr")
```

Una vez instalado ya podr�amos cargar el paquete:








































