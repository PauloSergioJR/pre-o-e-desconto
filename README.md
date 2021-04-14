prod = float(input('Qual o valor do produto ? R$'))
desc = (5/100)*prod
total = prod - desc
print('-'*100)
print('O valor do produto que custava R${}, com o desconto de 5 % passara a custar {:.2f}'.format(prod,total))
print('-'*100)
