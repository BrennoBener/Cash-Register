Cash Register
Design a cash register drawer function checkCashRegister() that accepts purchase price 
as the first argument (price), payment as the second argument (cash), and cash-in-drawer (cid) 
as the third argument.

cid is a 2D array listing available currency.

The checkCashRegister() function should always return an object with a status key and a change key.

Return {status: "INSUFFICIENT_FUNDS", change: []} if cash-in-drawer is less than the change due,
 or if you cannot return the exact change.

Return {status: "CLOSED", change: [...]} with cash-in-drawer as the value for the key change if it is equal
 to the change due.

Otherwise, return {status: "OPEN", change: [...]}, with the change due in coins and bills, sorted in 
highest to lowest order, as the value of the change key.

Currency Unit	Amount
Penny	$0.01 (PENNY)
Nickel	$0.05 (NICKEL)
Dime	$0.1 (DIME)
Quarter	$0.25 (QUARTER)
Dollar	$1 (ONE)
Five Dollars	$5 (FIVE)
Ten Dollars	$10 (TEN)
Twenty Dollars	$20 (TWENTY)
One-hundred Dollars	$100 (ONE HUNDRED)
See below for an example of a cash-in-drawer array:

[
  ["PENNY", 1.01],
  ["NICKEL", 2.05],
  ["DIME", 3.1],
  ["QUARTER", 4.25],
  ["ONE", 90],
  ["FIVE", 55],
  ["TEN", 20],
  ["TWENTY", 60],
  ["ONE HUNDRED", 100]
]

----------------------------------------------------------------------------------

Caixa registradora
Implemente uma função de caixa registradora checkCashRegister() que aceita o preço de compra como
 o primeiro argumento (price), pagamento como o segundo argumento (cash) e dinheiro na registradora (cid)
  como o terceiro argumento.

cid é um array de duas dimensões listando a moeda disponível e a quantidade.

A função checkCashRegister() deve sempre retornar um objeto com a chave status e uma chave change.

Retorne {status: "INSUFFICIENT_FUNDS", change: []} se o dinheiro no caixa for menor que o troco devido, 
ou se você não pode retornar o troco exato.

Retorne {status: "CLOSED", change: [...]} com dinheiro no caixa como o valor para a chave change se for 
igual ao troco devido.

Caso contrário, retorne {status: "OPEN", change: [...]}, com o troco devido em moedas e notas,
 ordenado do maior para o menor, como o valor da chave change.

Unidade de moeda	Quantidade
Penny	$0,01 (PENNY)
Nickel	$0,05 (NICKEL)
Dime	$0,1 (DIME)
Quarter	$0,25 (QUARTER)
Dólar	$1 (ONE)
Cinco dólares	$5 (FIVE)
Dez dólares	$10 (TEN)
Vinte dólares	$20 (TWENTY)
Cem dólares	$100 (ONE HUNDRED)
Veja abaixo um exemplo de um array de dinheiro no caixa (cid):

[
  ["PENNY", 1.01],
  ["NICKEL", 2.05],
  ["DIME", 3.1],
  ["QUARTER", 4.25],
  ["ONE", 90],
  ["FIVE", 55],
  ["TEN", 20],
  ["TWENTY", 60],
  ["ONE HUNDRED", 100]
]