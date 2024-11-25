# Concorrencia-SO
Um trabalho da faculdade onde será feito um algoritmo usando threads em C

O programa recebe
três argumentos de linha de comando:
$ ./psort<nusp> <entrada> <saída> <threads>

- O parâmetro <entrada> é o nome de um arquivo que contém os registros a serem
ordenados.
- Os registros serão ordenados pelas chaves APENAS.
- Você deve forçar gravações no disco chamando fsync() ou
msync() no arquivo de saída antes de terminar a execução do programa.
- O parâmetro <threads> deve ser usado para determinar a quantidade máxima de threads
adicionais que o programa usará. Se o parâmetro for igual a 0, o programa deve decidir
quantas threads usar.

Ao finalizar o projeto, haverão duas sessões no meu relatório:
1) Uma seção com as decisões de projeto que tomei; 
2) Uma seção com uma análise de desempenho do seu programa
