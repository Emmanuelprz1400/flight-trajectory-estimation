# Montecarlo MCMC

Lo que se realizo en este proyecto fue inspirado en el trabajo [Aviation-Security](https://github.com/Iliasx18/Aviation-Security) que a su vez toma como referencia al artículo de Paielli y Erzberg [Conflict probabilty estimation for free flight](https://arc.aiaa.org/doi/10.2514/2.4081).

Cabe mencionar, que para este proyecto no se cuenta con un corpus, ya que es muy complicado contar con una base de datos suficientemente numerosa, esto podría estar relacionado con la gran cantidad de variables que hacen ver pequeña a nuestra base de datos. En este proyecto utilizaremos el método de Monte Carlo para Cadenas de Markov para solucionar esta dificultad.

Simulamos las posibles trayectorias que pudieran tener los aviones y encontrar la probabilidad de conflicto entre ellas (que exista una intersección).  

## KPIs obtenidos:
Considerando un *nivel de confianza* = 0.95 y para un *tamaño de muestra* de n = 960364, obtenemos que:

  * *Probabilidad de colisión* es de 6.247631106538771e-06
  * *Margen de error* es de 0.0010000003671386069

