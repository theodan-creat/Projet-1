# Projet-1
> factorielle <- function(n) {
+   indice <- (n == 1)
+   if (all(indice)) return(n) # arrêt de la récursion
+   n[!indice] <- n[!indice]*factorielle(n[!indice] - 1) # appel récursif
+   return(n)
+ }
