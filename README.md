Projeto em que solicitou a criação de tabelas e seus relacionamentos no modelo Star Schema com algumas fórmulas DAX, eu criei a tabela D_Calendário usando o comando DAX 
'''
D_Calendário = CALENDAR(MIN('F_Vendas'[Date]), MAX('F_Vendas'[Date]))
'''.
Eu criei um relacionamento entre a tabela F_Vendas e D_Calendário
</br>
A imagem das tabelas estão abaixo:
