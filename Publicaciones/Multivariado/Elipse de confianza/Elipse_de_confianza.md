
¿Cómo se construye una elipse de confianza para una normal bivariada?
=====================================================================

Vamos a definir el vector de medias **μ** y la matriz de covarianzas **Σ** así:

``` r
centro <- c(70, 170)
Sigma <- matrix(c(20, 100,
                  100, 1000), ncol=2, nrow=2)
```
