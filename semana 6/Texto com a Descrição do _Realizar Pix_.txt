# descrição caso de uso REALIZAR PIX.
## UCS 3 - "Use case 3".
* Atores:
* cliente
* bancoBacen
### Descrição: 
* esse caso de uso mostra o fluxo de realização de pix do banco central.
 
### Pré-condições:
* O cliente ja deve estar logado no aplicativo.
* O cliente deve ter saldo o suficiente na conta.
### Pós-condições:
* atualização de saldo.
* decremento de saldo.
### Fluxo principal.
* O cliente seleciona a opção "Realizar pix".
* O sistema verifica autentificação de usuario.
* O sistema confirma o saldo.
* O sistema cadastra chave pix.
### casos de exceção
#### case 1:
* O cliente seleciona a opção "Realizar pix".
* O sistema verifica autentificação de usuario.
* O sistema confirma saldo insuficiente.
* volta errosaldoinsuficiente.
#### case 2
* O cliente seleciona a opção "Realizar pix".
* O sistema verifica autentificação de usuario.
* O sistema confirma o saldo.
* O sistema cadastra chave pix.
* O sistema não reconhece chave pix.
* O sistem retorna errorchavepix.

