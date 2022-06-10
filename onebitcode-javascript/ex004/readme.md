# Utilizando Condicionais

**Neste exercício vamos simular o sistema de navegação de uma nave interagindo com o usuario.**

O sistema deve fazer o seguinte:

1 - Perguntar o `nome` do piloto

2 - Colocar a `velocidade` inicial da nave como `0`

3 - Perguntar a que `velocidade` ele gostaria de acelerar a nave

4 - Pedir uma `confirmação` informando que está indo para velocidade `X km/s`

5 - Exibir uma das seguintes mensagens com base na velocidade escolhida:
* Se for **menor** que 0km/s: *"Nave está parada. Considere partir e aumentar a velocidade"*
* Se for **menor** que 40km/s: *"Você está devagar, podemos aumentar mais"*
* Se for **maior** ou igual a 40km/s e menor que 80km/s: *"Parece uma boa velocidade para manter"*
* Se for **maior** ou igual a 80km/s e menor que 100km/s: *"Velocidade alta. Considere diminuir"*
* Se for **maior** ou igual a 100km/s: *"Velocidade perigosa. Controle automático forçado"*

6 - Imprimir no final o `nome` do piloto com a `velocidade` atual.