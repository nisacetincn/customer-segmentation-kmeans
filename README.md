# customer-segmentation-kmeans
Müşteri Segmentasyonu (K-Means Kümeleme)

Bu proje, veri madenciliği yöntemlerinden biri olan K-Means kümeleme algoritması ile müşteri segmentasyonu gerçekleştirmektedir. Analizlerde, alışveriş merkezi müşterilerine ait bir veri seti kullanılmış ve müşteriler harcama alışkanlıkları ve gelir düzeylerine göre anlamlı gruplara ayrılmıştır.

Projenin Amacı

- Benzer alışveriş davranışlarına sahip müşteri gruplarını tespit etmek
- Kişiselleştirilmiş pazarlama kampanyaları için stratejik segmentler oluşturmak
- Firmaların müşteri ilişkilerini daha verimli yönetmesini sağlamak

Kullanılan Dosyalar

- Mall_Customers.csv: Kaggle’dan alınan müşteri verisi
- customer_segmentation.ipynb: Tüm veri analizi ve K-Means uygulaması Jupyter Notebook dosyasında yer almaktadır
- customer_segmentation_report.pdf: Projeye ait detaylı rapor

Kullanılan Kütüphaneler

- pandas
- numpy
- matplotlib
- seaborn
- sklearn (KMeans)

Kullanılan Yöntemler

- Veri Önişleme: Null değer kontrolü, gereksiz sütunların kaldırılması
- Elbow Yöntemi: Optimum küme sayısının belirlenmesi
- K-Means Kümeleme: 5 küme üzerinden segmentasyon yapılması
- Görselleştirme: Kümeleme sonuçlarının scatter plot ile analizi

Sonuç

Segmentasyon sonucunda müşteriler, yıllık gelir ve harcama skoru üzerinden 5 kümeye ayrılmıştır. Bu kümeler:

- Cluster 0: Ortalama gelir, ortalama harcama
- Cluster 1: Yüksek gelir, yüksek harcama (en değerli müşteri grubu)
- Cluster 2: Düşük gelir, yüksek harcama
- Cluster 3: Yüksek gelir, düşük harcama
- Cluster 4: Düşük gelir, düşük harcama

Bu gruplar sayesinde firmalar her segment için özel stratejiler geliştirerek pazarlama verimliliğini artırabilir.

Not

Veri seti Kaggle üzerinden alınmıştır. Proje referans olarak akademik bir çalışmaya dayanmaktadır.

