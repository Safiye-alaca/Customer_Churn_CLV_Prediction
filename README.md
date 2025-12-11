Müşteri Yaşam Boyu Değeri (CLV) ve Kayıp Riski (CHURN) Analizi 👑

📌 Proje Özeti

Bu proje, bir e-ticaret şirketinin geçmiş işlem verilerini kullanarak Yapay Zeka Destekli bir karar alma mekanizması oluşturmayı amaçlamaktadır. Proje, müşterileri üç temel boyutta analiz eder: Davranış (RFM), Kayıp Riski (CHURN) ve Gelecekteki Değer (CLV).

Temel Hedefimiz: Pazarlama ve elde tutma (retention) bütçesini, en yüksek kâr potansiyeli olan ve aynı zamanda kaybetme riski taşıyan müşterilere bilimsel olarak yönlendirmektir. Bu, kâr maksimizasyonu için kritik bir adımdır.

✨ Projenin Çözdüğü Sorunlar

Firmaların en büyük iki sorusuna yanıt bulduk:

1- Hangi Müşteriler Bizi Terk Etmek Üzere? Yüksek CHURN riski taşıyan müşterileri tespit ettik.

2- Hangi Müşteriler Gelecekte En Çok Parayı Getirecek? Her müşterinin tahmini Müşteri Yaşam Boyu Değerini (CLV) hesapladık.

🛠️ Kullanılan Analiz ve Modelleme Teknikleri

Bu projede veriden bilgi çıkarmak için birden fazla güçlü model kullandık:

1- Davranışsal Analiz: RFM (Recency, Frequency, Monetary) metodolojisi ile müşterileri Champions, At_Risk gibi anlamlı gruplara ayırdık.

2- Kayıp Riski Tahmini: Lojistik Regresyon modelini kullanarak müşterinin CHURN (terk etme) olasılığını tahmin ettik.

3- Gelecek Değer Tahmini: BG/NBD Modeli ile müşterinin önümüzdeki dönemde kaç kez alışveriş yapacağını hesapladık.

4- Parasal Değer Tahmini: Gamma-Gamma Modeli ile müşterinin her bir alışverişte ortalama ne kadar harcayacağını tahmin ettik.

📊 Öne Çıkan Sonuçlar

Tüm modellerin sonuçlarını birleştirerek, müşteri segmentlerini önümüzdeki 6 ayda getirecekleri tahmini toplam gelire (CLV) göre sıraladık.

Lider Segment Tespiti: Projenin sonuçları, Hibernating_Kayıp_Riski segmentinin yaklaşık 471.900 TL ile en yüksek toplam CLV potansiyelini taşıdığını gösterdi.

Kritik Risk: Ancak bu segment, aynı zamanda %86.6 ile en yüksek Kayıp Riski Oranına sahiptir.

Aksiyon Planı: Bu durum, şirketin acilen yüksek CLV'li Hibernating müşterilerini belirleyip, bu potansiyel geliri kaybetmemek için hızla aksiyon alması gerektiğini ortaya koymaktadır. Diğer değerli segmentler (Loyal ve Champions) ise korunmaya odaklanmalıdır.
