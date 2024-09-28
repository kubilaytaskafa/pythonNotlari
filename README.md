# pythonNotlari
Necmettin Erbakan Üniversitesi Yönetim Bilişim Sistemleri Bölümü 2023-2024 Bahar Yılı Kendime Ait Python Programlama  Dili Notları

# #               STRİNG FORMATLAMA
# #!format metodu ile print içerisindeki bir stringe değişkenlerimizi ekleyebiliriz. format methodu ile süslü parantez kullanmalıyız
# isim="arif"
# print("hosgeldin {} bey".format(isim))
# # !isim="kubilay"
# # !soyisim="taşkafa"
# # !yas="21"
# # !print("benim adım {} soyadım {} yaşım {}".format(isim,soyisim,yas))
# #!format için kullandığımız süslü parantezlerin içerisine sayı vererek .format içerisindeki indislerin sıralarını değiştirebiliriz.
# #!örneğin aşağıda 0. indis isim oluyor fakat biz ilk süslü paranteze 1 yazarsak artık ilk süslü parantezimizde soyisim olacak
# # !isim="kubilay"
# # !soyisim="taşkafa"
# # !yas="21"
# # !print("benim adım {1} soyadım {0} yaşım {2}".format(isim,soyisim,yas))
# #!format içerisindeki indisleri değişkene bağlayarak süslü parantezde kullanabiliriz.
# #!örnek:
# # !isim="kubilay"
# # !soyisim="taşkafa"
# # !yas="21"
# # !print("benim adım {c} soyadım {a} yaşım {b}".format(a=isim,b=soyisim,c=yas))

# #                     !SAYI FORMATLAMA
# #!sayılarda formatlama methodu ile ekleme işlemi yapabilirsiniz
# # !sonuc=200/7
# # sonuc=200/7
# # print("sonuc={}".format(sonuc))
# # !print("sonuc = {}".format(sonuc))
# #!formatlama yaparken yuvarlama işlemi yapılabilir.sülü parantez içerisinde 1.3 gibi bir sayı yazılabilir. 1.3 değerindeki 3 kısmı virgülden sonra kaç basamak gözükeceğini söyler.
# # !sonuc=200/70
# # !print("sonuc = {s:1.3}".format(s=sonuc))

# #                         ! -F STRİNG METHODU-

# # !fstring sayesinde formatlama yaparken değişken adını direkt olarak süslü paranteze ekleyebiliriz.
# # !isim="kubilay"
# # !soyisim="taşkafa"
# # !yas="21"
# # !print(f"benim adım {isim} soyadım {soyisim} yaşım {yas}")
# # isim=kubilay
# # print(f"hosgeldin  {isim} bey")
# #!örnek uygulamalar
# # !website="http://www.erbakan.edu.tr"
# # !bolum="uygulamalı bilimler fakültesi yönetim bilişim sistemleri (YBS)"
# #!bölüm karakter dizisinde kaç eleman vardır.
# # !sonuc=len(bolum)
# # !print(sonuc)
# #!website değişkenindeki değerden tr bölümünü yazdır. bu kısımda len fonksiyyonu ile kaç karakter olduğunu öğrenip istediğiniz karakteri aralık vererek yazdırabilirsiniz.
# # !sonuc=website[23:25]
# # !print(sonuc)
# #!uzunluk değeri bularak uzunluk üzerinde işlem yaparak bu  işlemi yapabiliriz.
# # !uzunluk=len(website)
# # !print(uzunluk-2:uzunluk)

# #                       !string methodlar
# #!upper methodu = bütün harfleri büyük yazdırır.

# #!lower methodu = bütün harfleri küçük yazdırır.
# #!title methodu = her kelimenin baş harfini büyük yazdırır
# #!capitalize methodu= stringin sadece baş harfini büyük yazdırır.
# #!strip methodu= stringimizin başında boşluk varsa siler
# #!split methodu= stringin her kelimesini liste biçiminde yazdırır.
# #!join methodu: stringimizde her bir indisten sonra karakter eklemeye yarar.
# #!find methodu: aranan kelimenin ilk indeks numarasını geri döndürür.sonuç pozitif bir sayı çıkarsa araığımız kelime vardır.sonuç negatifse aradığımız kelime yoktur.
# #!startswith methodu= stringinizin hangi harfle başladığını öğrenmek için kullanılır. belirli bir karakteri sorgulama yöntemi ile çalışır.sorguladığımız karakter eğer stringimizin ilk harfi ise true değilse false değeri çıkar
# #!endswith methodu=stringinizin hangi harfle bittiğini öğrenmek için kullanılır. belirli bir karakteri sorgulama yöntemi ile çalışır.sorguladığımız karakter eğer stringimizin ilk harfi ise true değilse false değeri çıkar
# #!replace methodu:string içerisindeki karakterleri değiştirebiliriz.
# # isim="kubilay"
# # isim2=isim.replace("k","y")
# # print(isim2)
# #!center methodu: stringimizi ortalamaya yarar. çalışma prensibi olarak belirli bir container tanımlarız ve o container içerisine stringi ortalama işlemi yaparız.

#     #               !LİSTE VERİ TİPİ 
# #!herhangi bir veri tipini listeye çevirmek için split komutunu kulanırız. herhangi bir parametre vermezsek boşluklara göre listeler.
# #!örnek:
# # mesaj="merhaba benim adım kubilay".split()
# # print(mesaj)

# # #!listelerde köşeli parantez kullanırız. farklı veri tiplerini aynı değişkene bağlayabiliriz.
# # #!örnek liste:
# # listeA=["bir",2,True,5.6]
# # print(listeA)

# #                                                 #!listeler üzerinde işlemler-
# # #! iki listeyi birleştirip  tek listede toplayabilirsiniz.
# # #!örnek uygulama:
# # liste1=["bir","iki","üç"]
# # liste2=["dört","beş","altı"]
# # sayilar=liste1+liste2
# # print(sayilar)
# # #!liste içinde liste kullanımı:
# # liste1=["bir","iki","üç",["arifin götü"]]
# # liste2=["dört","beş","altı"]
# # sayilar=[liste1]+[liste2]
# # print(sayilar)

# # #!liste uygulama soruları:
# # #! 1. soru  = "bmw,mercedes,opel,mazda," elemanlarına sahip bir liste oluşturuunuz
# # arac=["bmw","mercedes","opel","mazda"]
# # #! 2. soru =  "liste kaç elemanlıdır."
# # print(len(arac))
# # #! 3. soru =listenin ilk ve son elemanlarını gösteriniz.
# # print(arac[0])
# # print(arac[-1])      
# # #! 4. soru= mazda elemanını toyota olarak değiştiriniz.
# # arac[-1]="toyota"
# # #! 5. soru = mercedes listenin bir elemanı mıdır sorunuz
# # sonuc="mercedes" in arac
# # #!6. soru listenin ilk 3 elemanını alın 
# # print(arac[0:4])
# # #! 7. soru = listenin -2 indeksindeki değer nedir?
# # print(arac[-2])
# # #! 8. soru= listenin son 2 elemanı yerine  toyota ve renault elemanlarını ekleyin
# # arac[-2:]=["toyota","renault"]
# # #! 9.soru = listenin üzerine audi ve nissan elemanlarını ekleyin
# # sonuc=arac+["audi","nissan"]
# # print(sonuc)
# # #!10. soru listenin son elemanını silin 
# # del arac[-1]
# # #! 11. soru =liste elemanlarını tersten yazdırın
# #* sonuc=arac[::-1]
# # #! 12. soru =aşağıdaki verileri bir liste içinde saklayınız
# # #! öğrencia "alper turan 2010  70 60 70 " , öğrencib = bilge yiğit 1999 80 80 70  ögrencic= tuna boylu 1998 80,70,90
# #* ögrenciA=["Alper Turan",2010,[70,60,70]]
# #* ogrenciB=["Bilge Yiğit",1999,[80,80,70]]
# #* ögrenciC=["Tuna Boylu",1998,[80,70,90]]
# # #!13. soru liste elemanlarını ekrana yazdırın
# # print(ögrenciA)
# # print(ogrenciB)
# # print(ögrenciC)
# # #!14. soru öğrenci a nın ismini ve not ortalamasını yazdırın
# # # ort=(ögrenciA[2][0]+ögrenciA[2][1]+ögrenciA[2][2])/3
# # # print(ögrenciA[0]+" ","not ortalaması:",ort)

#                     #! -LİSTE METHODLARI-
# #! örnek listeler
# #* harfler=["a","b","c","d"]
# #* sayilar=[1,2,3,4,5,6,7]
# #! min methodu en küçük değeri bulur. harflerin pc üzerinde sayısal bir değeri vardır. min max değerleri harflere uygulanırsa asli kod tablosuna göre şekillenir.
# #! en küçük sayısal değere sahip harf a en büyük sayısal değere sahip ahrf z dir. min max işlemi bu değerlere göre işlme alır.
# #! büyük harflerde: büyük  A sayısal değeri 65 ten başlar ve birer birer artar
# #! küçük harflerde  küçük a sayısal değeri 97 den başlar ve birer birer artar.
# #! bir harfin büyük yazımı küçük yazımından sayısal değer olarak daha küçüktür.
# # deger=min(sayilar)
# # print(deger)
# # deger=min(harfler)
# # print(deger)
# # #! max methodu en büyük değeri bulur.
# # deger=max(sayilar)
# # print(sayilar)
# # deger=max(harfler)
# # print(deger)
# # #! .append methodu= bir listeye herhangi bir elemanı eklemek için kullanılır. listenin en sonuna ekler
# # sayilar2=[1,2,3,4]
# # sayilar2.append(5)
# #* print(sayilar2)
# # #! .insert komutu = istenilen indexe ekleme yapmak için kullanılır.
# #* sayilar3=[1,2,3,4]
# #* sayilar3.insert(0,5)
# #* print(sayilar3)
# # #?insert içerisinde indexi - ile verirsek sondan ekleme yapar fakat son eleman olmaz son eleman daima aynı kalır.
# sayilar4=[1,2,3,4]
# sayilar4.insert(-1,5)
# print(sayilar4)
# #! .pop() methodu= liste içerisinden eleman silmeye yarar.parantez içerisine bir index vermezsek listenin son elemanını siler.
# #* sayilar5=[1,2,3,4]
# #* sayilar5.pop()
# #* print(sayilar5)
# #* #?


# #! .remove komutu = doğrudan karakter silmeye yarar. index yerine silinecek karakteri ekleyebiliriz.
# liste=[1,2,3,4,5]
# liste.remove(2)
# print(liste)




# #! .sort komutu = sayısal olarak sıralama yapar. harfler üzerinde sort uygulanırsa alfabetik sıraya sokar
# liste2=[1,4,5,2,3,6]
# liste2.sort()
# print(liste2)
# liste3=["arda","arif","kubilay"]
# liste3.sort()
# print(liste3)



# #! .reverse methodu: listenin sıralamasını tersten yapar 

# liste3.reverse()





# #!len methodu = listenin kaç elemanlı olduğunu bulur.






# #! .count methodu: bir elemandan liste içerisinde kaç tane var onu bulur.




# #! . clear methodu = liste içerisindeki elemanların hepsini siler.

# #* [09:41, 18.03.2024] Arda Ybs: # Tuple veri tipi . birden çok öğeyi tek bir değişkende depolamak için kullanılır.
# #* #Tuple : Sıralı ve değiştirilemez bir koleksiyondur ve yuvarlak parantez ile gösterilir.

# #* demet = (1,"Arda",4.345)
# #* print(type(demet))
# #* print(demet[0])

# # *list = ["Ali","veli"]
# # *tuple = ("Damla","Ayşe","Ayşe")
# # *list[0] = "Ahmet"
# # *print(list[0])

# # *print(tuple.count("Ayşe"))
# # *print(tuple.index("Ayşe"))

# # *isimler = ("alper","cihan","turan")
# # *sonuc = isimler + tuple
# # *print(sonuc)
# # *[10:41, 18.03.2024] Arda Ybs: # Dictionaryler , veri değerini 'key:'value' ciftlerinde depolamak için kullanılır.

# # *#Dictionary,sıralı*,değşken ve tekrara izin vermeyen bir veri tipidir.
# # *#Süslü parantez ile yazılır ve anahtarları ve değerleri vardır.

# # *# key - value
# # *# 42 => Konya
# # *# 26 => Eskişehir
# # #* 06 => Ankara


# #* #Liste Şeklinde Yazdırma.
# # *# sehir = ["Konya","Ankara"]
# # *# plaka = [42,6]
# # *# print(plaka[sehir.index("Konya")])


# #* plakalar = {"Konya":42,"Ankara":6,"Eskişehir":26}
# #* print(plakalar["Konya"])

# # *plakalar["İstanbul"] = 34
# # *print(plakalar)
# # *print(plakalar["İstanbul"])

# #* kullanicilar = {
# #*     "alperturan":{
# # *        "yaş":35,
# #  *       "email":"alperturan@gmail.com",
# #   *      "adres":"Konya",
# #    *     "Telefon":"123123"
# #   *  },
# #   *  "cihanturan":{
# #   *      "yaş":18,
# #   *      "email":"cihanturan@gmail.co…
# # *[12:54, 18.03.2024] Arda Ybs: # Value tipindeki veriler => string , number (bellekte verinin kendisi depolanır.)

# #* x = 5
# #* y = 25

# # * x = y
# # * y = 10
# # * print(x,y)

# # * #reference veri tipleri => List (bellekte verinin kendisi değil adresi depolanır.)

# # * a = ["elma","armut"]
# # * b = ["elma","armut"]
# a=5
# b=a
# a+=5
# print(b)

# a=[1,2,3]
# b=a
# a.append(4)
# print(b)
# # * a = b
# # * b[0]="üzüm"
# # * print(a,b)

# #*      -atama operatörleri-
# #! x=5  # değişkene değer atadık
# #! y=20  # değişkene değer atadık
# #! z=16  # değişkene değer atadık
# #! x,y=y,x  #! x ile y değerini değiştirdik

# #!  x+=5  x değerine 5 ekledik   x=x+5
# #!  x-=5 x değerinden 5 çıkardık x=x-5
# #! x*=5 x değerini 5 ile çarptık 
# #! x/=5 x değerini  5 e böldük
# #! x%=5 x değerinin 5 ile bölümünden kalanı bulduk
# #! x//=5 x değerinin 5 ile bölümünün tam ksımı
# #! x**=5 x üzeri 5 anlamına gelir.

# #! değer= 1,2,3 ataması yaparsak tuple veri tipinde atanma yaparız
# #! x,y,z= deger dersek indekslere göre yani soldan sağa x y z değerlerine 1,2,3 değerleri atanacak x 1 y 2 z 3. 
# #! ancak bu işlemi yapmak için tuple liste eleman sayısı ile değişken sayısı aynı olmalıdır.

# #! degerler= 1,2,3,4,5 
# #! x,y,*z=degerler  bu atamada x 1 y 2 değerini alacak z değişkeni başında * olduğu için geri kalan değerler z ye liste şeklinde tanımlanacak
# #! liste olduğu için indekse göre değer alabiliriz.
# #! print(x,y,z[1])  run yaparsak z listesinin 1. indexsini alır


# # x,y,*z=(1,2,3,4,5)
# # print(z)

# #*     -KARŞILAŞTIRMA OPERATÖRLERİ-

# #!  YAZDIĞIMIZ PROGRAMLARDA PROGRAMIN GİDİŞATINI BELLİ KOŞULLAR ALTINDA FARKLI ADIMLARA  YÖNLENDİRMEK İSTİYORSAK KARŞILAŞTIRMA OPERATÖRLERİNİ KULANIRIZ.
# #! KARŞILAŞTIRMA SONUCUNDA BOOLEAN TİPİNDE TRUE(DOĞRU) YA DA FALSE(YANLIŞ) DEĞERİNİ ALIRIZ. BU DEĞERLERE GÖRE İŞLEM ALIRIZ
# #!ÖRNEKLER:
# #* kullaniciAdi,sifre="alican",123456
# #* a,b,c,d=5,5,10,4
# #* sonuc=(a==b) # ? sonucumuz true olacak
# #* sonuc=(a==c) #? sonucumuz false olacak
# #** sonuc =("alican"==kullaniciAdi) #? sonucumuz true olacak ==> eşit
# #* *sonuc=("alican"==sifre)  #? sonucumuz false olacak  ==> eşit
# #** sonuc=(a!=b)  #? sonucumuz false olacak ==> eşit değil
# #* sonuc=(a!=c) #? sonucumuz true olacak  ==> eşit değil 
# #* sonuc=(a>c) #? sonucumuz false olacak  ==> büyük
# # *sonuc=(a<c) #? sonucumuz true olacak  ==>> küçük
# # *sonuc=(a>=b) #? sonucumuz true olacak   ==> büyük eşit
# # *sonuc(a<=c) #? sonucumuz true olacak   ==> küçük eşit
# #* sonuc(True+False+40)   # #? sonucumuz 41 olacak true matematik değeri 1 false matematik değeri 0 
# # print(True+True+40)
# #! karşılaştırma operatörü uygulamaları
# #! girilen 2 sayıdan büyük olanı bulan program
# #* a=int(input("A sayısını giriniz:"))
# #* b=int(input("b sayisini giriniz"))
# #* sonuc(a>b)
# #* print(a,"değeri",b,"değerinden büyük mü?",sonuc)
# #! kullanıcından 2 vize(%50) ve iki final (%50) notunu alıp ortalama heaplayınız eğer ortalama 50 ve üzerinde ise geçti değilse kaldı yaz
# #* vize1=float(input("birinci vizeyi giriniz"))
# #* vize2=float(input("ikinci vizeyi giriniz"))
# #* final=float(input("final notunu giriniz"))
# #* ortalama=(((vize1+vize2)/2)*0.5)+(final*0.5)
# #* print("not ortalamanız",ortalama,"geçme durumunuz",(ortalama>=50))
# #! girilen sayının tek mi çift mi oldupunu bulan program
# #* a=int(input("sayi giriniz:"))
# #* tekCift=(a%2==0)
# #* print("girilen sayının çift olma durumu:",tekCift)

# #! parola ve email bilgisini isteyip doğruluğunu kontrol ediniz
# #* email="kasapisoPolatli06@gmail.com"
# #* parola="canimPolatlim"

# #* mailSor=input("email giriniz:")
# #* ParolaSor=input("parola giriniz:")

# #* mailsonuc=(email==mailSor.lower().strip) #lower methodu ile kullanıcı emaili büyük harfle yapsak bile küçüğe çevirir. strip methodu ile input girilirken başta sonda boşluk varsa siler
# #* parolasonuc=(parola==ParolaSor)

# #* print("email sorgu sonucunuz:",mailsonuc,"parola sorgu sonucunuz:",parolasonuc)

# #!              -MANTIKSAL OPERATÖRLER

# #* X=5
# #* sonuc(5<x<10) #x değeri 5 ile 10 arasında mı matematiksel gösterimi. bunu kodlama ile gösteremeyiz.
# #*bunu yapmak için mantıksal operatör kullanmak gerekir.
# #! and operatörü : 2 veyahut daha fazla sınamadan en az biri false ise sonuç false olur. matematik mantık işlemindeki ve işlemine benzer
# #! ö1 
# #* x=5
# #* sonuc=(x>5) and (x>10) 
# #* print(sonuc)
# #!ö2
# #* hak=0
# #* devam="e"
# #* sonuc=(hak>0)and(devam=="e")
# #! or operatörü: iki veya daha fazla sınamadan en az birisi true ise sonuç true olur. matematikteki mantık işlmeindeki veya işlemine benzer
# #? true true = true
# #? true false = true
# #? false true = true
# #? false false = false
# #! ö1
# #* x=5 
# #* sonuc=(x>5) or (x<10)
# #* print(sonuc)
# #!   not operatörü = sonuc true ise not ile false, false ise not ile true olur.
# #? not(true)= false
# #? not(false)= true
# #! ö1
# #* x=5
# #* sonuc= not(x<3)
# # *print(sonuc)
# #! soru 1 : x 5 ile 10 arasında bir çift sayı mıdır?
# #* x=5
# #* sonuc=((x>5)and(x<10)) and (x%2==0)
# #* print(sonuc)
# #! soru 2 : girilen bir sayının 0-100 arasında olup olmadığını kontrol ediniz
# #* a=float(input("sayi giriniz:"))
# #* sonuc=(a>0) and (a<=100)
# #* print(a,"sayisinin 0 ile 100 arasinda olma durumu:",sonuc)
# #! soru3 = girilen 3 sayiyi büyüklük olarak sıralayınız
# #* a=int(input("sayi giriniz:"))
# #* b=int(input("sayi giriniz:"))
# #* c=int(input("sayi giriniz:"))
# # *sonuc= (a>b) and (a>c)
# #* print(a,"en büyük sayıdır:",sonuc)
# #* sonuc=(b>a)and(b>c)
# #* print(b,"en büyük sayidir:",sonuc)
# #* sonuc=(c>a)and(c>b)
# #* print(c,"en büyük sayıdır:",sonuc)

# #!                    -identity ve membership karşılaştırması
# #! identity= is olarak kullanılır ve referance tipindeki değişkenin adres karşılaştırmasını yapar.
# #! ö1:
# #* x=y=[1,2,3]
# #* z=[1,2,3]
# #? print(x==y) ==> değerler karşılaştırılır. true
# #? print(x==z)  ==> değerler karşılaştırıldı true
# #? print(x is y)   ==> referance adresler karşılaştırıldı  True
# #? print(x is z) ==> referance adresi karşılaştırıldı False
# #* x=[1,2,3]
# #* y=[2,4]

# #* del x[2]     #? x değişkeni 2. indeksi sil      

# #* y[1]=1    y 1. indekse 1 ekle 
# #* y.reverse ()  ters çevir 
# #* print(x==y)     true
# #* print(x is y)  false
# #* print(x is not y )   false 
# #! membership = in olarak kullanılır. liste tipindeki değişkenler içerisinde herhangi bir elemanın olup olmadığını kontrol eder.
# #* x=[1,2,3]
# #* print(1 in x) 
# #! ö2
# #* isim="ali"    #! string tipindeki bir değişkende her bir karakteri de sorgulayabiliriz. string elemanlar bir dizi değişkenidir.
# #* print("a" in isim)
# #! ö3
# #* isim="ali"
# #* print("e" not in isim)  içinde değil mi sorgusunu yapar.

# #!              -KOŞUL İFADELERİ (İF,ELSE,ELİF)
# #! İF... ELSE YAPISI: PROGRAMIN BELLİ KOŞULLAR ALTINDA AKIŞINI DEĞİŞTİRMEK İÇİN KULLANILIR.
# #! ifte he daim karşılaştırma yapılır.
# #! kullanımı 
# #? if (karşılaştırma):
# #?     if bloğu
# #? else:
# #?    if karşılaştırması doğru değilse çalışacak 
# #!örnek
# # *if (2<3):
# # *    print("merhaba")
# #!örnek2
# #* kullaniciAdi=input("kullanici adiniizi giriniz:")
# #* sifre=int(input("sifreyi giriniz:"))
# #* if (kullaniciAdi=="kubilay") and (sifre==1071):
# #*         print("hosgeldiniz",kullaniciAdi,"bey")
# #* else:
# #*     print("yalnis islem yaptiniz")   
# #! örnek 3
# #* kullaniciAdi=input("kullanici adiniizi giriniz:")
# #* sifre=int(input("sifreyi giriniz:"))
# #* if (kullaniciAdi=="kubilay"):
# #*      if(sifre=="1234"):
# #*          print("hosgeldiniz")
# #*      else:
# #*          print("sifreyi yanlis girildi...")
# #* else:
# # *     print("kullanici adi yalnis girildi...")   
# #! if else ile 2 durum kontrol edilir. eğer birden fazla if durumunu kontrol etmek istersek ilk iften sonraki diğer if koşullarını elif ile yazmalıyız.
# #! yapı : if - elif- else
# #? if(karsilastirma):
# # ?    if blogu
# #? elif (karsilastirma):
# #?     ikinci if in blogu
# #? istediğin kadar elif yazabilirsin
# #? else:
# #?     if veya elif koşulları sağlanmazsa calisacak blog
# #!örnek1.
# #* a=int(input("1. sayi gir:"))
# #* b=int(input("2. sayi gir:"))
# #* if (a>b):
# #*     print(a,"büyüktür",b,"den/dan")
# #* elif(b>a):
# #*     print(b,"büyüktür",a,"dan/den")
# #* else:
# #*     print("sayilar esittir...")
# #! örnek:2 bir sayının pozitif mi negatif mi yoksa 0 mı olduğunu kontrol eden program
# #* a=int(input("sayi giriniz:"))
# #* if (a>0):
# #*     print=(a,"sayisi sifirdan büyüktür")
# #* elif (a<0):
# #*     print(a,"sayisi negatiftir")
# #* else:
# #*     print("sayi sifirdir.")
# #? break -continue komutları
# # break = döngüden çıkış yapmayı sağlar 
# # continue = sadece o anki döngü turunu iptal eder

#örnek:
# x=0

# while x<5:
#     x+=1
#     if x ==2:
#         continue
#     print(x)

#örnek 1 den 100 e kadar olan çift sayilarin toplamını bulacak program
#* x=0
#* toplam=0
#* while x<=100:
#*     x+=1
#*     if x%2==1:
#*         continue
#*     toplam=toplam+x
#* print(toplam)
#?                              -döngü fonksiyonları-
# range() fonksiyonu -->>> bir kod kümesinde belirli sayıda döngü yapmak için range() fonksiyonunu kullanırız. 
# range fonksiyonu varsayılan olarak 0 an başlayan ve birer birer artan bir sayı dizisi oluşturur.
# ve belirtilen bir sayıda biter. (belirtilen sayı dahil değildir.)
# başlangıç değerini bir parametre ekleyerek belirtmek  mümkündür.
#!örnek == range(2,6)  --> 2 ile 6 arasındaki değerler anlamına gelir ancak 6 dahil değildir.
# range fonksiyonu varsayılan olarak  diziyi bir arttırır ancak 3. bir parametre ekleyerek artış miktarını değiştirebiliriz.
#! örnek --> range(2,10,2) sona eklenen 2 değeri artış miktarı olur ve dizi oluşurken ikişer olarak artar.
#örnek:
#* for i in range(50,100,20):
#*     print(i)
#* print(list(range(50,100,20)))   # tek satırda range ile değerler üretip liste biçiminde yazdırma
# for döngüsü ile kullanılabilecek işlemler
#? else: bir for döngüsündeki else  anahtar sözcüğü döngü bittiğinde yürütülecek bir kod bloğunu belirtir
#? ancak döngü bir break ifadesi ile durdurulursa else bloğu yürütülmez    
#örnek.
#* for i in range(6):
#*     print(i)
#* else:
#*     print("sonunda bitti..:")    
# enumerate() fonksiyonu kendisine parametre olarak  verilen değer hakkında bize 2 farklı bilgi verir.   
# bir öge ve bu ögeye ait index numarası döndürür.
#! örnek enumerate kullanmadan index numarası ve öge alma 
#* index=0
#* mesaj="merhaba"
#* for harf in mesaj:
#*     print(f"index:{index} harf:{harf}")
#*     index+=1    
#! enumerate ile index numarası ve öge alma     
#* mesaj="merhaba"
#* for i in enumerate(mesaj):
#*     print(i)

#zip fonksiyonu= 2 ya da daha fazla listenin öğelerini birbiriyle eşleştirir.
#* liste1=[1,2,3,4,5]
#* liste2=["a","b","c","d","e"]
#* liste3=[100,200,300,400,500]
#* print(list(zip(liste1,liste2,liste3)))
# *for i in zip(liste1,liste2,liste3):
# *     print(i)    
#* for a,b,c in zip(liste1,liste2,liste3):
#*      print(a,b,c)
#!örnekler
#! boş bir listeyi for döngüsü ile doldurma
#* sayilar=[]
#* for x in range(10):
#*     sayilar.append(x)
#* print(sayilar)
#* # farkli kullanim
#* sayilar=[x for x in range(10)]
#* print(sayilar)
#! 0 dan 10 a kadar olan sayilarin karelerini yazdırma
#* for i in range(10):
#*     print(i**2)
#* #farkli kullanim 
#* sayilar=[x**2 for x in range(10)]
#* print(sayilar)
#! 3 ün katlarının karesini alan program
#* sayilar=[x*x for x in range(10) if x%3==0]
#* print(sayilar)
#! string ifadenin harflerini listeye ekleme
#* mesaj="merhaba"
#* listem=[]
#* for harf in mesaj:
#*     listem.append(harf)
#* print(listem)
#!farkli kullanım 
#* mesaj="merhaba"
#* listem=[harf for harf in mesaj]
#* print(listem)
#! yaşları hesaplayan program
#* yillar=[1983,1999,2008,1959,1986]
#* yaslar=[2024-yil for yil in yillar]
#* print(yaslar)
# iç içe for göngüleri  içteki for döngüsü 3 defa çalıştığında dıştaki for döngüsü bir kere çalışır.
# sonuc=[]
# for x in range(3):
#     for y in range(3):
#         sonuc.append((x,y))
# print(sonuc)
# # farkli kullanim 
# sayilar=[(x,y) for x in range(3) for y in range(3)]
# print(sayilar)


#! soru  gönderilen br kelimeyi belirtilen kez ekranda gösteren fonksiyonu yazınız

# def yazdir(kelime,adet):
#     print(kelime*adet)


# yazdir("arif\n",4)  # arifi 4 kere alt alta yazacak 

#! soru  kendine gçnderilen sınırsız sayıdaki parametreyi bir listeye çeviren fonksiyonu yazınız.

# def listeyecevir(*parametre):  # bbaşa yıldız koymamızın sebebi sınırsız parametre almak olacak

#     liste=[]

#     for prm in parametre:
#         liste.append(prm)
#     return liste 

# sonuc=listeyecevir(10,2,3,4,5,6,7,8,9,0)

# print(sonuc)


# # # gönerilen 2 asayı arasındaki tüm asal sayıları bulan fonksiyonu yazınız.
# sayi1=int(input("1. sayiyi giriniz..:"))
# sayi2=int(input("2. sayiyi giriniz..:"))

# def asalBul(sayi1,sayi2):
#     for sayi in range(sayi1,sayi2+1):
#         if sayi>1:
#             for i in range(2,sayi):
#                 if sayi%i==0:
#                     break
#                 else:
#                     print(sayi)

# asalBul(sayi1,sayi2)

# kendisene gönderilen bir sayinin tam bölenlerini bir liste şeklinde gösteren fonksiyonu yazınız.
#* sayi=int(input("sayi giriniz..:"))

#* def tambolen(sayi):
#*     tambolenliste=[]
# *    for bolen in(2,sayi+1):
# *        if sayi%bolen==0:
#  *           tambolenliste.append(bolen)
        
# *    return tambolenliste

#* sonuc=tambolen(sayi)

#* print(sonuc)


#  ?     lambda fonksiyonu 
# isimsiz bi fonksiyonu ifade eder.
# bir lambda fonksiyonu herhnagi bir sayıda bağımsız değişken alabilr. ancak yalnızca bir ifadeye sahip olur.
# başk Bİ fonk içinde anonim bir fonk olarak kullanıldığında gerçek işlevi yerine getirir.
#!kullanımi
#!fonksiyon_ismi=lambda değişken: işlem

#örnek :  lambda kullanmadan kare alma fonksiyonu ve lammbda ile kare alma fonksiyonu
#! lambdasız
#* def kare(sayi):
# *    return(sayi**2)

#* sayi= int(input("bir sayi giriniz..:"))

#* print(kare(sayi))
#! lamda ile
#* kare=lambda sayi: sayi**2

#* sayi=int(input("bir sayi giriniz..:"))
#* print(kare(sayi))

#örnek

# *def xcarp(x):
# *    return lambda a:a*x
#* ikikatla=xcarp(2)
#* ücekatla=xcarp(3)

#* print(ikikatla(2))
#* print(ücekatla(2))

#? filter fonksiyonu=  tekrar edebilir bir nesnedeki ögeleri hariç tutmak için kullanılır.

# örnek verilen bir listedeki tek elemanları listelemek

#* liste=[1,2,3,4,6,7,9,10]

#* yeniliste=list(filter(lambda x:(x%2==1),liste))

#* print(yeniliste)

#?           -LOCAL AND GLOBAL SCOPE(YEREL VE GLOBAL DEĞİŞKENLER)-
# bir değişken yalnızca oluşturulduğu bölgenin içinden kullanılabilir. buna scope (kapsam) denir.

#!  local scope (yerel kapsam)= bir fonksiyonun içinde oluşturlan bir değişken o fonksiyon için geçerli olur
# ! global scope (evrensel kapsam) = python prgoramnının ana bölgesinde oluşturan değişkenlerdir. hem bir fonk içinde hem de normal olarak kullanıabilir.


#* x="global x"

#* def fonksiyon():
#*     x="local x"

#* fonksiyon()
#* print(x)

#!  global scope 
# *x="global x"

# *def fonksiyon():
#     #! local scope
# *    x="local x"
#  *   print(x)    def bloğu içinde print aldığımız için local scope u yazdırır.

#* fonksiyon()

#* print(x)  blok dışında yazdığımız için global yazar.

#! local bir scope olmazsa blok içinde de global scope esas alınır.

#!  global anahtar kelimesi ile local bir scope u global scope a çevirebiliriz.
# örnek

#* ad="arif"

# *def AdDegistir(yeni_ad):
# *    global ad   # local olan ad değişkeni artık global oldu.
# **    ad=yeni_ad
#  *   print(ad)

#* AdDegistir("kubilay")
#* print(ad)

# ?  iç içe fonksiyonlarda global ve yerel değişkenler

#* isim="global string"

#* def selam():
#*     isim="arda"
#*     def merhaba():
#*         print("merhaba "+isim)
#*     merhaba()

#* selam()

# ! her bloğun kendine özel local değişkeni vardır. bloğun kendi local değişkeni yoksa bir üsrt bloğa gider eğer hiçbir local değişken yoksa global scope a bakar.

# örnek

#* x=50

#* def test():
# *    global x
# *    x=100
# *    print(f"x:{x}")
#*     print(f"yeni x {x}")
    
#* test(x)
#* print(f"x:{x}")



#  ?           python class ve nesneleri (oop (object oriented programming))
#!  python nesne yönelimli bir programlamadır.
#!  nesneler sınıflar altında tanımlandığı için sınıflar temel alınarak  programlama gerçekleştirilir.

#! class => Person  classımız varsa kişiler kendi içinde hangi özelliklerde bulunabilir.
#! class Person(name,department,):
#! instance(object)= liste[1,2,3]   aslında oluşturduğumuz listeler list classı içerisinde türetilen bir objedir.

#!  class oluşturma :
#!  class ooluşturmak için class:  anahtar kelimesini kullanacağız.
#! örn  class Person:
#! class adları genellikle büyük harfle başlarız.
#! classlarda  bir özellik tanımlamazsak syntax eror alırız.
#! pass kavramı:  attributes ve method tanımlamadan classı bırakmak için pass kullanırız. pass sayesinde hata almadan o classı geçeriz.

#!  -obje oluşturma-  (object instance nesne hepsi aynı anlam)

#* class Person:
#*     pass 

#* p1=Person()
#* print(p1)

#! yukarıdaki işlemde bir değişkene Person classını bağlar. biz her Personu classını tanımladığımızda farklı bir nesne üretmiş oluruz.

                                        #? -class da attribute tanımlama-

#! class attribute (sınıfa dair özellikler demektir. bu özellikler objeye ait özellikten üstündür.)
# class attribute özellikleri bütün objelerimiz için geçerli olacak.
# şimdi p1 ve p2  için adress tanımlayacağız.
# class Person():  
#     adress="MERAM/KONYA"    #OBJELERİMİZ İÇİN GEÇERLİ OLAN YAPILAR İÇİN KULLANIRIZ.


#! -object attribute-
# p1 ve p2 nesnelereine bir object attribute tanımlayacağız.

        
#     def __init__(self,name,year):    #yapıcı method: constructor aşağıda tanımlanan nesneler için yapılan tanımlamaları çalıştırmak
#         # init methodu çalışmadığı anda class çalışmaz
#         self.name=name 
#         self.year=year
#         print("init methodu çalıştı")

     

# p1=Person("ALİ",1990)  #BURADA BİR NESNE OLUŞTURDUK PARAMETRELERİMİZİ CLASS İÇİNDEKİ METOHDUN ALDIĞI PARAMETRELERE GÖRE İŞLEM YAPTIK.
# p2=Person("ayşe",1995) 

#* p1.name="ahmet" p1 in adı değişti
#* p.adress="ÇANKAYA/ANKARA" P1 İN ADRESİ DEĞİŞTİ

# print(p1.name,p1.adress)
# print(p2.name,p2.adress)

                    #? METHOD OLUŞTURMA
#  METHOH TANIMLAMAK İÇİN DEF METHODİSMİ(): KULLANIRILIR.
# METHOD KİME HİZMET EDECEKSE ONUN REFERANSINI İÇERİR.
# ÖRN:
# def intro(self):
#  print("merhaba,benim adım "+self.name)

#ÖRNEK YAŞ HESAPLAMA METHODU:
# PARAMETREMİZ NE İSE ONA GÖRE İŞLEM YAPARIZ.
#* def yasHesapla(self):
#*     return 2024-self.year

# ! örnek daire isminde class tanımlayıp dairenin yarıçapı ve alanını hesaplayan uygulama

#* p:3,14 
#*  cevre 2pr
#*  alan 2prkare

#* class Circle:
#*     # class object attribute
#*     pi=3.14
#*     # constructor
#*     def __init__(self,yaricap=1):
#*         self.yaricap=yaricap

# *    def cevre(self,):
# *        return 2*self.pi*self.yaricap
        
# *    def alan(self,):
# *        return self.pi*(self.yaricap**2)


#* islem1=Circle(2)
#* islem2=Circle(3)

#* print(islem1.cevre())
#* print(islem1.alan())
#* print(islem2.cevre())
#* print(islem2.alan())

                #?   İNHERİTANCE (KALITIM) KONUSU
#! PERSON İSMİNDE CLASS OLUŞTURDUK ÖZELLİKLERİ => NAME,LASTNAME,AGE,EAT(),RUN(),DRİNK()
#! BAŞKA BİR CLASS TANIMLADIK STUDENT,TEACHER => BURADA PERSONDAKİ TÜM ÖZELLİKLERİ KULLANABİLİRİZ.

#! BİR CLASSDAKİ ÖZELLİKLERİ DİĞER CLASSLARDA ALIP KULLANMAYA İNHARİTANCE MİRAS ALMA YANİ KALITIM DENİR.

#! KULLANIMI:   STUDENT(PERSON), TEACHER(PERSON) KODLAMASIYLA STUDENT VE TEACHER CLASSLARININ PERSON CLASSINDAN MİRAS ALMASINI SAĞLAR.
#! FAKAT STUDENT VEYA TEACHER İÇİN TANIMLANAN ÖZELLİKLER PERSONU İLGİLENDİRMEZ.

#!  ÖRNEK KULLANIM :

#* class Person():
#*     def __init__(self):
    
#*         print("person sınıfı oluşturuldu")


#* class Student(Person):
#*     def __init__(self):
#*         Person.__init__(self)   # person classının yapıcı metohdunu çağırmamız lazım
#*         print("student sınıfı oluşturuldu")

#* p1=Person()
#* s1=Student()

# ÖRNEK KULLANIM:

#* class Person():
# *     def __init__(self,name,lastname):
# **         self.name=name
# *         self.lastname=lastname
# *         print("person sınıfı oluşturuldu")

# *     def ben_kimim(self):
# *          print("ben bir PERsonum")
     
    

#* class Student(Person):
# *     def __init__(self,name,lastname,ogrencino):  #parametrelerimizi ekliyoruz. person classındaki değerleri çalıştırabilmek için
# *         Person.__init__(self,name,lastname)   # person classının yapıcı metohdunu çağırmamız lazım
# *         self.ogrencino=ogrencino
# *         print("student sınıfı oluşturuldu")
# *     def merhaba():
#*         print("merhaba ben bir öğrenciyim")


#* class Teacher(Person):
# *    def __init__(self, name, lastname,brans):
# *        Person.__init__(self,name,lastname)
# *        self.brans=brans
# *    def ben_kimim(self):
# *        print(f"ben bir {self.brans} öğretmeniyim")

# *p1=Person("kubilay","taşkafa")
# *c1=Student("kubilay","taşkafa",23410051044)
# *o1=Teacher("şeyma","gül","matematik")

# *print(p1.name)
# *print(p1.lastname)
# *print(c1.name)
# *print(c1.lastname)

#* p1.ben_kimim()
#* c1.ben_kimim()


#* print(o1.name,o1.lastname,)
#* o1.ben_kimim()

#? override( geçersiz kılma ) 
#? bir class içerisinde tanımladığımız bir methodu aynı isimle miras alan alt methodlarda kullanırsak altm modüldeki fonksiyon üst modüldeki 
#? fonksiyonu geçersiz kılar. bu işleme oveeride ddenir.
                        
                                                #? - MODÜLLER -
#? hazır modül kullanımı 

#? modül kullanma yöntemleri 
# ! 1. yöntem
import math

#? deger=dir(math)     # dir çağırmış olduğumuz modüldeki bütün komutları verir.
#? print(deger)

# ?deger=help(math)    #çağırmış olduğumuz modül hakkında bize yardım eder.

#? deger=help(math.factorial)  #modülün içindeki belirli bir fonk hakkında yardım  eder.

# math modülü içindeki fonkların kullanımı 

# deger=math.sqrt()   #karekök alma
# deger=math.factorial()   #faktöriyel
# deger=math.floor()     #aşağı yuvarlama

# # !    import edilecek modüle takma ad vermek 

# import math as islem    #artık math kullanmak yerine islem kullanabilirsiniz.

# #!  3. yöntem  from methodu
# #? bir modülden sadece belirli fonkları import edebilirsiniz
# from math import factorial   #math dan sadece factoriel fonksiyonunu import ettik 

# #? eğer import kısmında * kullanırsanız  bütün modülü import eder,

# # eğer mdoül altındaki bir fonksiyon ile aynı isimle bir fonksiyon da bizler oluştutursak python en son hangi fonk oluşturulmuşsa 
# # o fonksiyonu kullanır.


# random modülü 
import random 

#? sonuc=random.random()    # sıfırla 1 arasında bir sayı üretir.
#? sonuc=random.random()*100   # sıfırla 100 arasında bir sayı ü
#? sonuc=random.uniform()   #belirtilen 2 sayı arasında random bir sayı üretir.
#? sonuc=random.randint()   #belirtilen 2 sayı arasında random bir TAMSAYI ÜRETİR.

#!  listeden random veri alma 
# liste=["ali","veli","hasan","arda","ahmet"]
# sonuc=liste[random.randint(0,len(liste)-1)]   #0 ile liste içindeki eleman sayısı arasında random bir tam sayı üretir ve indexi o tam sayı olan değeri çeker
# print(sonuc)

#choice fonksyionu yukarıdaki işlemi daha kolay yaparr.
#* liste=["ali","veli","hasan","arda","ahmet"]
#* sonuc=random.choice(liste)
#* print(sonuc)

# bu işlemi string ifadeelrde de yapabilirsiniz her bir index ifade bir listedir. stringdeki her bir harf listenin bir elemanıdır index numarası vardır.
liste=list(range(10))  # sıfırla 10 arasında sayılar alınır ve liste formatına dönüştürülür.
random.shuffle(liste)   # listenin elemanlarını karıştırarak verir.
sonuc=liste
print(sonuc)


        # ? modül oluşturma 
#* number=10
#* numbers=[1,2,3,4]
#* Person={
#*     "name":"ali",
#*     "age":21,
#*     "city":"istanbul"

#* }

#* def fonk(x):
#*     print(f"x:{x}")

#* class Person:
#*     def konus(self):
#*         print("Konuşuyorum")

#* #bu oluşturduğumuz py uzantılı dosyayı aynı yerdeki başka bir py uzantılı dosyada çağırıp kullanabiliriz. 
#* #  örneğin aynı diznimizde bulunan başka bir py uzantılı dosyayı import edebşim

#* import deneme
#* #bu modül içindeki yapıları kullanma 
#* sonuc=mod.number
#* sonuc=mod.numbers
#* sonuc=mod.person["name"]
#* sonuc=mod.person["age"]
#* sonuc=mod.fonk()
#* p=mod.Person()

#* p.konus()



