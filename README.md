Compreensões para a execução do Algoritmo
No terminal digite o seguinte comando (É necessário que o python esteja instalado em sua máquina!)
```
$ python3 scp.py arquivo_de_entrada.txt numero_de_iteracoes_realizadas
```
numero_de_iteracoes_realizadas é o número de vezes que você quer que o algoritmo execute, quanto mais iterações,
melhor poderá ser a solução encontrada

Onde o arquivo de entrada deve ser do tipo .txt e deve estar no mesmo diretório do arquivo scp.py

OBS: Ao executar esse algoritmo, ele irá trazer a melhor solução encontrada(aplicando o melhoramento)
para ambos algoritmos construtivos, ele irá realizar 20 mil iterações para cada algoritmo construtivo,
ou seja, dependendo do tamanho do arquivo de entrada, o algoritmo pode demorar um pouco para ser executado.

Caso queira diminuir o número de iterações, basta alterar o valor que está presente dentro das funções:
        - construtivo_com_melhoramento(dados) 
        - construtivo_2_com_melhoramento2(dados)
Onde você mesmo pode alterar o valor presente na linha
        #- for _ in range(20000):
Para um valor menor, por exemplo:
        #- for _ in range(10000):

Caso queira também, você pode testar o algoritmo funcionando apenas com o algoritmo construtivo, sem ter melhoramento de solução,
para isso, basta comentar as linhas que chamam o melhoramento: Comentário é feito com o símbolo '#' (linhas 302 a 307)

           # nome_do_arquivo = sys.argv[1]
           # print("Set Covering Problem - Heuristica Construtiva 1\n")
           # construtivo_com_melhoramento(ler_arquivo(nome_do_arquivo))
           # print("\nSet Covering Problem - Heuristica Construtiva 2\n")
           # construtivo_2_com_melhoramento(ler_arquivo(nome_do_arquivo))

E descomentar as linhas (remover o '#') que aparecem da linha 309 a  319, e executar o algoritmo normalmente
