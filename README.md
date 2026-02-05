# README.md
## Notas vista en clase de "Teoria de algoritmos" 

Las clases que hemos tenido con el Dc.Villarroel han sido muy divertidas e interesantes, sobre todo ala hora de platicar y entender problemas planteadas por el, como el del agente viajero que consta de:

Un viajero debe visitar una serie de ciudades una sola vez, regresar al punto de partida y hacerlo con la menor distancia (o costo) total posible. Es un problema clásico de optimización y computación y ademas aparece en logística, rutas de reparto, planificación, circuitos electrónicos, etc.

*Dificultad*

Es un problema NP-difícil: a medida que aumenta el número de ciudades, las posibles rutas crecen muy rápido, y encontrar la mejor se vuelve computacionalmente muy costoso.

Hablando de probelmas NP, igual en clase abordamos y analizamos algunos problemas NP. Un problema está en ℕℙ si, dada una solución candidata, esta puede verificarse en tiempo:

Resolver puede ser difícil, pero verificar es fácil.

Ejemplos:

-Problema del Agente Viajero (TSP)
-Satisfacibilidad Booleana (SAT)
-Coloreo de grafos

*Relación entre P y NP*
P⊆NP

Esto significa que todo problema en P también pertenece a NP

Pero no se sabe si:
P=NP?
Este es uno de los problemas abiertos más importantes de la informática.

*Problemas NP-Completo*

Un problema es NP-Completo si cumple

-Está en ℕℙ
-Es tan difícil como cualquier otro problema en ℕℙ
-Implicación clave
-Si un solo problema NP-Completo se resuelve en tiempo polinomial:
⇒P=NP

*Ejemplos clásicos*

-SAT
-TSP (versión de decisión)
-3-SAT
-Clique

Estos solo son algunos de los problemas clasicos, de manera muy resumida

$$P=frac[A][B]$$
$$N=NP$$
