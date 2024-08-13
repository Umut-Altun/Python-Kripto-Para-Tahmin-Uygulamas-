# 🚀 Kripto Fiyatları Tahmini - Bitcoin TL Fiyat Analizi

Bu proje, Python kullanarak CoinGecko API'si üzerinden Bitcoin'in son 6 aylık TL cinsinden fiyat verilerini çekip, bu verilerle bir tahmin modeli oluşturmayı amaçlamaktadır. SARIMA modellemesi kullanılarak, Bitcoin'in önümüzdeki 30 gün için fiyat tahmini yapılmaktadır.

## 🔧 Projede Kullanılan Teknolojiler
- **Python**: Veri analizi ve modelleme için kullanılan temel programlama dili.
- **Pandas**: Veri işleme ve analiz için kullanılır.
- **Plotly**: Grafiksel veri gösterimi için interaktif bir kütüphane.
- **Statsmodels**: Zaman serisi analizi ve tahminleme için kullanılır.

## 📊 Proje Adımları
1. **Gerekli Kütüphanelerin İmport Edilmesi**: Projede kullanılacak kütüphaneler projeye dahil edilir.
2. **Veri Çekme**: CoinGecko API'sinden son 6 aylık Bitcoin fiyat verileri TL cinsinden çekilir.
3. **Veri İşleme**: Çekilen veriler Pandas DataFrame'e dönüştürülür ve tarih sütunu datetime formatına çevrilir.
4. **Veri Temizleme**: Fiyat sütunu sayısal formata dönüştürülüp, verinin günlük frekansa ayarlanması sağlanır.
5. **Modelleme**: SARIMA modeli kullanılarak fiyat tahmini yapılır.
6. **Tahmin**: Önümüzdeki 30 gün için Bitcoin fiyat tahmini gerçekleştirilir.
7. **Grafikleme**: Gerçek ve tahmin edilen Bitcoin fiyatları Plotly ile grafik üzerinde gösterilir.

## 📈 Sonuç
Proje, geçmiş verilere dayalı olarak Bitcoin'in TL cinsinden fiyat hareketlerini tahmin etmek için kullanılır. Tahmin sonuçları, ileriye dönük fiyat hareketlerinin analizi için kullanılabilir.

## 🔮 Gelecek Çalışmalar
- Diğer kripto paralar için benzer modellemelerin yapılması.
- Modelin farklı zaman dilimlerinde ve parametrelerde test edilmesi.
- Tahmin doğruluğunu artırmak için daha gelişmiş modelleme tekniklerinin uygulanması.

## 💡 Nasıl Kullanılır
1. Bu projeyi bilgisayarınıza klonlayın veya indirin.
2. Gerekli kütüphaneleri yüklemek için `requirements.txt` dosyasını kullanın.
3. `kripto_fiyat_tahmini.py` dosyasını çalıştırarak tahmin modelini oluşturun ve sonuçları görüntüleyin.


Bu proje, kripto para piyasalarını anlamaya ve tahmin yapmaya yönelik kişisel bir projedir ve yatırım tavsiyesi değildir.
