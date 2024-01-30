Compreensões para a execução do Algoritmo
No terminal digite o seguinte comando (É necessário que o python esteja instalado em sua máquina!)
```
$ python3 scp.py arquivo_de_entrada.dat numero_de_iteracoes_realizadas
```
```numero_de_iteracoes_realizadas``` é o número de vezes que você quer que o algoritmo execute, quanto mais iterações,
melhor poderá ser a solução encontrada

Onde o arquivo de entrada deve ser do tipo .dat e deve estar no mesmo diretório do arquivo scp.py

OBS: Ao executar esse algoritmo, ele irá trazer a melhor solução encontrada(aplicando o melhoramento) para ambos
algoritmos construtivos, ele irá realizar as iterações que o usuário forneceu na entrada para cada algoritmo construtivo,
ou seja, dependendo do tamanho do arquivo de entrada, o algoritmo pode demorar um pouco para ser executado.

Caso queira também, você pode testar o algoritmo funcionando apenas com o algoritmo construtivo, sem ter melhoramento de solução,
para isso, basta comentar as linhas que chamam o melhoramento: Comentário é feito com o símbolo '#' (linhas 315 a 319)

           # num_iteracoes = int(sys.argv[2])
           # print("Set Covering Problem - Heuristica Construtiva 1\n")
           # construtivo_com_melhoramento(ler_arquivo(nome_do_arquivo))
           # print("\nSet Covering Problem - Heuristica Construtiva 2\n")
           # construtivo_2_com_melhoramento(ler_arquivo(nome_do_arquivo))

E descomentar as linhas (remover o '#') que aparecem da linha 321 a  331, e executar esse comando
```
$ python3 scp.py arquido_de_entrada.txt
```
Que o algoritmo vai trazer 20 resultados encontrados (melhores) para o construtivo 1 e 2 sem a aplicação do melhoramento
