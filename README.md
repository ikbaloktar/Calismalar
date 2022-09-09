# Calismalar



Tektoplam = 0
Cifttoplam = 0
i = 1
while i <= 1000:
    if (i % 2 == 1):
        Tektoplam += i
    else:
        Cifttoplam += i

    i += 1

print(f"Tek Sayıların Toplamı: {Tektoplam}")
print(f"Çift Sayıların Toplamı: {Cifttoplam}")


a = int(input("Sayı Giriniz:"))
Tektoplam = 0
Cifttoplam = 0
i = 1
while i <= a:
    if (i % 2 == 1):
        Tektoplam += i
    else:
        Cifttoplam += i

    i += 1

print(f"Tek Sayıların Toplamı: {Tektoplam}")
print(f"Çift Sayıların Toplamı: {Cifttoplam}")
