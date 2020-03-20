# sistemas-inteligentes-2020.1

### Repositorios a descargar:

A continuación todos los repositorios que serán utilizados en clase, recuerden que deben integrar el .jar de cada uno en un proyecto de eclipse (netbeans también se puede [o en su caso cualquier ambiente de desarrollo que usen]). La única excepción es uniltiranyu, para ese repo hay que descargar todo el código fuente.

* https://github.com/jgomezpe/uniltiranyu [fuente]
* https://github.com/jgomezpe/aplikigo
* https://github.com/jgomezpe/fwew
* https://github.com/jgomezpe/hazarda
* https://github.com/jgomezpe/kitee
* https://github.com/jgomezpe/matematiko
* https://github.com/jgomezpe/speco

### Orden de las diapositivas:

La siguiente lista muesta el número de diapositiva que cada uno debe hacer para cada capítulo, es decir, si soy el primero de la lista, debo hacer las diapositivas 1, 25, 49 y 73 de todos los capítulos. Hay que traducir los capítulos 2, 3, 4, 5, 6, 7, 8 y 9.


| Estudiante                            | Número de diapositiva  |
| ------------------------------------- |:----------------------:|
| Aguirre Arias, Gabriel David          |  1 25  49  73          |
| Albarracín Riveros, Giovanny Fermin   |  2 26  50  74          |
| Angulo Suescun, Daniel                |  3 27  51  75          |
| Aranguren Silva, Andrés Fernando      |  4 28  52  76          |
| Barreto Cajica, Alex Jose Alberto     |  5 29  53  77          |
| Díaz Vecchio, Alejandro               |  6 30  54  78          |
| Medina Correa, Jherson Adrian         |  7 31  55  79          |
| Medrano Monroy, Manuel David          |  8 32  56  80          |
| Mendez , Oscar Fabian                 |  9 33  57  81          |
| Moreno Rincon, Daniel Arturo          |  10  34  58  82        |
| Otalora Cubides, Luis Eduardo         |  11  35  59  83        |
| Pardo Arias, Nicolas Eduardo          |  12  36  60  84        |
| Perdomo Cristancho, David Esteban     |  13  37  61  85        |
| Perez Ceron, Daniel Camilo            |  14  38  62  86        |
| Pieschacon Rueda, Felipe              |  15  39  63  87        |
| Rico Hernandez, David Felipe          |  16  40  64  88        |
| Rodriguez Salguero, Nicolas           |  17  41  65  89        |
| Ruiz Herrera, Sergio Andrés           |  18  42  66  90        |
| Salgado Lopez, Rafael Antonio         |  19  43  67  91        |
| Solano Velasquez, Ivan Dario          |  20  44  68  92        |
| Suarez Gamez, Moises Bernardo         |  21  45  69  93        |
| Torres Forero, Jhonatan               |  22  46  70  94        |
| Velasquez Vargas, Diego Armando       |  23  47  71  95        |
| Zambrano Penagos, Guiselle Tatiana    |  24  48  72  96        |


### Formato de diapositiva:

Por favor subir un archivo .tex cuyo contenido sea el código LaTex de esa diapositiva únicamente, el nombre del archivo debe ser el número de diapositiva, ejemplo:

6.tex:
```tex
\begin{frame}{El agente aspiradora}

\begin{center}
\def\arraystretch{1}
 \begin{tabular}{||l|r||} 
 \hline
 Secuencia de percepciones   & Acción \\
 \hline
 \hline
 \hspace{1em} '[A, Limpio]' \hspace{1em} & \hspace{1em} Derecha \\
 \hspace{1em} '[A, Sucio]' \hspace{1em} & \hspace{1em} Aspirar \\
 \hspace{1em} '[B, Limpio]' \hspace{1em} & \hspace{1em} Izquierda \\
 \hspace{1em} '[B, Sucio]' \hspace{1em} & \hspace{1em} Aspirar \\
 \hspace{1em} '[A, Limpio]', '[A, Limpio]' \hspace{1em} & \hspace{1em} Derecha \\
 \hspace{1em} '[A, Limpio]', '[A, Sucio]' \hspace{1em} & \hspace{1em} Aspirar \\ 
 ... & ... \\ [1ex]
 \hline
 \end{tabular}
\end{center}
\setlength{\arrayrulewidth}{0.3mm}
\begin{tabular}{|l|} 
 \hline
    La \textbf{función} Reflex-Vacuum-Agent(\textit{[ubicación,estado]}) \textbf{retorna} una acción \\
    \\
    \hspace{1em} \textbf{sí} \textit{estado = Sucio} \textbf{entonces retorna} \textit{Aspirar} \\
    \hspace{1em} \textbf{entonces sí} \textit{ubicación = A} \textbf{entonces retorna} \textit{Derecha} \\
    \hspace{1em} \textbf{entonces sí} \textit{ubicación = B} \textbf{entonces retorna} \textit{Izquierda} \\
 \hline
\end{tabular}
¿Qué es la función Derecha? \newline
¿Puede ser implementada en un pequeño programa de agente?
\end{frame}
```

Este archivo corresponde a la diapositiva 6 del capítulo dos, por ende debe estar ubicado en la siguiente ruta:

```
/diapositivas/chapter2/6.tex
```

En caso de que la diapositiva contenga imágenes embebidas, estas deben ir en la misma carpeta y su nombre debe usar como prefijo el número de la diapositiva:

```
/diapositivas/chapter2/6_image_name.png
```

