# Botones de Emergencia

El programa “botones de emergencia” al recibir una señal de uno de los botones (policía, bomberos y ambulancia), analiza la información de cámaras del sector (se ocupan dos matrices en nuestro caso), se recolecta información según el tipo de emergencia, según estos datos se decide si es una emergencia verdadera o, falsa en el caso de ser falsa un moderador humano va a poder dar un último análisis y decidir si es o no emergencia, en caso de ser una emergencia real se dará aviso a las autoridades pertinentes, además se le enviaran los datos registrados para un mejor desempeño en su labor y se guardarán en una base de datos y con esto se termina la ejecución.

## funcionamiento

Este programa es para solicitar ayuda, ya sea para llamar a la policía, bomberos o ambulancia, dependiendo del tipo de situación que se presente. A su vez estudia las situaciones que en este código son simuladas por dos matrices, la primera está predefinida y la segunda está hecha pseudo-azar. Cada botón (elección) tiene tres matrices, donde dos de ellas tienen el número de emergencia dentro de ella y la otra no (si la primera matriz por ejemplo tiene un {1,3,3} de forma horizontal o vertical se asume que hay emergencia). Esto se hizo así para aumentar la posibilidad que se cumpla la condición de que sea emergencia, de otra manera sería complicado que tuviéramos un caso al azar. 

Algunas posiciones de las matrices tiene algún significado (cantidad de personas, armas, etc.). Después de eso se promedian estos valores y se le da aviso. Si el programa no encuentra una emergencia pasa hacia un moderador que analiza los datos crudos y determina si es o no emergencia de manera manual. Este proceso termina decidiendo si se da el aviso o no a las autoridades correspondientes. Después de dar el aviso, la información procesada, se guarda (se imprime por pantalla y se almacena en una base de datos) un reporte general, que cuenta con la información cruda y datos relevantes según la situación



## Análisis de matrices

![Análisis de matrices](https://i.imgur.com/Fj2MFVi.png)

## Autores

* Jose A. Mena Olave. (j.mena03@ufromail.cl)
* Andrés I. Carrasco Inostroza. (a.carrasco12@ufromail.cl)
* Cristopher A. Almonacid Castillo. (c.almonacid03@ufromail.cl)
* Roberto C. Quintana Canio. (r.quintana06@ufromail.cl)


## License
[MIT](https://choosealicense.com/licenses/mit/)
