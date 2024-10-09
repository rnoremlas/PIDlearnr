# PIDlearnr

Prueba para crear un paquete con tutoriales hechos con *learnr* y compartirlo en GitHub. Este paquete contiene dos tutoriales: *TC1learnr* y *TC2learnr*.

Para instalar el paquete desde GitHub hay que usar el paquete *remotes*:

> install.packages("remotes")
> 
> library(remotes)
> 
> remotes::install_github("rnoremlas/PIDlearnr")

Para usar los dos tutoriales que vienen en el paquete has de usar el paquete *learnr*:

> install.packages("learnr") 
> library(learnr)
> learnr::run_tutorial("TC1learnr", package= "PIDlearnr")
> learnr::run_tutorial("TC2learnr", package= "PIDlearnr")

¡¡Espero que este paquete sea de tu interés!!
