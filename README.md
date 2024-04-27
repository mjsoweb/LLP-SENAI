<b>Lógica de Programação</b>

<i>Implementação de um sistema de controle de estoque de peças para facilitar o gerenciamento de estoque de uma empresa em JavaScript.</i>

<p>Esse sistema terá como função principal a de controlar a entrada e saída de peças
do estoque, além de atender aos seguintes requisitos:</p>

• a empresa possui apenas uma peça a ser controlada;<br>
• o sistema deverá solicitar sempre o saldo inicial da peça uma única vez a
cada vez que o sistema é iniciado;<br>
• o sistema deverá ter dois tipos de entrada de dados:<br>

1 = compra (entrada) de peças<br>
2 = venda (saída) de peças<br>

• enquanto o usuário não encerrar a entrada de dados, o sistema deverá
continuar solicitando nova entrada de dados:<br>
• os dados de entradas são: tipo de entrada e quantidade de peças;<br>
• caso a entrada seja do tipo 1 (compra), somar a quantidade ao estoque da
peça;<br>
• caso a entrada seja do tipo 2 (venda), subtrair a quantidade do estoque da
peça caso a quantidade de entrada seja inferior ou igual ao saldo de
estoque.<br> 
<br>
Caso seja informado uma quantidade maior que o saldo da peça,
apresentar a mensagem “Saldo insuficiente" e desconsiderar atualização
de saldo;<br>
<br>
• a cada entrada de dados, apresentar o saldo atualizado do estoque;<br>
• ao final de cada entrada de dados, perguntar se o usuário deseja continuar
(s) ou não (n) a entrada de dados;<br>
• caso o usuário encerre o sistema, apresentar a mensagem "Sistema
encerrado".<br>
