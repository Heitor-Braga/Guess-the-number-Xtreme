# Guess-the-number-Xtreme
![projeto finalizado](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/ff785bf3-6a94-41ab-9ee3-18826b44b721)

Projeto finalizado.

____________________

Circuito do cronômetro:

![cronometro](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/23326c6e-6eaa-4ea5-915a-11dc3bfad568)

Para cada dígito do cronômetro há 4 flip-flops D, cujas saídas estão ligadas a um circuito combinacional, que define, a partir do número atual mostrado no display, o estado próximo de cada flip-flop.

Este é o circuito combinacional para os dígitos que vão de 5 a 0:

![combinacional 5-0](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/33fa64dd-04bf-4f1c-b79f-a7c12fbd066d)

Este é o circuito para os dígitos que vão de 9 a 0:

![combinacional 9-0](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/c14654d1-69f0-4805-962f-185d0b3acafa)

____________________

Circuito somador:

![somador](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/3d4d0467-cf0b-436a-b160-25d2c7f1d2e5)

O somador recebe dois números de 4 bits e retorna um número de cinco bits.
obs: O quinto bit (mais significativo) de cada número que entra no somador é apenas um bit de sinal.

____________________

Esse é o circuito que recebe um número de 4 bits e retorna ele no formato de complemento de 2.
Além disso, uma das saídas representa o sinal desse número.

Por exemplo, se as 4 entradas forem 1 0 0 1, ele irá ter como saída os valores 1 0 1 1 1, sendo o primeiro bit o de sinal.
Representando assim um 7 negativo.

![combinacional display](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/0cbcb741-25dc-455b-b3b5-e3924c0aca18)

____________________

Visto alguns dos circuitos elementares para a construção do projeto, eis a aplicação deles:

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/bb67007b-1dd2-46b5-80f9-745691dc066b)

Representação dos números escolhidos pelos jogadores, do número X e do número Y nos displays.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/3bf59b08-e7d9-4898-a94c-59317d301c1b)

Circuito para o botão de chutar.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/5df4617a-9a23-4b20-9a22-c95973d79e2c)

No primeiro circuito temos a soma entre o número X e Y escolhidos pelos jogadores.
Logo após há a comparação desse número com um número aleatório gerado pelo jogo.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/c050124f-98bb-4ab7-a929-f64b7502e574)

Circuito para o botão de próximo.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/b0b68740-9e99-4669-ad6a-f79b964976ab)

Esse é o circuito que recebe o resultado da comparação e indica qual led deve ser aceso, bem como se houve ponto.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/d7b2cbb5-59ae-4813-bd36-12b8fe7a2172)

Cicuito responsável pela representação do placar.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/bd157cc5-80bc-45d5-a5e0-4562fc5cb1e8)

Quando o tempo dos dois jogadores acaba, esse circuito mostra se houve vencedor ou se foi um empate.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/ca46e592-cd97-466e-ab8a-2fa7a2ce517f)

Aqui temos as condições para definir quando o jogo acaba e qual jogador está na vez.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/bddff99b-b6db-4059-af3f-fbcfe2d07e18)

Esse é o circuito responsável por gerar um número aleatório.
São gerados dois números aleatórios de 4 bits e, em seguida, feito a soma entre eles.
O máximo valor possível é 14 e o mínimo é -16.

____________________

![image](https://github.com/Heitor-Braga/Guess-the-number-Xtreme/assets/149103391/e23645e3-2991-4722-8878-5dd53553bac8)

Essa é a aplicação do cronômetro no circuito principal.
Há um para cada jogador e aí estão definidas as condições para cada um dos cronômetros iniciarem, pausarem ou resetarem.




























