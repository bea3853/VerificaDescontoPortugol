# VerificaDescontoPortugol
Aplicação para verificar desconto em portugol
algoritmo "VerifcarDesconto"
var
sal, des1, des2:real

inicio

escreval ("Apenas para clientes que ganham entre R$1000.00 e 4999.99")

escreval ("Digite o valor do seu salário:")
leia (sal)


se (sal<2999.99)entao
des1:= (sal/100*30)
escreval ("Você tem 30% de desconto sobre o seu salário, ou seja R$", des1:1:2)
senao se (sal>2999.99) entao
des2:= (sal/100*35)
escreval ("Você tem 35% de desconto sobre o seu salário, ou seja R$", des2:1:2)
fimse


fimalgoritmo
