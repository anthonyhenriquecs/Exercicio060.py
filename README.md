# Exercicio060.py

#from math import factorial
#n = int(input('Digite um numero:'))
#f = factorial(n)
#print('O fatorial de {} é :{}'.format(n,f))

n = int(input('Digite um numero:'))
c = n
f = 1
print('Calculando o fatorial de {}!:'.format(n))
while c > 0:
    print(c,end= ' ')
    print(' x 'if c > 1 else ' = ', end= '')
    f *= c
    c -= 1
print('{}'.format(f))
