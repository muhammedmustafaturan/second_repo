import random

karakterler =("+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890")

uzunluk = int(input("Parola uzunluğunu girin: "))
    
parola = ""

for i in range(uzunluk):
    parola += random.choice(karakterler)

print("Yeni parola:", parola)
