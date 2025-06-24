## 🛫 Airline Passenger Satisfaction - Veri Analizi Projesi
  Bu projede, bir havayolu firmasının yolcu memnuniyetini etkileyen faktörler veri analizi yoluyla incelenmiştir. Proje boyunca temel istatistiksel özetler, eksik ve aykırı değer analizleri, görselleştirme teknikleri kullanılmıştır. Elde edilen bulgular yolcu memnuniyeti hakkında önemli çıkarımlar sunmaktadır. 

### 📂 Veri Seti
  Kullanılan veri seti, Kaggle üzerinde yer alan “Airline Passenger Satisfaction” veri setidir. Veri seti; yolcularla ilgili yaş, cinsiyet, seyahat sınıfı gibi bilgilerin yanı sıra check-in servisi, uçuş içi hizmetleri ve rahatlık gibi çeşitli değişkenler aracılığıyla yolcu memnuniyetini anlamaya yöneliktir. 
  
Toplam Gözlem: 103904

Sütun Sayısı: 25

### 📊 İstatistiksel Özet
  Sayısal değişkenler (Age, Flight Distance, Departure Delay in Minutes vb.) için merkezi eğilim ve dağılım ölçümleri hesaplanmıştır.
* Ortalama, medyan, standart sapma, min-max değerleri incelenmiştir.

### 🧩 Eksik Değer Analizi
  Veri setinde yalnızca Arrival Delay in Minutes sütununda eksik değerler tespit edilmiştir.
* Eksik değerlerin oranı analiz edilmiştir.
* Değişkenin çarpık dağılım göstermesi nedeniyle medyanla doldurmak yerine bu satırlar veri dışına alınmıştır.
* missingno kütüphanesi kullanılarak eksik veriler görselleştirilmiştir.

### 🚨 Aykırı Değer (Outlier) Analizi
  Sayısal değişkenlerde aykırı değer tespiti için IQR (Interquartile Range) yöntemi uygulanmıştır.
* Flight Distance, Check-in service, Departure Delay in Minutes, Arrival Delay in Minutes gibi değişkenlerde aykırı değer bulunmuştur.
* Bu değerler analiz dışında bırakılmadan, sadece görselleştirme ile işaretlenmiştir.
* Boxplot grafikleri ile desteklenmiştir.

### 📈 Görselleştirme
  Veri seti hem genel istatistik hem de hedef değişken (satisfaction) ile olan ilişkileri gösterecek şekilde detaylı biçimde görselleştirilmiştir.
  
  Kullanılan grafik türleri:
* Histogram ve boxplot: Sayısal dağılımları görmek için kullanıldı.
* Catplot: Tüm hizmet kategorilerinin memnuniyet üzerindeki etkisini analiz etmek için kullanıldı.
* Scatterplot: Sayısal iki sütun arasındaki ilişkiyi görmek için kullanıldı.  

Öne çıkan gözlemler:
* Sınıf (Class) ve seyahat türü (Type of Travel) memnuniyeti en çok etkileyen değişkenlerdir.
* Business class yolcuları büyük oranda memnun, economy sınıfında memnuniyet çok düşüktür.
* Sadık müşteriler ve iş seyahati yapanlar, memnuniyet düzeyi yüksek olan gruplardır.
* Hizmet kalitesi (koltuk konforu, eğlence, yiyecek vb.) arttıkça memnuniyet de artmaktadır.
* Dijital hizmetler (Wi-Fi, online biniş) memnuniyet açısından zayıf kalmaktadır.

### 📝 Sonuç 
  Bu proje kapsamında, yolcu memnuniyetine etki eden faktörler analiz edilerek görselleştirilmiş ve yorumlanmıştır. Elde edilen öngörüler, havayolu firmalarının hizmetlerini geliştirmeleri ve müşteri deneyimini artırmaları için kullanılabilir.

airline-passenger-satisfaction-bitirme-projesi.ipynb: Tüm analizlerin yer aldığı Jupyter Notebook








  
   
