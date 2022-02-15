from random import choice,choice,choices
sayilar=(1,2,3,4,5,6,7,8,9,0,"vefa","hazal")
sifre=str(input("krilacak sifreyi giriniz"))
sifres=""
adim=0
while True:
 print("sifreniz deneniyor...",sifres)
 if sifre==sifres:
   break
 else:
   sifres=""
     for i in range(4):
        sifres+=str(choice(sayilar))
           adim+=1
print("sifreniz krilmistir ",sifre,"adimda krilmis",adim)
