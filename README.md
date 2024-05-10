s = "string"
indice = 0 
while indice in range (len (s)):
 print ("estamos no elemento", s [indice])
indice +=1

for elemento in [1,2,3,4,5,6]:
    print ("estamos no elemento",elemento)

    palavra= "tranquilo"
for indice, letra in enumerate(palavra):
    print (indice, letra)

    s = "viva o python"
for ch in s:
    print ("oi") 

    s = "viva o python"
for ch in s [3:8]:
    print ("oi")

    par = 0
impar = 0
for n in range (1,10):
    n = int (input("digite um numero"))
    if n %2== 0:
        par += 1  
    else :
        impar += 1 
print ("quantidade de numero par", par)
print ("quantidade de numero impar", impar)
