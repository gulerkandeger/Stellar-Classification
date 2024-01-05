# Stellar-Classification
![image](https://github.com/gulerkandeger/Stellar-Classification/assets/77187949/c6dc9949-cea7-4b5b-b84d-f4cf2f6d2b21)

#### Projenin Amacı
Bu proje, yıldızların gözlemlenen özellikleri kullanılarak yıldızları belirli sınıflara 
ayırmak için makine öğrenmesi modeli geliştirmeyi amaçlar. Yıldızların sınıflandırılması genellikle 
spektral özelliklere dayanır ve astronomlar genellikle yıldızların sıcaklıklarını, kütlelerini ve 
evrimsel durumlarını belirlemek için bu spektral verileri kullanırlar. Makine öğrenimi, büyük 
miktarda gözlemlenen veriyi analiz ederek yıldızları sınıflandırmak ve bu sınıflandırmayı 
otomatikleştirmek için güçlü bir araç olabilir

#### Data Set
Bu projede 'Stellar' veri seti kullanılmıştır.

#### Proje Özet
* Kütüphaneler import edildi.
* Veri seti okundu ve çıkarım yapmak için analiz işlemleri yapıldı.
* Veri üzerinde preprocessing işlemleri yapıldı:
    1. Missing Value <br>
    2. Encoding Categorical Features <br>
    3. Train/Test Split <br>
    4. Scaling <br>
* Decision Tree ve Random Forest algoritmaları ile sınıflandırma yapıldı.
* Model başarı ölçümü için confusion matrix ve accuracy score kullanıldı.
#### Sonuç
Modellerin accuracy değerleri şu şekildedir ; <br>
Decision Tree Accuracy : 0.8665151515151515 <br>
Random Forest Accuracy : 0.9568181818181818
###### Buradan bu veri seti için Random Forest'in daha güçlü bir model olduğu sonucuna varılmıştır.
