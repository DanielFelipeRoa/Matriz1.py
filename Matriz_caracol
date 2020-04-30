import random

n = int(input("Favor ingrese el valor de n: "))
matriz = [None] * n
for i in range(0,n):
  for j in range(0,n):
    matriz [i][j] = (int)(random.randint(1,1001))
print "Original"
print matriz

print "En caracol"

for i in range(0,n):
  if (i % 2 == 0):
    for j in range(0,n):
      print str(matriz[i][j]) + "\t"
  else:
    for j in range(n-1,-1,-1):
      print str( matriz[i][j] ) + "\t"
