# Python ile Veri Bilimi Programlama Temelleri ve Kütüphaneleri

Bu proje, veri bilimi alanında Python programlama dilinin temellerini öğrenmek veya bilgilerini tazelemek isteyenler için hazırlanmış kapsamlı bir Jupyter Notebook kaynağıdır. Notebook, temel Python kavramlarından başlayarak, veri analizinde ve görselleştirmede yaygın olarak kullanılan NumPy, Pandas, Matplotlib ve Seaborn gibi önemli kütüphanelerin kullanımını açıklamalı ve uygulamalı örneklerle sunmaktadır.

## 🎯 Amaç

Bu kaynağın temel amacı, veri bilimine yeni başlayan veya Python bilgilerini veri analizi odağında pekiştirmek isteyen kişilere yol göstermektir. Karmaşık teorilere girmeden, pratik uygulamalar ve anlaşılır açıklamalarla temel yetkinliklerin kazanılması hedeflenmiştir.

## 📚 Kapsanan Konular

Notebook aşağıdaki ana bölümleri ve alt başlıkları içermektedir:

1.  **Python Temelleri - Veri Bilimi İçin Programlama:**
    * Ekrana Yazdırma ve Yorum Satırları (`print()`, `#`)
    * Değişkenler ve Veri Tipleri (integer, float, string, boolean, tip kontrolü, temel işlemler)
    * String (Metin) İşlemleri (birleştirme, uzunluk, `upper()`, `lower()`, `replace()`, `split()`)
    * Veri Yapıları:
        * Listeler (oluşturma, indeksleme, dilimleme, metotlar)
        * Demetler (Tuple) (oluşturma, indeksleme, değişmezlik)
        * Kümeler (Set) (benzersiz elemanlar, küme işlemleri)
        * Sözlükler (Dictionary) (anahtar-değer çiftleri, erişim, ekleme/güncelleme, metotlar)
    * Koşul İfadeleri (`if`, `elif`, `else`, karşılaştırma ve mantıksal operatörler)
    * Döngüler (`for`, `while`, `range()`, `break`, `continue`)
    * Fonksiyonlar (`def`, parametreler, `return`, docstring'ler, lambda fonksiyonları)
    * Modüller ve Kütüphaneler (`import`, `math` modülü örneği)
    * Dosya İşlemleri (metin dosyalarını okuma ve yazma)
    * Hata Yönetimi (`try`, `except`, `else`, `finally`)

2.  **NumPy Kütüphanesi:**
    * Giriş ve NumPy dizilerinin önemi.
    * Dizi Oluşturma (`np.array()`, `np.zeros()`, `np.ones()`, `np.arange()`, `np.linspace()`, `np.random`)
    * Dizi Özellikleri (`ndim`, `shape`, `size`, `dtype`)
    * İndeksleme ve Dilimleme (tek ve çok boyutlu dizilerde)
    * Temel Matematiksel İşlemler (eleman bazlı işlemler, evrensel fonksiyonlar: `np.sqrt()`, `np.exp()`, `np.log()`)
    * İstatistiksel Fonksiyonlar (`np.sum()`, `np.min()`, `np.max()`, `np.mean()`, `np.std()`)
    * Matris İşlemleri (transpoze, matris çarpımı, ters alma, determinant)
    * Doğrusal Cebir (`np.linalg.solve()`, `np.linalg.eig()`, `np.linalg.svd()`)

3.  **Pandas Kütüphanesi:**
    * Giriş: Series ve DataFrame yapıları.
    * Veri Okuma ve Yazma (CSV, Excel vb. dosyalardan).
    * Veri Keşfi (`head()`, `tail()`, `info()`, `describe()`).
    * Veri Seçimi ve İndeksleme (`loc`, `iloc`, koşullu seçim).
    * Eksik Verilerin Yönetimi (`isnull()`, `fillna()`, `dropna()`).
    * Veri Gruplama ve Agregasyon (`groupby()`).
    * Veri Birleştirme (`merge`, `concat`, `join`).
    * Temel Veri Manipülasyonları.

4.  **Matplotlib Kütüphanesi:**
    * Giriş: Temel çizim mantığı.
    * Basit Çizim Türleri (çizgi grafiği, saçılım grafiği, bar grafiği, histogram).
    * Grafik Özelleştirme (başlık, eksen etiketleri, lejant, renkler, stiller).
    * Çoklu Grafik Alanları (Subplots).

5.  **Seaborn Kütüphanesi:**
    * Giriş: Matplotlib üzerine kurulu istatistiksel görselleştirme kütüphanesi.
    * Yaygın Kullanılan Grafik Türleri (`distplot`/`histplot`, `kdeplot`, `boxplot`, `violinplot`, `scatterplot`, `heatmap`, `pairplot`, `countplot`).
    * Grafik Estetiği ve Temaları.

*(Not: Pandas, Matplotlib ve Seaborn bölümleri için notebook'ta markdown başlıkları bulunmaktadır. Bu README, bu başlıklar altında genellikle işlenen standart konuları varsaymaktadır. Notebook'un tam içeriğine göre bu kısımlar detaylandırılabilir.)*

## 🛠️ Kullanılan Teknolojiler

* Python 3.x
* Jupyter Notebook (veya Google Colab)
* NumPy
* Pandas
* Matplotlib
* Seaborn

## 🚀 Nasıl Kullanılır?

1.  Bu depoyu klonlayın veya `Veri_Bilimi_Programlama_Tekrar.ipynb` dosyasını indirin.
2.  Jupyter Notebook, JupyterLab veya Google Colab gibi bir ortamda notebook dosyasını açın.
3.  Hücreleri sırayla çalıştırarak açıklamaları okuyabilir ve kod örneklerini deneyebilirsiniz.
4.  Kendi veri setleriniz veya problemleriniz üzerinde pratik yapmak için kodları değiştirebilir ve yeni hücreler ekleyebilirsiniz.

## 🎯 Hedef Kitle

* Veri bilimi ve makine öğrenmesine yeni başlayanlar.
* Python programlama dilini veri analizi ve görselleştirme amacıyla öğrenmek isteyenler.
* NumPy, Pandas, Matplotlib ve Seaborn kütüphanelerindeki bilgilerini tazelemek veya pekiştirmek isteyenler.
* Veri bilimi mülakatlarına veya projelerine hazırlanan öğrenciler ve profesyoneller.
