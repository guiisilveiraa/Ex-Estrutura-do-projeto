# Especificação - Frete

# Especificação - Frete

### RF-001
Quando o usuário informar um CEP válido, o sistema deve calcular e exibir o valor do frete em até 800 ms.

### RB-001
Quando o valor do pedido for igual ou superior a R$ 300,00, o sistema deve disponibilizar frete grátis.

### RF-002
Quando o usuário consultar o frete, o sistema deve informar o prazo de entrega em dias úteis.

### RF-003
Quando houver mais de uma modalidade de entrega disponível, o sistema deve apresentar pelo menos 2 opções de frete.

### RB-002
Quando o frete for calculado, o valor exibido deve corresponder ao valor retornado pela transportadora.

### RF-004
Se não houver entrega disponível para o CEP informado, o sistema deve informar a indisponibilidade em até 1 segundo.

### RF-005
WHEN o usuário informar um CEP válido, THE SYSTEM SHALL calcular e exibir o valor do frete em até 800 ms.

### RB-003
WHILE a região for 'Norte', o limite é de R$300,00. Demais regiões: R$200,00

### RB-004
IF valor <= 0, THEN exibir erro 'Valor de carrinho inválido'