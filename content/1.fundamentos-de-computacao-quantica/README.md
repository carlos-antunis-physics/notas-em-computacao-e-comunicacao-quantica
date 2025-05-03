#   Fundamentos de computação quântica

A computação quântica consiste num paradigma recente e ainda em desenvolvimento de computação que permite, teoricamente, ganhos notáveis de performance sobre a computação clássica. Iremos abordar aqui, as bases que fundamentam a computação quântica como a ideia de `Qbits` ademais às operações que tal máquina é capaz de operar, as `portas lógicas quânticas`, bem como a utilização dessa no design de algoritmos mais eficientes.

>   ##  [1.1. Introdução à computação quântica](./1.introducao-a-computacao-quantica.ipynb)
>
>   Nesta seção iremos abordar os processos clássicos e quânticos de computação. Inicialmente, trataremos de descrever a computação clássica como operações sobre bits e mostraremos seu análogo quântico, o `qubit`, ademais aos fenômenos de superposição e interferência. Imediatamente após, iremos nos ater a composição de sistemas quânticos de dois níveis, onde se destaca a emergência do fenômeno de emaranhamento. Por fim, descreveremos os processos clássicos e quânticos de computação por meio de portas lógicas.

<div align="center">

![under construction image](../../under-construction.png)

</div>

##  Introdução aos algoritmos quânticos

Apresentaremos aqui alguns algoritmos quânticos elementares que demonstram, como prova de princípio, a capacidade da computação quântica de se sobresair ante à computação clássica em determinados casos.

>   ### [1.2. Algoritmo de Deutsch-Jozsa](2.algoritmo-de-deutsch-jozsa.ipynb)
>
>   O algoritmo de Deutsch-Jozsa é um dos primeiros exemplos da vantagem latente do processamento quântico de informações sobre a computação clássica. Tal algoritmo é utilizado para classificar funções binárias (função que opera sobre uma `bit-string` retornando outra) é constante ou balanceada.

>   ### [1.3. Algoritmo de Groover](3.algoritmo-de-groover.ipynb)
>
>   O algoritmo de Groover é um dos primeiros algoritmos quânticos propostos, e também apresenta-se como um dos mais proeminentes exemplos de vantagem da computação quântica sobre a clássica. Tal algoritmo é utilizado em problemas de busca não estruturada, apresentando um ganho quadrático de eficiência ao seu análogo clássico (algoritmo de `busca linear`), sendo o primeiro algoritmo quântico com valor verdadeiramente prático.

>   ### [1.4. Algoritmo de Bernstein-Vazirani](4.algoritmo-de-bernstein-vazirani.ipynb)
>
>   O algoritmo de Bernstein-Vazirani é também um importante exemplo de algoritmo quântico. Este algoritmo é utilizado para determinar uma string oculta de uma função linear sendo necessária apenas uma consulta ao oráculo, diferentemente do método clássico que exigiria múltiplas consultas.

>   ### [1.4. Algoritmo de Simon](4.algoritmo-de-bernstein-vazirani.ipynb)
>
>   O algoritmo de Simon é um importante algoritmo quântico, por ser um dos primeiros a demonstrar vantagem exponencial sobre os métodos clássicos. Este é projetado para encontrar uma string oculta dada uma função $f$ que satisfaz a condição $f(x) = f(x \oplus s)$ - onde $\oplus$ denota a soma `bit`a `bit` (`xor`).

>   ### [1.5. Algoritmo da transformada de Fourier quântica](5.algoritmo-de-simon.ipynb)
>
>   O algoritmo da transformada de Fourier quântica (`QFT`) é uma versão quântica da transformada de Fourier discreta (`DFT`). Sendo uma importante ferramenta para alguns algoritmos quânticos (tal qual o algoritmo de Shor).

>   ### [1.6. Algoritmo de Shor](6.algoritmo-da-transformada-de-fourier-quantica.ipynb)
>
>   O mais proeminente dos primeiros algoritmos quânticos, o algoritmo de Shor é o cerne do impacto da computação quântica no futuro onde computadores quânticos serão acessíveis. Tal algoritmo é concebido com a finalidade de fatorar números em fatores primos, sendo capaz de resolver tal problema em tempo polinomial, um ganho exponencial em relação ao seu análogo clássico. Sua relevância se dá pois apresenta uma ameaça gritante à segurança criptográfica de sistemas baseados na criptografia RSA, que se fundamenta na dificuldade de fatorar números grandes.

##  Apêndices

>   ### [A. Aspectos fundamentais da mecânica quântica](./apendices/A.aspectos-fundamentais-da-teoria-quantica.ipynb)
>
>   Neste apêndice iremos abordar os fundamentos da teoria quântica, introduzindo os seus postulados que permitem compreender o comportamento de medidas no regime quântico da natureza, ademais à forma com que estes evoluem como avançar do tempo. Por fim, iremos introduzir o operador densidade, que permite descrever a estatística de um sistema físico, contabilizando efeitos quânticos ou clássicos (advindos da experimentação).

>   ### [B. Aspectos fundamentais de computação](./apendices/B.aspectos-fundamentais-de-computacao.ipynb)
>
>   Neste apêndice introduziremos os fundamentos da teoria de computação e complexidade, desde seus modelos formais - tais como autômatos elementares e máquinas de Turing - a complexidade da implementação de algoritmos e por fim iremos apresentar alguns dos mais importantes algoritmos da computação clássica.

---

<div align="right">

[voltar à página inicial](../../README.md)

</div>