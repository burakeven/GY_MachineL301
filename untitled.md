# K EN YAKIN KOMSU
Gözlemlerin birbirine olan benzerlikleri üzerinden tahmin yapılır.
-Sınıflandırma ya da regresyon problemlerinde kullanıbilen algoritmadır.
-Parametrik olmayan bir öğrenme türüdür.

#KNN Basamaklari
-Komsu sayisini belirli(K)
-Bilinmeyen nokta ile diger tum noktalar ile arasindaki uzakliklari hesapla
-Uzakliklari sirala ve belirlenen k sayisina göre en yakin olan k gozlemi sec
-Siniflandirma ise en sık sinif, regresyon ise ortalama degeri tahmin degeri olarak ver.

# Destek Vektor Regresyonu(Support Vector Regression)
Guclu ve esnek modelleme tekniklerinden birisidir.
Siniflandirma ve regresyon icin kullanilabilir.
Robust(Dayanikli) bir regresyon modelleme teknigidir.

Amac, bir marjin araligina maksimum noktayi en kucuk hata ile alabilecek sekilde dogru ya da egriyi belirlemektir.

# YAPAY Sinir Aglari
-Amac en kucuk hata ile tahmin yapabilecek katsayilara erismektir.

# Classification and Regression Tree (CART)
- Sinirlandirma ve regresyon agaci
-Amac veri seti icerisindeki karmasik yapilari basit karar yapilarina donusturmektir.
-Heterojen veri setleri belirlenmis bir hedef degiskene gore homojen alt gruplara ayrilir.

# Random Forests
Topluluk ogrenme yontemleri; Birden fazla algoritmanın ya da birden fazla agacin bir araya gelerek toplu bir sekilde ogrenmesi ve tahmin etmeye calismasidir.
- Bagging
Temeli bootstrap yontemi ile olusturulan birden fazla karar agacinin urettigi tahminlerin bir araya getirilerek degerlendirilmesine dayanir.
Bagging calisma prensibinin kilit noktasi, bootstrap rastgele ornekleme yontemidir.
Bootstrap rastgele ornekleme yontemi, gozlem birimlerinin icinden yerine koymali bir sekilde tekrar tekrar ornek cekmek demektir.

# Gradient Boosting Machines
AdaBoost'un siniflandirma ve regresyon problemlerine kolayca uyarlanabilen genellestirilmis versiyonudur.
Artiklar uzerine tek bir tahminsel model formunda olan modeller serisi kurulur.

Artiklar = gercek ve tahmin edilen degerler arasindaki farklar

# eXtreme Gradient Boosting(XGBoost)
GBM'in hiz ve tahmin performansini arttirmak uzere optimize edilmis, olceklenebilir ve farkli platformlara entegre edilebilir halidir.

# Light GBM
XGBoost'un egitim suresi performansini arttirmaya yonelik gelistirilen bir diger GBM turudur.