# baraj
## Scikits Learn


![image](https://github.com/iremssezer/baraj/assets/74788732/62ff6f79-536d-4520-b926-99f5a3834bee)


## Dataset from the BURSA AÇIK VERİ PLATFORMU: 


- Aylara Göre Toplam Yağış Miktarı Ortalaması: [https://acikyesil.bursa.bel.tr/dataset/aylaragoretoplamyagismiktariortalamasi]


- Bursa barajlarının dönemlere göre doluluk oranı: [https://acikyesil.bursa.bel.tr/dataset/baraj-bursa]


## Tüketimin Zaman İçinde Değişimi


![image](https://github.com/iremssezer/baraj/assets/74788732/0dfa5c81-8b7d-4c50-a7ba-77b5ce5e480d)


## Baraj Doluluk Oranı


![image](https://github.com/iremssezer/baraj/assets/74788732/8084fba0-5d16-4cd3-b196-6ea746dd183f)


## Aylara Göre Ortalama Yağış Miktarı


![image](https://github.com/iremssezer/baraj/assets/74788732/a981485b-b6b1-4b8b-a1e1-bb2522d7e13c)


### Doğancı ve Nilüfer barajlarına ait veriler kullanılarak tahmin yapılmıştır.




## Random Forest Regressor modeli kullanıldı.


![image](https://github.com/iremssezer/baraj/assets/74788732/5ba20ac4-b83a-4f84-88e4-40e71ef02bc7)


- Rastgele oluşturulmuş birden çok karar ağacının çıktısını birleştiren, regresyon ve sınıflandırma problemlerini çözmek için kullanılan bir makine öğrenme algoritmasıdır.


- Hiper parametre kestirimi yapılmadan da iyi sonuçlar vermesi hem regresyon hem de sınıflandırma problemlerine uygulanabilir olmasından dolayı popüler makine öğrenmesi modellerinden biridir.


## Hiperparametre Optimizasyonu


![image](https://github.com/iremssezer/baraj/assets/74788732/eadb2591-78ed-488c-b393-f23f965829e7)


- Lineer Regresyon bağımlı ve bağımsız değişkenler arasında y= mx+b fonksiyonuyla ifade edilebilecek doğrusal bir ilişki olduğunu varsayar. Lineer Regresyon modelinin eğitilmesi sırasında çeşitli optimizasyon teknikleri kullanılarak en uygun m ve b değerleri belilenir bu değerler model parametreleridir.


- Parametrelerden farklı olarak hiperparametreler modelin eğitilmesi sırasında öğrenilmez. Modelleme aşamasının öncesinde veri bilimci tarafından belirlenirler.


- Hiperparametre optimizasyonu, bir makine öğrenmesi algoritması için belirlenen başarı metriğine göre en uygun hiperparametre kombinasyonunu bulma işlemidir.


- Hiperparametre optimizasyonu ile model karmaşıklığı dengelenerek overfitting ve underfitting dengesi sağlanabilir.


### RandomizedSearchCV


- Rastgele olarak bir hiperparametre seti seçilir ve cross-validation ile model kurularak test edilir. Belirlenen hesaplama süresi limitine ya da iterasyon sayısına ulaşıncaya kadar bu adımlar devam eder

