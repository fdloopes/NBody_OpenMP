/* Conteúdo do diretório */

main.cpp  // Chamadas principais do problema N-NBody
nbody.cpp // Instanciação de variaveis globais, Argumentos e funções utilizadas no problema
nbody.hpp // Definições de funções e variaveis
Makefile  // Responsável por facilitar a compilação do programa
input_files // Diretório que possui os arquivos de entrada

/* Dicas para compilar e executar o programa */

Comando para compilar o programa: make openmp

Comando para limpar executaveis: make clean clean-o

Comando para executar o programa: ./nbody_simulation <numero de threads> <arquivo de entrada>

<numero de threads>   // Passar um inteiro relativo ao número de threads que se deseja definir
<arquivo de entrada>  // Aqui passa o caminho "input_files/nbody_input-<tamanho da entrada>.in"
<tamanho da entrada>  // O tamanho pode ser 16384_16384, 32768_32768 ou 65536_65536

Exemplo de comando para executar programa

./nbody_simulation 4 input_files/nbody_input-32768_32768.in
