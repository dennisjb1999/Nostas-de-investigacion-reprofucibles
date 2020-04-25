# Notas sobre investigacion reproducible y analisis de datos
# Reproductibilidad

El termino __reproductibilidad__ (o _reproducibility_, en ingles) se refier a la capacidad de reproducir un trabajo de investigacion de manera que sus resultados puedan ser obtenidos por otros al seguir la misma metodologia .
Usualmente, la reproductibilidad requiere que los datos y el codigo de programacion utilizados en la investigacion esten disponibles para quienes deseen usarlos (Bezjak et al., 2018). Este concepto esta relacionado con el de __replicabilidad__ (o _replicability_, en ingles), el cual se refiere a la posibilidad de obtener resultados consistentes(no indenticos) al replicar un estudio con un conjunto distinto de datos, pero siguiendo el mismo diseño experimental. Estos conceptos son elementos centrales de la investigacion empirica.

# Importancia de la reproductibilidad 

¿Por que es importante la investigacion reproducible? Para encontrar una respuesta, podemos estudiar sus inicios. A principios de la decada de 1990, un geofisico estadounidense llamado John claerbout realizo la siguiente afirmacion:

>"Al dia de hoy, pocos resultados publicados son reproducibles en un sentido pratico. Verificarlos requiere de tanto
> esfuerzo como el que tomo crearlos. Despuesde un tiempo incluso los autores son incapaces de reproducir sus
> propios resultados. Por esta razon, muchas personas ignoran la mayor parte de la literatura cientifica."(Claerbout,
> 1992)

Con el fin e resolver esta problematica, diferentes organizaciones, como el Comite Internacional de Publicaciones de Medicina o la Administacion de Alimentos y Medicamentos de Estados Unidos ([FDA]( https://www.fda.gov/)), empezaron a publicar lineamientos para atacar los problemas derivados de una inadecuada documentacion de los experimentos basados en ensayos aleatorios. De manera simultanea, se ledio mas importancia a la calidad de los datos utilizados en las investigaciones.
Asi, por ejemplos, como se muestra en la figura 1, Mark Ziemannencontro en 2016 que un 20% de los articulos con archivos de datos suplementarios publicados en revistas cientificas contenian errores en los nombres de los genes, debido a los paramentros de configuracion de Microsoft Excel(Ziemann et al.,2016)

![](https://geoprocesamiento-2020i.github.io/laboratorio-01-markdown/ZiemannEtAlFig1.png)

Figura 1. Resultados de la revision sistematica de archivos Excel suplementarios. Fuente:(Ziemann et al.,2016)

#Bibliografia
Bezjak, S., Clyburne-Sherin, A., Conzett, P., Fernandes, P., Görö, E., Helbig, K., Kramer, B., Labastida, I., Niemeyer, K.,
Psomopoulos, F., Ross-Hellauer, T., Schneider, R., Tennant, J., Verkabet, E., Brinket, H., & Helle, L.(2018). Open Science Training Handbook. Zenodo. http://doi.org/10.5281/ZENODO.1212496
Claerbout, J.F.(1992). Earth Soundings Analysis: Processing Versus Inversion, Blackwell Science Inc.
Ziemann, M., Eren, Y.,& El-Osta, A. (2016). Gene name errors are widespread in the scientific literatre. Genome Biology, 17(1), 177. https://doi.org/10.1186/s13059-0161044-7
