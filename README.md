# Makine Arıza Analizi

Bu proje, bir makine arıza veri setini analiz etmek ve arızaları tahmin etmek için makine öğrenimi tekniklerini kullanır. Proje, verilerin keşfedilmesi, önişleyici modelleme ve sonuçların görselleştirilmesini içerir.

## Veri Seti

Veri seti, makine arızalarıyla ilgili bilgileri içerir, örneğin:

* Zaman
* Vardiya
* Duruş Süresi
* Arıza Türü
* Arıza Alt Türü
* Etkilenen Bölüm

## Veri Analizi

Veri setini anlamak için çeşitli keşifsel veri analizi teknikleri kullanılmıştır. Bunlar şunları içerir:

* Temel istatistiklerin hesaplanması (ortalama, standart sapma vb.)
* Arıza türlerinin dağılımının görselleştirilmesi
* Vardiyalara göre arıza sayısının karşılaştırılması
* Arıza şiddetinin analiz edilmesi

## Önişleyici Modelleme

Arızaları tahmin etmek için bir Random Forest sınıflandırıcı modeli eğitilmiştir. Model, verilerin %80'i üzerinde eğitilmiş ve kalan %20'si ile değerlendirilmiştir. Elde edilen doğruluk skoru %XX'dir.

## Sonuçlar

Model, makine arızalarını yüksek doğrulukla tahmin edebilmektedir. Bu bilgiler, önleyici bakım planlamak ve arıza sürelerini azaltmak için kullanılabilir.

## Görselleştirmeler

Analizin sonuçları, anlaşılmayı kolaylaştırmak için çeşitli grafiklerle görselleştirilmiştir. Bunlar şunları içerir:

* Arıza türlerine göre duruş süresinin kutu grafiği
* Vardiyalara göre arıza sayısının bar grafiği
* Arıza şiddeti dağılımının pasta grafiği
* Zaman serisine göre ortalama duruş süresinin çizgi grafiği

