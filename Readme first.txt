Os arquivos SP_33N.txt, SP_69N.txt, SP_136N.txt e SP_417N.txt definem os dados dos sistemas de distribuição de energia elétrica de 33, 69, 136 e 417 barras, respectivamente.

No arquivo "SP_Configuracion.txt" se define qual sistema será executado (33, 69, 136 ou 417 barras).

Usar o programa "repoten.exe" na janela de comandos (que pode ser aberta com o link direto "Ejecutar repoten") ou ao abrir "ejecutar repoten" deve-se digitar "repoten.exe " e ser passados 2 argumentos: 

O "número de iterações" e o "parâmetro tabu", em seguida clique "enter" para começar a simulação.

Assim, para executar o programa utilizando os sistemas de 33, 69 e 136 barras, deve-se seguir o exemplo:

------------------------------
repoten.exe 100 5
------------------------------

O  comando anterior resolve o problema com 100 iterações e com parâmetro tabu igual a 5.

Para o sistema de 417 barras, os parâmetros devem ser alterados, como segue o exemplo: 

------------------------------
repoten.exe 1000 51
------------------------------

O melhor resultado foi encontrado com 1000 iterações de fluxos de carga e parâmetro tabu igual a 51.