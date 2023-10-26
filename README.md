# Guess-the-number-Xtreme
![projeto finalizado](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/2bcc473e-4d9a-4af7-961a-abf9426c8109)

Projeto finalizado.

____________________

Circuito do cronômetro:

![cronometro](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/75b7c87f-ca8e-4350-a5a4-e8fcddf8dd0d)

Para cada dígito do cronômetro há 4 flip-flops D, cujas saídas estão ligadas a um circuito combinacional, que define, a partir do número atual mostrado no display, o estado próximo de cada flip-flop.

Este é o circuito combinacional para os dígitos que vão de 5 a 0:

![combinacional 5-0](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/6cd49640-5868-4f7f-ac07-6d5bb9dd080f)

Este é o circuito para os dígitos que vão de 9 a 0:

![combinacional 9-0](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/d80d1b42-c4bb-43ed-ae53-eb11c281e794)

____________________

Circuito somador:

![somador](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/88333d62-6c7b-4426-9291-b09491b57a4a)

O somador recebe dois números de 4 bits e retorna um número de cinco bits.
obs: O quinto bit (mais significativo) de cada número que entra no somador é apenas um bit de sinal.

____________________

Esse é o circuito que recebe um número de 4 bits e retorna ele no formato de complemento de 2.
Além disso, uma das saídas representa o sinal desse número.

Por exemplo, se as 4 entradas forem 1 0 0 1, ele irá ter como saída os valores 1 0 1 1 1, sendo o primeiro bit o de sinal.
Representando assim um 7 negativo.

![combinacional display](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/b4b2881c-65f2-44f3-8e1e-18dc2ba43930)

____________________

Visto alguns dos circuitos elementares para a construção do projeto, eis a aplicação deles:

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/02aa8ac5-1838-4498-8cf9-9148badc374f)

Representação dos números escolhidos pelos jogadores, do número X e do número Y nos displays.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/efad7878-3dc7-480a-a807-ff9c37a5745c)

Circuito para o botão de chutar.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/bcb1ecc1-88b8-4b39-beca-5107e3aafb7d)

No primeiro circuito temos a soma entre o número X e Y escolhidos pelos jogadores.
Logo após há a comparação desse número com um número aleatório gerado pelo jogo.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/927589f2-30e2-4fd4-ac5a-cd90011b4e15)

Circuito para o botão de próximo.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/9a6c488e-7a81-488e-b61b-5340fd057148)

Esse é o circuito que recebe o resultado da comparação e indica qual led deve ser aceso, bem como se houve ponto.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/dbdf517d-1cf9-4d82-84b3-ea66d3cd2c44)

Cicuito responsável pela representação do placar.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/0a44269d-7d0e-4f8e-85b1-52118de9de4a)

Quando o tempo dos dois jogadores acaba, esse circuito mostra se houve vencedor ou se foi um empate.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/5161442b-f38c-4519-966d-aa94940e6d9e)

Aqui temos as condições para definir quando o jogo acaba e qual jogador está na vez.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/d1ce4fd7-e53e-4bc6-a1dc-c23dc3c0a199)

Esse é o circuito responsável por gerar um número aleatório.
São gerados dois números aleatórios de 4 bits e, em seguida, feito a soma entre eles.
O máximo valor possível é 14 e o mínimo é -16.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/5febaab2-eb8e-4eeb-8e54-092b9b7b784c)

Essa é a aplicação do cronômetro no circuito principal.
Há um para cada jogador e aí estão definidas as condições para cada um dos cronômetros iniciarem, pausarem ou resetarem.




























