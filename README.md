
# IIC2562 - Taller de Programacion II
## 2018-2
Bienvenidos a la página de apoyo del curso Taller de Programacion II.

# Instrucciones del Curso

Este es un curso 100% práctico, orientado a entrenar a alumnos en [programación competitiva](https://es.wikipedia.org/wiki/Usuario:Ltaravilse/Programaci%C3%B3n_competitiva) y preparar equipos que participen en la [ACM ICPC](https://en.wikipedia.org/wiki/ACM_International_Collegiate_Programming_Contest) (celebrada anualmente) representando a la universidad. Por lo tanto, la nota final dependerá de la resolución por parte del alumno de problemas de programación competitiva. Cada cierto tiempo (una vez cada 1 o 2 semanas) se publicará un *contest* (o competencia, en español). Los contests se caracterizan por lo siguiente:

* Se publicarán en [codepit.io](https://www.codepit.io/), un sitio web brasileño (sí, casi todo está en portugués) que permite crear competencias utilizando problemas obtenidos de diferentes jueces online (los enunciados de estos problemas están _casi_ siempre en inglés eso sí), con un scoreboard que se actualiza en tiempo real a medida que los participantes resuelven problemas. Para competir sólo basta con crearse una cuenta en [codepet.io](https://www.codepit.io/) y posteriormente unirse a los contests a medida que estos vayan siendo publicados.
* Las competencias pueden ser ya sea **individuales** o **grupales**.
* En el caso de competencias grupales, les está permitido armar grupos de un máximo de 3 alumn@s (codepit.io permite hacer esto fácilmente).
* Cada contest tiene su propia **exigencia _default_**, es decir, un número **mínimo** de problemas a resolver (el cual puede ser diferente para cada contest). Sin embargo, si el alumno **asiste a clases**, se le restará 1 problema a su exigencia en el contest correspondiente, obteniéndose así una **exigencia personalizada**. Por ejemplo, si un contest tiene una duración de 3 semanas con una exigencia default de X problemas, y supongamos que 2 clases están asociadas a dicho contest, si un alumno asiste a ambas clases entonces obtendrá una exigencia personalizada de (X-2), mientra que si sólo asiste a una clase será de (X-1), y si no asiste a ninguna tendrá una exigencia de X.
* Cada contest tendrá una duración oficial máxima (generalmente 2 o 3 semanas). El alumno (o grupo de alumnos) tendrá dicho plazo para resolver los problemas del contest. Sean N los problemas resueltos por el alumno (o grupo de alumnos) y Xp la exigencia personalizada de un alumno "p". Según la cantidad de problemas resueltos, se generan dos posibles sub-casos:
  * Si N >= Xp, dicho alumno obtiene una asistencia de 100% en dicho contest. Además, todos los problemas adicionales resueltos (N - Xp) se sumarán a un contador llamado **excedente total**.
  * Si N < Xp, dicho alumno obtiene una asistencia de 100 * (Xp / N) % en dicho contest. Además, todos los problemas que le faltaron (Xp - N) se sumarán a un contador llamado **deuda total**.
* En codepit.io, cuando el plazo de un contest se acaba, los participantes pueden seguir enviando soluciones en un modo post-competencia conocido como **upsolving**. Todos los problemas resueltos en modo upsolving se agregarán a un contador llamado **total upsolving Codepit**.

Además de estos contests, existen otras 3 formas adicionales de obtener bonus para mejorar su nota final:
* __BONUS RPC__ (grupal): Cada cierto tiempo la [Red de Programación Competitiva (RPC)](http://redprogramacioncompetitiva.com/) organiza competencias de entrenamiento. El calendario y registro para estas competencias se encuentran acá: http://registro.redprogramacioncompetitiva.com/contests, y los scoreboards de las competencias pasadas se pueden encontrar acá: http://redprogramacioncompetitiva.com/Contest. Nótese que se trata de un **bonus grupal**, por ende para obtener este bonus deben:
  * Registrarse en grupos de 2 o 3 alumnos.
  * Mandar una foto del grupo con todos sus integrantes juntos frente a un mismo computador (sí, la idea es que se junten físicamente usando un solo computador, como en la competencia real).
  * Mandar el link al scoreboard final de la competencia RPC en que participaron.
  * El bonus se calculará como 6 * (X/N) décimas, donde X = problemas resueltos por el grupo, N = problemas resueltos por el equipo que quedó en primer lugar. Las 6 * (X/N) décimas obtenidas se sumarán directamente a su nota final.
  * __\*\*EXTRA__: las RPCs tienen un modo _post-maratón_ (lo mismo que el _upsolving_ de codepit.io), así que si los alumnos lo desean pueden seguir resolviendo problemas en este modo, avisarnos, y estos problemas se les sumarán a un contador llamado **total upsolving RPC**.

* __BONUS Codeforces__ (individual): Cada cierto tiempo [Codeforces](http://codeforces.com/) organiza competencias individuales, que generalmente duran alrededor de 2 horas, con problemas de diferentes niveles de dificultad. Si se registran en Codeforces, el sitio les debería ir avisando por email sobre las próximas competencias. Alternativamente, pueden revisar el [siguiente calendario](http://codeforces.com/calendar) o bien utilizar [esta página](https://clist.by/) y en el search box tipear "codeforces". Para obtener este bonus deben:
  * Registrarse en Codeforces.
  * Participar en una competencia.
  * Al final de la competencia avisarnos en qué competencia participaron (por ej. mandar el link a su perfil de Codeforces).
  * El bonus se calculará como 3 * (X/N) décimas, donde X = problemas resueltos por el alumno, N = problemas resueltos por la persona que quedó en primer lugar. Las 3 * (X/N) décimas obtenidas se sumarán directamente a su nota final.
  * __\*\*EXTRA__: al finalizar la competencia, si quedaron con ganas de resolver problemas que no alcanzaron a resolver durante la competencia, pueden hacerlo, avisarnos, y estos problemas se les sumarán a un contador llamado **total upsolving Codeforces**.

* __BONUS Regional__ (grupal): Cada año las universidades mandan sus mejores equipos para participar en las competencias regionales de la ACM ICPC. Sólo los mejores equipos en cada región logran clasificar a las ACM ICPC World Finals. La PUC no es una excepción así que seleccionaremos los mejores 3 equipos (cada equipo con 3 alumnos) que nos representarán en la regional, la cual este año se llevará a cabo el 10 de Noviembre en la Universidad Austral de Chile, Valdivia. ¿Cómo obtener este bonus?
  * Deben ser parte de alguno de los 3 mejores equipos seleccionados para representar a la PUC en la regional.
  * El bonus se calculará como 10 * (X/N) décimas, donde X = problemas resueltos por el equipo, N = problemas resueltos por el equipo que quedó en primer lugar. Las 10 * (X/N) décimas obtenidas se sumarán directamente a su nota final.

#### Cálculo de la Nota Final
La nota final se calcula calculando muchas cosas:
* El promedio de la asistencia de todos los contests (llamémoslo X).
* En caso de que X < 100%, el porcentaje que les falte (100% - X) lo pueden recuperar "reduciendo" su *deuda total* de problemas (llamémosla D). Para esto se hará el siguiente update:
   * D := deuda total de problemas
   * K := X * (excedente total + total upsolving Codepit + total upsolving RPC + total upsolving Codeforces)
      * nótese que la sumatoria anterior es "penalizada" por la asistencia promedio (i.e. vale más resolver problemas dentro de plazo que fuera de plazo).
   * D_reducido = max {D - K, 0}
   * X_aumentado = X + (1 - X) * ((D - D_reducido) / D)
* Así se puede calcular su nota:
   * Nota = 1 + 6 * X_aumentado
* Sin embargo, luego se bajará la escala del curso, donde el alumno con mayor asistencia quedará con nota 7 (siempre y cuando la escala baje "poco" - i.e. habrá un límite para bajar la escala).
   * Nota_v2 = aplicar_escala_reducida(Nota)
* Finalmente, se aplicarán las décimas de bonus:
   * Nota_v3 = Nota_v2 + BONUS RPC + BONUS Codeforces + BONUS Regional

### Seguimiento de Asistencia y Problemas Resueltos:
Todo lo anterior se encuentra formalizado en el siguiente google spreadsheet:
https://docs.google.com/spreadsheets/d/1wm2jleZBV_M8V6FbTBpKfcI4uzNTg9ReMvnjq21LBXY/edit?usp=sharing

### IMPORTANTE: mensaje para los alumnos nuevos
El nivel de dificultad de los problemas en las regionales ICPC es bien alto, y por lo tanto un buen entrenamiento requiere que los alumnos sean expuestos a problemas de ese nivel. Sin embargo, entendemos que tirar a los alumnos nuevos "a los leones" de golpe puede ser un poco traumático. Por lo tanto, para los primeros 3 contests tendremos dos divisiones: división 1 (más difícil) y división 2 (más fácil). Los alumnos nuevos pueden optar por participar en la división 2 si así lo desean.

### IMPORTANTE: sobre lenguajes de programación
En programación competitiva el lenguaje más utilizado por lejos es C++ (y dentro de C++ generalmente se usa de C++11 para arriba). En segundo lugar se encuentra Java. [Y hace muy poco se comenzó a utilizar también Python](https://www.quora.com/Can-Python-be-used-in-ACM-ICPC). Sin embargo, lamentablemente la mayoría de los jueces online (los servidores que tienen los enunciados de los problemas y ejecutan los códigos enviados por la gente) generalmente están calibrados para aceptar soluciones en C++ y a veces Java, y pasa mucho que las soluciones en Python fallan con el famoso Time Limit Exceeded (TLE), ya que Python de por sí es un lenguaje interpretado que se demora mucho más en ejecutar que lenguajes compilados a código de máquina como C++. Además, la mayoría de los códigos de ejemplo disponibles en internet para progcomp están en C++ o quizá Java. Dado lo anterior, el consejo típico es aprender C++. A los alumnos nuevos que quieran seguir este consejo, les recomendamos aprovechar los primeros 3 contests en división 2 para aprender a programar en C++. Más abajo pueden encontrar harto material de estudio al respecto.

### IMPORTANTE: tips generales parar resolver problemas
 - En C++, en general pueden hacer un poco más de **10^8 operaciones por segundo** (una estimación bien al ojo por experiencia con diferentes jueces online).
 - Siempre estimen la [**complejidad computacional**](https://en.wikipedia.org/wiki/Time_complexity) de su algoritmo y **evalúenla con el caso de prueba más grande** (peor caso). Por ejemplo, si un problema depende de N donde 1 <= N <= 10^5 y mi algoritmo es cuadrático (complejidad = O(N^2)), entonces en el peor caso haré (10^5)^2 = 10^10 operaciones, y por ende según el punto anterior necesitaría **100 segundos** para correrlo. En cambio, si mi algoritmo tiene complejidad O(N\*log(N)) entonces en el peor caso sólo haré 10^5 * log(10^5) = 1.7 * 10^6 operaciones (aprox.), y por ende sólo necesitaría **0.017 segundos** (la nada misma) para correrlo. Entonces, si mi problema tiene un tiempo máximo de ejecución de 2 segundos, ¿qué algoritmo va a funcionar? Claramente el segundo.
 - Si van a usar mucha memoria, preocúpense de **no pasarse del límite de memoria permitido**. Por ejemplo si les dan 256MB de memoria, en bytes eso es 256 * 1024 * 1024 = 268435456 bytes, un int32 ocupa 4 bytes, así que como máximo podrían crear un arreglo de int32 de largo 67108864 = 6.7 * 10^7 aprox (o la mitad si usan un int64, un double, etc.). También podría acabárseles la memoria si hacen demasiadas llamadas recursivas [[1](https://codeforces.com/blog/entry/47003), [2](https://stackoverflow.com/a/11777585/2801404)].

### IMPORTANTE: sobre ética
En este curso está totalmente permitido buscar en internet material, explicaciones e incluso ejemplos de soluciones de problemas. Tienen todo el internet a su disposición. Las únicas reglas que deben cumplir son:
1) no buscar explicaciones / soluciones de problemas **a menos que ya estén rendidos intelectualmente**
2) **nunca hacer copy-paste de soluciones ajenas**, sino que deben **entender** la solución (teoría + implementación) y ser capaces de programar dicha solución por ustedes mismos después (la idea es que aprendan, si hacen copy-paste no van a estar aprendiendo nada)
 
_________________________________

# Material de Apoyo

### General
* Canales de Youtube con muchas explicaciones:
  * Algorithms Live!: https://www.youtube.com/channel/UCBLr7ISa_YDy5qeATupf26w/
  * Tushar Roy - Coding Made Simple: https://www.youtube.com/channel/UCZLJf_R2sWyUtXSKiKlyvAw
  * Programación Competitiva CL:  https://www.youtube.com/channel/UCmVg7YyMS8H-65WCmkVHB9g/feed
* Repositorios con muchos códigos de ejemplo (implementaciones de algoritmos y estructuras de datos típicos):
  * C++ Cheat Sheet for ACM ICPC : https://github.com/ntuorangejuice/cheat-sheet
  * Stanford University ICPC Team Notebook: https://cs.stanford.edu/group/acm/SLPC/notebook.pdf
  * Google Doc con muchos códigos (C++): https://docs.google.com/document/d/1rcex_saP4tExbbU62qGUjR3eenxOh-50i9Y45WtHkc4/edit
  * Google Doc con Apuntes de Robinson Castro et al (C++): https://docs.google.com/document/d/1pan53PU9_PIrPPVyNrbfXIAU-B6YnIaSBcB9lP9j0jE/edit  
  * Repo de Apuntes del team Caloventor en Dos (C++): https://github.com/mvpossum/eldiego
  * Repo de Apuntes de Pablo Messina (C++): https://github.com/PabloMessina/Competitive-Programming-Material
* Otras páginas con links a muchos recursos y material de estudio:
  * Codeforces: An awesome list for competitive programming!: https://codeforces.com/blog/entry/23054
     * All of the good tutorials found on codeforces: https://codeforces.com/blog/entry/57282
  * Standford CS 97SI: Introduction to Programming Contests: http://web.stanford.edu/class/cs97si/
  * GeeksForGeeks: HOW TO PREPARE FOR ACM ICPC: https://www.geeksforgeeks.org/how-to-prepare-for-acm-icpc/
  * GeeksForGeeks: Top 10 Algorithms and Data Structures for Competitive Programming: https://www.geeksforgeeks.org/top-algorithms-and-data-structures-for-competitive-programming/
  * Sitio web del Taller de la U. de Chile: http://progcomp.cl/taller
  * Techie Delight: Coding made easy: http://www.techiedelight.com/  
  * Material Campamento 2015 progcomp.cl: http://campamento2015.progcomp.cl/material
  * Material Campamento 2016 progcomp.cl: http://campamento2016.progcomp.cl/material
  * Material Campamento 2017 progcomp.cl: http://campamento2017.progcomp.cl/material
  * Material Campamento 2018 progcomp.cl: http://campamento2018.progcomp.cl/material
* Libros con harto material de programación competitiva:
  * Competitive Programmer's Handbook: https://www.cses.fi/book.pdf
  * Competitive Programming 2: https://www.scribd.com/doc/155208844/Competitive-Programming-2
  * Competitive Programming 3 (CP3): https://cpbook.net/

### Soluciones de Regionales Latinoamericanas
* Blogs con explicaciones:
  * Blog CaloventorEnDos: http://caloventorendos.blogspot.cl
  * Chocoblog: https://chococontest.wordpress.com/
* Google Sheet con soluciones de las últimas regionales (work in progress): https://docs.google.com/spreadsheets/d/1F8aBV83xKPVFfq_A0EKhCa8qbjf0gKKg8puQF-rbonQ/
* Inputs y outputs oficiales de regionales latam pasadas: http://maratona.ime.usp.br/antigas18.html

### Para aprender C++ (MUY RECOMENDADO)
 * ¿Qué es mejor para leer input / imprimir output? cin/cout vs printf/scanf: http://www.cplusplus.com/forum/beginner/34165/
 * Documentación Oficial de C++: http://www.cplusplus.com/reference/ 
 * C++ Tutorial (SOLO LEARN: EVERYONE CAN CODE): https://www.sololearn.com/Course/CPlusPlus/
 * LearnCpp: http://www.learncpp.com/
 * Intro a C++: https://youtu.be/pqWsOsfGKA0
 * Intro a la Programación Competitiva en C++: https://youtu.be/zTUJFG34Tyw
 * Estructuras básicas en C++: https://youtu.be/OldL5e5eGmY
 * C++ Programming Video Tutorials For Beginners [ Complete Series ]: https://www.youtube.com/playlist?list=PLfVsf4Bjg79Cu5MYkyJ-u4SyQmMhFeC1C 
 * C++ Cheat Sheets & Tricks:
   * C++ Cheat Sheet for ACM ICPC : https://github.com/ntuorangejuice/cheat-sheet
     * Aquí pueden encontrar un C++ Solution Template (código que uno siempre escribe al comenzar una solución) + MUCHO MUCHO más :)
   * C++ STL cheatsheet for competitive programming: https://gist.github.com/satwikkansal/c959e89161cc60db16b412233177feab
   * C++ Tricks: https://codeforces.com/blog/entry/15643
   * C++ tricks for competitive programming (for C++ 11): https://www.geeksforgeeks.org/c-tricks-competitive-programming-c-11/
   * C++ Cheat Sheet de Pablo Messina: https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/c%2B%2B_cheat_sheet.cpp 
 * Instalando y corriendo C++:
   * Windows:
     * http://www.mingw.org/Welcome_to_MinGW_org
     * https://www.quora.com/How-do-I-compile-a-C++-program-on-a-Windows-PC-in-CMD
   * Ubuntu:
     * http://askubuntu.com/questions/348654/how-to-install-g-compiler
     * http://askubuntu.com/questions/61408/what-is-a-command-to-compile-and-run-c-programs
   * Mac:
     * https://www.quora.com/What-is-the-best-FREE-C-C++-compiler-for-Mac-OS
     * http://stackoverflow.com/questions/9148488/how-do-i-compile-c-with-clang
 * Ejemplo de secuencia de pasos para resolver un problema en C++ en Windows usando la terminal (en Linux/Mac es bien parecido):
    * Crear un archivo example.cpp
    * Escribir un código de C++ válido y guardar.
    * Abrir una terminal y navegar a la carpeta donde está el archivo.
    * Opción 1:
      * En la terminal, compilar y ejecutar con el comando: ```g++ -std=c++11 example.cpp && a.exe```
      * Escribir el input directamente en la terminal
      * El output irá apareciendo poco a poco en la terminal (intercalado con el input)
    * Opción 2:      
      * Crear un archivo en la carpeta donde están parados llamado input.txt, copiar y pegar el input ahí y guardar.
      * En la terminal, compilar y ejecutar con el comando: ```g++ -std=c++11 example.cpp && a.exe < input.txt```
      * el output aparecerá en la misma terminal
    * Opción 3:
      * Crear un archivo en la carpeta donde están parados llamado input.txt, copiar y pegar el input ahí y guardar.
      * En la terminal, compilar y ejecutar con el comando: ```g++ -std=c++11 example.cpp && a.exe < input.txt > output.txt```
      * el output quedará guardado en el archivo output.txt

___________________________________________
## Material para Temas Específicos

### Search:
* Binary Search:
  * https://www.youtube.com/watch?v=jf1baieXkSQ
  * https://www.tutorialspoint.com/data_structures_algorithms/binary_search_algorithm.htm
  * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Search/BinarySearch.cpp
  * http://progcomp.cl/binarysearch
* Ternary Search:
  * https://en.wikipedia.org/wiki/Ternary_search
  * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Search/TernarySearch.cpp

### Data Structures:
* Union Find (Disjoint Sets):
  * https://www.youtube.com/watch?v=ID00PMy0-vE
  * http://www.geeksforgeeks.org/union-find-algorithm-set-2-union-by-rank/
  * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Data_Structures/unionfind.cpp
* Segment Tree:
  * http://progcomp.cl/segmenttree
  * https://www.youtube.com/watch?v=ZBHKZF5w4YU
  * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Data_Structures/segment-tree.cpp
* Segment Tree Lazy: https://www.youtube.com/watch?v=xuoQdt5pHj0
* Fenwick Tree (a.k.a. BIT o Binary Indexed Tree):  
  * (recomendado) (explicación de Jorge Pérez) https://youtu.be/0PzR0IoqkkU?t=2160
    * https://youtu.be/0PzR0IoqkkU?t=1453 (por si quieren ver la explicación de **sweep line** también que viene justo antes)
  * (recomendado) https://www.youtube.com/watch?v=CWDQJGaN1gY
  * http://progcomp.cl/fenwicktree
  * https://cs.stackexchange.com/questions/10538/bit-what-is-the-intuition-behind-a-binary-indexed-tree-and-how-was-it-thought-a
  * https://www.topcoder.com/community/data-science/data-science-tutorials/binary-indexed-trees/
* Fenwick Tree 2D:
  * http://www.geeksforgeeks.org/two-dimensional-binary-indexed-tree-or-fenwick-tree/
  * (explicación de Jorge Pérez) https://youtu.be/0PzR0IoqkkU?t=4207
  * https://www.topcoder.com/community/data-science/data-science-tutorials/binary-indexed-trees/#2d
* Wavelet Tree: https://www.dcc.uchile.cl/~jperez/papers/ioiconf16.pdf

### Dynamic Programming (DP):
* ¿Qué es DP?
  * https://www.youtube.com/watch?v=OQ5jsbhAv_M  
  * https://www.youtube.com/watch?v=P8Xa2BitN3I
  * https://www.youtube.com/watch?v=P8Cm_koLdxM
* Bottom-Up vs Top-Down: http://stackoverflow.com/questions/6164629/dynamic-programming-and-memoization-bottom-up-vs-top-down-approaches
* Playlist con muchos ejemplos: https://www.youtube.com/watch?v=8LusJS5-AGo&list=PLrmLmBdmIlpsHaNTPP_jHHDx_os9ItYXr
* Optimizaciones para DP: 
  * Divide & Conquer Optimization:
    * http://jeffrey-xiao.github.io/#!/blog/posts/2015-12-14-Divide-and-Conquer-Optimization
    * https://www.hackerrank.com/contests/ioi-2014-practice-contest-2/challenges/guardians-lunatics-ioi14/editorial
    * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Dynamic_Programming/Divide%26ConquerOptimization.cpp     
    * https://www.youtube.com/watch?v=wLXEWuDWnzI
   
### Graphs:
* Slides de Nico Lehmann sobre Grafos:
  * http://campamento2015.progcomp.cl/material (revisar la parte Grafos)
  * http://campamento2016.progcomp.cl/material (revisar la parte Grafos)  
* Play list sobre Grafos: https://www.youtube.com/playlist?list=PLrmLmBdmIlpu2f2g8ltqaaCZiq6GJvl1j
* Breadth First Search (BFS) & Depth First Search (DFS):
  * https://www.youtube.com/watch?v=ImMnYq2zP4Y
  * https://www.youtube.com/watch?v=zaBhtODEL0w
* Flood Fill: https://en.wikipedia.org/wiki/Flood_fill
* Articulation Points (aka Cut Vertices), Bridges (aka Cut Edges) and Biconnected Components (aka Blocks): 
  * Graph Theory: 53. Cut-Vertices: https://www.youtube.com/watch?v=BxAgmaLWaq4
  * Graph Theory: 55. Bridges and Blocks: https://www.youtube.com/watch?v=iGsxKUzW3cs
  * Menger's Theorem: https://www.youtube.com/watch?v=dUAeleBMRCQ
    * https://www.quora.com/How-can-I-prove-without-using-Mengers-theorem-that-any-two-vertices-of-a-2-connected-graph-lie-on-a-common-cycle
  * Articulation Points Graph Algorithm: https://www.youtube.com/watch?v=2kREIkF9UAs
  * http://web.iitd.ac.in/~bspanda/biconnectedMTL776.pdf
  * https://www.hackerearth.com/practice/algorithms/graphs/articulation-points-and-bridges/tutorial/
  * https://www.hackerearth.com/practice/algorithms/graphs/biconnected-components/tutorial/
  * Código de ejemplo: https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Graphs/articulation-points%2Ccut-edges%2Cbiconnected-components.cpp
* Diameter of a Tree: http://cs.stackexchange.com/questions/22855/algorithm-to-find-diameter-of-a-tree-using-bfs-dfs-why-does-it-work
* Dijkstra:
  * https://www.youtube.com/watch?v=gdmfOwyQlcI
  * https://www-m9.ma.tum.de/graph-algorithms/spp-dijkstra/index_en.html
  * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Graphs/Dijkstra.cpp
* Minimum Spanning Tree:
  * Kruskal's Algorithm:
    * https://www.youtube.com/watch?v=71UQH7Pr9kU
    * https://www.youtube.com/watch?v=fAuF0EuZVCk
  * Prim's Algorithm:
    * https://www.youtube.com/watch?v=cplfcGZmX7I
    * https://www.youtube.com/watch?v=oP2-8ysT3QQ
  * Correcteness Proofs:
    * Proof of Cut Property: https://www.youtube.com/watch?v=P7K7mG8QDVM
    * Proof of Prim's MST algorithm using cut property: https://www.youtube.com/watch?v=UfhUr5QzfiI
    * Correctness of Kruskal's Algorithm: https://www.youtube.com/watch?v=S9PIItOUyzA
  * Example Code: https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Graphs/MinimumSpanningTree.cpp    
* Topological Sort:
  * https://www.youtube.com/watch?v=ddTC4Zovtbc
  * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Graphs/TopoSort.cpp
* Lowest Common Ancestor (LCA):
  * General Overview of Methods:
    * http://codeforces.com/blog/entry/16221 (skip to the LCA part)
  * Sparse Tables and LCA: https://www.youtube.com/watch?v=EKcQt-74bNw
  * Method 1 (RECOMMENDED): Binary Lifting Method (aka jump pointers: https://en.wikipedia.org/wiki/Level_ancestor_problem#Jump_pointer_algorithm):
    * http://codeforces.com/blog/entry/22325
      * Note: as the post says, this method is very handy as it can be also used to compute querys over paths in Trees
    * https://www.youtube.com/watch?v=kOfa6t8WnbI
  * Method 2: Euler Tour + Range Minimun Query:
    * https://www.topcoder.com/community/data-science/data-science-tutorials/range-minimum-query-and-lowest-common-ancestor/
    * Sparse Table Algorithm Range Minimum Query: https://www.youtube.com/watch?v=c5O7E_PDO4U
  * Example Code of Both Methods:
    * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Graphs/LCA.cpp
* Level Ancestor:
  * https://en.wikipedia.org/wiki/Level_ancestor_problem
  * https://www.quora.com/Why-does-storing-log-N-pointers-work-in-the-jump-pointer-solution-of-the-level-ancestor-problem
  * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Graphs/LA.cpp
* Heavy-Light Decomposition:
  * https://blog.anudeep2011.com/heavy-light-decomposition/
  * https://www.geeksforgeeks.org/heavy-light-decomposition-set-1-introduction/
  * http://codeforces.com/blog/entry/22072
* Max Flow:
  * Ford-Fulkerson Algorithm:
     * https://www.youtube.com/watch?v=Tl90tNtKvxs
     * https://www.youtube.com/watch?v=XPpmzulEmjA
     * https://www.youtube.com/watch?v=MczX0SM3I84
     * https://www.youtube.com/watch?v=GiN3jRdgxU4
  * Dinic Algorithm (RECOMENDADO):
     * https://www.youtube.com/watch?v=uM06jHdIC70
     * http://www.cs.cmu.edu/afs/cs.cmu.edu/academic/class/15451-f14/www/lectures/lec11/dinic.pdf
     * http://theory.stanford.edu/~tim/w16/l/l2.pdf
     * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Graphs/Dinic.cpp
  * Casos de uso:
     * (MUY RECOMENDADO) Ejemplos de problemas usando flujo: https://www.youtube.com/watch?v=nKcVc8XkFSA
     * Maximum Bipartite Matching: http://www.geeksforgeeks.org/maximum-bipartite-matching/

### Strings:
* Trie:
  * https://en.wikipedia.org/wiki/Trie
  * https://www.youtube.com/watch?v=zIjfhVPRZCg
  * https://www.youtube.com/watch?v=AXjmTQ8LEoI
  * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Strings/Trie.cpp
* KMP (String Pattern Matching):
  * https://www.youtube.com/watch?v=v82y5TCcBhQ
  * https://www.youtube.com/watch?v=GTJr8OvyEVQ
  * https://www.youtube.com/watch?v=KG44VoDtsAA
  * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Strings/KMP.cpp
* Shortest Repeating Cycle:
  * http://www.geeksforgeeks.org/find-given-string-can-represented-substring-iterating-substring-n-times/
  * http://stackoverflow.com/questions/6021274/finding-shortest-repeating-cycle-in-word
  * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Strings/shortest_repeating_cycle.cpp

### Mathematics:
* Números Primos:
  * Criba de Eratóstenes (todos los primos hasta N):
    * Criba de Eratóstenes [ICPCCL 2016]: https://www.youtube.com/watch?v=J4QCQ0dgeCI
    * https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes
  * Prime Factorization of Factorials: http://mathforum.org/library/drmath/view/67291.html
* Aritmética Modular:
  * ¿De qué se trata Aritmética Modular?
    * Introduction to Modular arithmetic: https://www.youtube.com/watch?v=9lUSKOjV4d0
    * High level introduction to modular arithmetic: https://www.youtube.com/watch?v=r0gYad8auYY
    * Congruence (Modular Arithmetic) & 5 Properties Explained with 7 Problems: Ultimate Shortcuts: https://www.youtube.com/watch?v=B1gD6540uWA
  * Modular Exponentiation By Squaring:
    * https://en.wikipedia.org/wiki/Modular_exponentiation#Right-to-left_binary_method
    * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Mathematics/binary_modular_exponentiation.cpp
  * Modular Fibonacci with Exponentiation by Squaring:
    * http://mathoverflow.net/questions/40816/fibonacci-series-mod-a-number
  * Algoritmo de Euclides:
    * Algoritmo de Euclides [ICPCCL 2016]: https://www.youtube.com/watch?v=k47fkSULGr0
    * GCD (greatest common divisor): https://www.youtube.com/watch?v=5jLWXwSXJdg
    * GCD extendido: https://www.youtube.com/watch?v=hB34-GSDT3k
    * Multiplicative Inverse Mod N: https://www.youtube.com/watch?v=_bRVA5b4sb4
    * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Mathematics/euclidean_algorithm.cpp
  * Modular Binomial Coefficient (Choose(n,k) mod X):
    * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Mathematics/modular_binomial_coefficient.cpp

### Geometry:
* Video Repaso de Geometría (SÚPER BUENO):
  * Geometría Computacional [ICPCCL 2016]: https://youtu.be/nk5ejrBWORw?list=PL-c_98SOXhxaXMMfnemh2ihniZsj57L8-
* Códigos varios de geometría 2D: https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Geometry/Geometry2DUtils.cpp. Incluye:
  * Ejemplo de un struct Point
  * Producto Cruz: Orientación de un punto respecto a un rayo (left, collinear o right)
    * basado en: https://www.geeksforgeeks.org/orientation-3-ordered-points/
  * Ordenar segmentos disjuntos por orden de intersección respecto a un rayo usando producto cruz
  * Detectar intersección de rectángulos
  * Detectar intersección de segmentos
    * basado en: https://www.geeksforgeeks.org/check-if-two-given-line-segments-intersect/
  * Detectar intersección de círculos
  * Distancia punto - segmento
    * basado en: https://stackoverflow.com/questions/849211/shortest-distance-between-a-point-and-a-line-segment
  * Distancia punto - recta
  * Hashing de ecuación de recta a partir de 2 puntos
* Trigonometría: https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Geometry/Trigonometry.cpp. Incluye:
  * Cálculo del ángulo de un vector 2D (medido ccw con respecto x+) usando atan2(y,x)
  * Implementación del teorema del coseno para cálcular ángulos internos de triángulos
* Cálculo de Áreas:
  * Teorema de Green (aplicado al caso particular de calcular áreas):
    * lecturas:
        * https://math.stackexchange.com/questions/199003/proving-greens-theorem-for-computing-area
        * https://mathinsight.org/greens_theorem_find_area
    * videos:
        * Green's Theorem: https://www.youtube.com/watch?v=a_zdFvYXX_c
        * 78 - Finding area with Green's theorem: https://www.youtube.com/watch?v=42vEvHpXYP8
        * How to Use Green's Theorem to Find the Area of A Region: https://www.youtube.com/watch?v=w3ugdu0oFgE
        * Green's Theorem: area under an arch | MIT 18.02SC Multivariable Calculus, Fall 2010: https://www.youtube.com/watch?v=KXof0q88xbg
  * Área de un polígono simple:
    * http://math.blogoverflow.com/2014/06/04/greens-theorem-and-area-of-polygons/
    * http://stackoverflow.com/questions/451426/how-do-i-calculate-the-area-of-a-2d-polygon    
    * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Geometry/PolygonArea.cpp
* Sweep Line y Radial Sweep Line:
  * https://en.wikipedia.org/wiki/Sweep_line_algorithm
  * https://www.topcoder.com/community/data-science/data-science-tutorials/line-sweep-algorithms/
  * http://codeforces.com/blog/entry/20377
  * https://apps.topcoder.com/forums/?module=Thread&threadID=684537&start=0&mc=6
* Detectar si un punto está dentro de un polígono:
  * http://geomalgorithms.com/a03-_inclusion.html
  * https://en.wikipedia.org/wiki/Point_in_polygon
  * Código ejemplo: https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Geometry/PointInPolygon.cpp
  * Point in Convex Polygon: http://stackoverflow.com/questions/1119627/how-to-test-if-a-point-is-inside-of-a-convex-polygon-in-2d-integer-coordinates
* Dualidad Línea Punto:
  * Buenas slides explicando dualidad: https://algo.kaust.edu.sa/Documents/cs372l13.pdf
  * Excelente pdf con demostraciones: https://pdfs.semanticscholar.org/810c/e0c19283481567c6545bf8c0cc8a4dcb8a1f.pdf  
  * Aplicación interactiva: http://students.cec.wustl.edu/~tdeck/duality/
* Convex Hull:
  * Buen video explicando Convex Hull: https://www.youtube.com/watch?v=wRTGDig3jx8
  * Monotone Chain Algorithm (algoritmo recomendado):
    * Video animación: https://www.youtube.com/watch?v=A4uWWnzTplM
    * Ejemplos de implementaciones:
      * https://en.wikibooks.org/wiki/Algorithm_Implementation/Geometry/Convex_hull/Monotone_chain
      * https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Geometry/ConvexHull.cpp
* Convex Hull Trick:
  * https://wcipeg.com/wiki/Convex_hull_trick
  * https://stackoverflow.com/questions/17834699/what-is-convex-hull-trick-exactly

_______________________________________________

## Contests

* Contest 1:
  * División 1: https://www.codepit.io/#/contest/5b68c884766004001f49fb52/view
     * hints: geometría 2D
  * División 2: https://www.codepit.io/#/contest/5b68d13b766004001f49fb56/view
     * hints: problemas de implementación, un poco de geometría 2D
  * Fecha Inicio: 06 de Agosto
  * Duración: 20 días
  * Soluciones de Ejemplo:
    * Div1: [Inside or Outside?](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/SPOJ/INOROUT_Inside_or_outside.cpp), [Counting Triangles](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/kattis/CountingTriangles.cpp), [ACIS, A Contagious vIruS](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/UVA/13117_ACIS_A_Contagious_vIruS.cpp), [Dating On-Line](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/URI/DatingOn-Line.cpp), Cake Cut [[v1](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/LiveArchive/7205_CakeCut_v1.cpp),[v2](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/LiveArchive/7205_CakeCut_v2.cpp)], [Keeping the Dogs Apart](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/kattis/KeepingTheDogsApart.cpp), [Fence the Vegetables Fail](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/UVA/13009_FenceTheVegetablesFail.cpp), [Arranging Tiles](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/URI/ArrangingTiles.cpp), [High Mountains](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/URI/HighMountains.cpp)
    * Div2: [Sum of the Others](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/kattis/SumOfTheOthers.cpp), [Touchscreen Keyboard](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/kattis/TouchscreenKeyboard.cpp), [Polynomial Multiplication 1](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/kattis/PolynomialMultiplication1.cpp), [Planting Trees](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/kattis/PlantingTrees.cpp), [Chewbacca and Number](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/Codeforces/514A_ChewbaccaAndNumber.cpp), [Inside or Outside?](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/SPOJ/INOROUT_Inside_or_outside.cpp), [Counting Triangles](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Solved%20problems/kattis/CountingTriangles.cpp)    
    
  
