<b><h1>Sistemas Operacionais - Projeto “Multicat integer sort”</b> </h1>

Este projeto visa a criação de um programa que utilize múltiplas threads para ler números inteiros de vários
(n ≥ 1) arquivos com valores inteiros em diferentes quantidades, ordenar todos esses dados e concatena-los
em um único arquivo resultante.<p>
Toda essa operação – leitura dos arquivos, ordenação e concatenação dos dados – deve ocorrer utilizando 2,
4, 8 ou 16 threads, a critério do usuário.<p>
O programa deverá ser escrito para o sistema operacional Linux e obrigatoriamente utilizar a biblioteca POSIX
Threads.

<b><h2>Descrição do problema a ser resolvido</b></h2>

Considere que há vários (N ≥ 1) arquivos, cada um deles com uma certa quantidade de números inteiros sem
ordem estabelecida. O programa deverá ler os dados de todos esses n arquivos, organizá-los em ordem
crescente e armazenar em um único arquivo resultante.<p>
A ordenação pode ser feita com qualquer algoritmo estabelecido pela equipe. Entretanto, recomenda-se a
utilização de algoritmos rápidos de ordenação como, por exemplo, o Quicksort ou o Heapsort.<p>
A quantidade de arquivos é variável, podendo ser um único arquivo ou vários, a critério do usuário. Os arquivos
originais devem ser preservados.
 
 <b><h2>Entradas e saídas de valores para o programa</b></h2>
 
<b>Entradas:</b> o número de threads, os arquivos com os dados de entrada e o arquivo de saída que conterá os
resultados. Recomenda-se que todas essas informações de entrada sejam fornecidas na própria linha de
comando, conforme o exemplo a seguir.<p>
<b>Saídas</b>: um arquivo com os valores inteiros ordenados.<p>
    Por exemplo, suponha que o programa multicat deva ser executado com 16 threads lendo os arquivos de
números inteiros arq1.in, arq2.in, arq3.in, e produzindo o arquivo arqSaida.out com os dados
ordenados. <p><b>Assim, o comando para a execução do programa ficaria assim:</b></p>

./multicat 16 arq1.in arq2.in arq3.in arqSaida.out  <p>

