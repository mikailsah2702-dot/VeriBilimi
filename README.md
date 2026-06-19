# Türkiye Deprem Verileri Analizi (1915-2021)

## Proje Hakkında

Bu proje, 1915-2021 yılları arasında Türkiye'de meydana gelen depremlere ait verilerin Python kullanılarak analiz edilmesi amacıyla hazırlanmıştır. Çalışma kapsamında veri ön işleme, veri temizleme, veri görselleştirme ve temel istatistiksel analizler gerçekleştirilmiştir.

## Kullanılan Teknolojiler

* Python
* Pandas
* Matplotlib
* Jupyter Notebook / Google Colab

## Veri Seti

Çalışmada Kaggle platformunda bulunan "Turkey Earthquakes (1915-2021)" veri seti kullanılmıştır.

Veri setinde aşağıdaki bilgiler yer almaktadır:

* Deprem tarihi
* Deprem saati
* Enlem
* Boylam
* Derinlik
* Deprem büyüklüğü
* Depremin meydana geldiği yer

## Veri Ön İşleme Adımları

Proje kapsamında aşağıdaki işlemler gerçekleştirilmiştir:

* Gereksiz sütunların kaldırılması
* Eksik verilerin temizlenmesi
* Tarih ve saat verilerinin dönüştürülmesi
* Yıl ve ay sütunlarının oluşturulması
* Konum bilgilerinin düzenlenmesi
* Analiz için yeni değişkenlerin oluşturulması

## Yapılan Analizler

### 1. Yıllara Göre En Büyük Depremler

Yıllar bazında meydana gelen en yüksek büyüklükteki depremler incelenmiştir.

### 2. Aylara Göre Deprem Sayıları

Depremlerin aylara göre dağılımı analiz edilmiştir.

### 3. Depremlerin İllere Göre Dağılımı

Türkiye'de deprem yoğunluğunun hangi illerde daha fazla olduğu belirlenmiştir.

### 4. Deprem Büyüklüğü Dağılımı

Deprem büyüklüklerinin frekans dağılımı incelenmiştir.

### 5. Deprem Derinliği Dağılımı

Depremlerin derinlik özellikleri analiz edilmiştir.

### 6. Derinlik ve Büyüklük İlişkisi

Deprem derinliği ile deprem büyüklüğü arasındaki ilişki araştırılmıştır.

### 7. Ortalama Deprem Büyüklüğü En Yüksek İller

İller bazında ortalama deprem büyüklükleri hesaplanmıştır.

### 8. Uzun Dönemli Deprem Eğilimleri

Yıllara göre deprem sayılarındaki değişimler hareketli ortalama yöntemi ile incelenmiştir.

## Elde Edilen Sonuçlar

* Türkiye'nin deprem açısından aktif bir ülke olduğu görülmüştür.
* Küçük ve orta büyüklükteki depremler büyük depremlere göre çok daha sık meydana gelmektedir.
* Depremlerin büyük bölümü yüzeye yakın derinliklerde gerçekleşmektedir.
* Fay hatlarına yakın bölgelerde deprem yoğunluğu daha fazladır.
* Deprem büyüklüğü ile derinlik arasında güçlü bir ilişki bulunmamıştır.

## Projeyi Çalıştırma

```bash
pip install pandas matplotlib
```

Ardından notebook dosyasını çalıştırabilirsiniz.

## Kaynakça

* Turkey Earthquakes (1915-2021) Dataset - Kaggle
* Pandas Documentation
* Matplotlib Documentation
* Python Documentation

## Hazırlayan

MİKAİL ŞAHİN

Veri Bilimi Dersi Projesi
