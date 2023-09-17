# Hi-Kod_homework
Hi-Kod_homework(if-and loop)


maas1 = float(int(input("maaşınızı girin : ")))
if(maas1 <= 10000):
    vergi = (maas1 / 5 )
    sonuc = (maas1 - vergi)
    print(sonuc)
    
if(maas1 <= 25000):
    vergi = (maas1 / 10 )
    sonuc = (maas1 - vergi)
    print(sonuc)
if(maas1 <= 45000):
    vergi = (maas1 / 10 )
    sonuc = (maas1 - vergi)
    print(sonuc)
else:
    vergi = (maas1 / 30 )
    sonuc = (maas1 - vergi)
    print(sonuc)

----------------------------------------

kullanıcıAdı = input("kullanıcı adınızı giriniz ")
sifre = input("şifrenizi giriniz ")
            
if len (sifre) == 6 :
        print("hesabınız oluşturuldu")
        
if len (sifre) >= 7 :
        print("yeniden şifre seçiniz")
        
if len (sifre) <= 5 :
        print("yeniden şifre seçiniz")
        
----------------------------------------

while (True):
    şifre = input("şifrenizi girin, şifreniz 5-10 karakter olmalı ")

    if 5 <= len(şifre) <= 10 :
        print("hesabınız oluşturuldu")
        break
    else:
        print("yeniden şifre giriniz")

----------------------------------------

gerçekŞifre = 123456

isim = input("isminizi girin ")
şifre = input("şifrenizi giriniz")

for i in range(3):
    if şifre == gerçekŞifre :
        print("giriş yapıldı")
        break
    else:
        print(f"{3 - i} hakkınız kaldı. Bir daha deneyin.")
        şifre = input("şifrenizi giriniz: ")




















