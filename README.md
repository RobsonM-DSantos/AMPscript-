# AMPscript-
Solução usando um Loop for e uma estrutura condicional para uma data extension com vários produtos 
![WhatsApp Image 2023-03-14 at 11 34 08](https://user-images.githubusercontent.com/101661686/225035252-8ce1cd9c-5353-4cde-aae0-72b44fae7f06.jpeg)

<br>
<br>

<p>Esse código utiliza a linguagem AMPScript, que é usada em e-mails e landing pages criados no Salesforce Marketing Cloud. O código realiza o seguinte procedimento:

Define quatro variáveis para armazenar os valores das colunas de uma tabela DE_ABANDONED_CART_CONTENT (conteúdo do carrinho de compras abandonado) de um determinado cliente, que é identificado através do valor do atributo "customerNo".
Usa a função LookupRows() para buscar todas as linhas da tabela DE_ABANDONED_CART_CONTENT que contenham o valor de "customerNo" igual ao valor armazenado em @customerNo e armazena essas linhas em @rows.
Usa a função rowcount() para obter o número total de linhas encontradas em @rows e armazena o resultado em @rowcount.
Se @rowcount for maior do que zero, inicia um loop for que será executado uma vez para cada linha em @rows.
Para cada linha, o código armazena os valores de suas colunas em suas respectivas variáveis: @FPV, @fpp, @cra, @base, @Codigo_Produto, @massive, @productname e @image.
Usa uma sequência de condicionais "if" e "elseif" para determinar o valor a ser atribuído a cada uma das variáveis @n1, @n2, @n3 e @N4, com base nos valores armazenados nas variáveis @massive, @FPV, @fpp e @cra.
No final do loop, o código termina a sua execução e as variáveis criadas deixam de existir.</p>
