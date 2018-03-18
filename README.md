# programlama2

#soru1
x=int(input("toplam satış miktarını giriniz:"))
y=int(input("hammadde maliyetini giriniz:"))
z=int(input("bakım onarım giderlerini giriniz:"))
q=int(input("sevkiyat giderlerini giriniz:"))
w==int(input("satın alınan hizmet giderlerini giriniz:"))
katmadegerciro=(x-(y+z+q+w))
if(int(katmadegerciro)>1000):
    print("işletme katma değer cirosu yüksek.")
elif(int(katmadegerciro)<500):
    print("işletme katma değer cirosu düşük.")
else:
    print("işletme katma değer cirosu normal.")

#soru2
def ikibinonaltiHesapla():
    x=int(input("ikibinonaltı yılında çalışılan süreyi girin:"))
    y=int(input("ikibinonaltı yılında toplam müşteri sayısını girin:"))
    ikibinonalti=(x/y)
    return ikibinonalti
def ikibinonyediHesapla():
    z=int(input("ikibinonyedi yılında çalışılan süreyi girin:"))
    q=int(input("ikibinonyedi yılında toplam müşteri sayısını girin:"))
    ikibinonyedi=(z/q)
    return ikibinonyedi
def farkHesapla():
    x=int(input("ikibinonaltı yılında çalışılan süreyi girin:"))
    y=int(input("ikibinonaltı yılında toplam müşteri sayısını girin:"))
    z=int(input("ikibinonyedi yılında çalışılan süreyi girin:"))
    q=int(input("ikibinonyedi yılında toplam müşteri sayısını girin:"))
    aralarindakiFark=((z/q)-(x/q))
    return aralarindakiFark
    
    
   #soru3
   def ilkAltiAylikKarHesapla():
    x=int(input("yazılım gelirlerini giriniz:"))
    y=int(input("finansman gelirlerini giriniz:"))
    z=int(input("ürün satış gelirlerini giriniz"))
    q=int(input("çalışan maaş giderlerini giriniz:"))
    w=int(input("kira giderlerini giriniz:"))
    e=int(input("donanım giderlerini giriniz:"))
    ilkAltiAylikKar=((x+y+z)-(q+w+e))
    return ilkAltiAylikKar

def sonAltiAylikKarHesapla():
    a=int(input("yazılım gelirlerini giriniz:"))
    b=int(input("sponsorluk gelirlerini giriniz:"))
    c=int(input("ürün satış gelirlerini giriniz"))
    d=int(input("e-ticaret gelirlerini giriniz:"))
    f=int(input("çalışan maaş giderlerini giriniz:"))
    g=int(input("kira giderlerini giriniz:"))
    h=int(input("bakım giderlerini giriniz:"))
    sonAltiAylikKar=((a+b+c+d)-(f+g+h))
    return sonAltiAylikKar

k=int(input("ilk altı aylık karı girin:"))
l=int(input("son altı aylık karı girin:"))
if (int(isletmeninYillikKari)>5000):
    print("işletme çok karda.")
elif (int(isletmeninYillikKari<1000):
      print ("işletme yeterince karda değil.")
else:
      print("işletmenin karı normal.")
      
#soru4

def donembasiStokHesapla():
      x=int(input("koltuk sayısını giriniz:"))
      y=int(input("yatak sayısını giriniz:"))
      z=int(input("dolap sayısını giriniz:"))
      donembasiStok=(x+y+z)
      return donembasiStok

def donemsonuStokHesapla():
      x=int(input("koltuk sayısını giriniz:"))
      y=int(input("yatak sayısını giriniz:"))
      z=int(input("dolap sayısını giriniz:"))
      a=int(input("satılan koltuk sayısını giriniz:"))
      b=int(input("satılan yatak sayısını giriniz:"))
      c=int(input("satılan dolap sayısını giriniz:"))
      k=int(input("alınan koltuk sayısını giriniz:"))
      l=int(input("alınan yatak sayısını giriniz:"))
      m=int(input("alınan dolap sayısını giriniz:"))
      donemsonuStok=((x+y+x)-(a+b+c))+(k+l+m)
      return donemsonuStok

def ortStokHesapla():
     t=int(input("dönembaşı stok bilgilerini girin:"))
     s=int(input("dönemsonu stok bilgilerini girin:"))
     ortStok=((t+s)/2)
     return ortStok
