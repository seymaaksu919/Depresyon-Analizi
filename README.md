<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <title>Öğrenci Depresyon Tahmini - KNN Modeli</title>
</head>
<body>

  <h1>📘 Öğrenci Depresyon Tahmini - KNN Modeli</h1>

  <h2>📌 Proje Amacı</h2>
  <p>
    Bu proje, bir öğrenci veri seti üzerinde K-En Yakın Komşu (KNN) sınıflandırma algoritması kullanarak öğrencilerin depresyonda olup olmadığını tahmin etmeyi amaçlar. Veri setinde öğrencilerin demografik, akademik ve psikolojik özellikleri yer almaktadır.
  </p>

  <h2>📊 Kullanılan Teknolojiler</h2>
  <ul>
    <li>Python</li>
    <li>Pandas, NumPy</li>
    <li>Matplotlib, Seaborn</li>
    <li>Scikit-Learn (KNeighborsClassifier, Train-Test Split, Confusion Matrix, Accuracy Score)</li>
  </ul>

  <h2>🗂️ Proje Adımları</h2>
  <ol>
    <li><strong>Veri Yükleme:</strong> CSV formatındaki öğrenci veri seti içe aktarılır.</li>
    <li><strong>Ön İşleme:</strong> Gereksiz sütunlar kaldırılır, eksik veriler kontrol edilir.</li>
    <li><strong>Veri Keşfi:</strong> Veri seti hakkında temel istatistiksel bilgiler alınır ve kategorik değişkenler görselleştirilir.</li>
    <li><strong>Korelasyon Analizi:</strong> Sayısal değişkenler arasındaki ilişkiler incelenir.</li>
    <li><strong>Modelleme:</strong> KNN sınıflandırma modeli kurulur. Veri eğitim ve test setlerine bölünür.</li>
    <li><strong>Değerlendirme:</strong> Model doğruluğu, karışıklık matrisi ve sınıflandırma raporu ile değerlendirilir.</li>
  </ol>

  <h2>⚙️ Nasıl Çalıştırılır?</h2>
  <ol>
    <li><strong>Gerekli Kütüphaneleri Kurun:</strong><br>
      <code>pip install pandas matplotlib seaborn scikit-learn</code>
    </li>
    <li><strong>Defteri Açın:</strong> Jupyter Notebook veya Google Colab ile <code>KNN.ipynb</code> dosyasını çalıştırın.</li>
    <li><strong>Veri Setini Ekleyin:</strong> <code>student_depression_dataset.csv</code> dosyasının notbook ile aynı klasörde olduğundan emin olun.</li>
    <li><strong>Hücreleri Çalıştırın:</strong> Adım adım ilerleyerek veriyi analiz edin, modeli eğitin ve çıktıları yorumlayın.</li>
  </ol>

  <h2>✅ Beklenen Çıktılar</h2>
  <ul>
    <li>Öğrencilerin depresyonda olma durumu tahmin edilir.</li>
    <li>Modelin doğruluk skoru hesaplanır.</li>
    <li>Karışıklık matrisi ve sınıflandırma raporu sunulur.</li>
    <li>Veri keşfi ve görselleştirmeler yapılır.</li>
  </ul>
