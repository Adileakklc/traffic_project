# Urban Traffic Intelligence Platform 🚦

Bu proje, **şehir içi trafik olayları ve vatandaş ihbarlarının daha doğru, hızlı ve veriye dayalı şekilde değerlendirilmesini** sağlar.

Temel amacı; dağınık ve güvenilirliği belirsiz trafik verilerini **tek bir sistemde toplayarak**, bu verileri **anlamlı analizlere dönüştürmek** ve **karar vericilerin doğru aksiyonu almasını kolaylaştırmaktır**.

---

## Bu Sistem Ne İşe Yarar?

Bu sistem sayesinde:

- Trafik olayları ve ihbarlar **merkezi bir platformda toplanır**
- Her kayıt **kalıcı olarak veritabanına** yazılır
- Veriler analiz edilerek **önemsiz, tekrarlı veya düşük güvenilirlikte bildirimler ayırt edilebilir**
- Bölge ve mahalle bazlı **yoğunluk ve eğilimler** görülebilir
- Belediye veya operasyon ekipleri, **hangi olaya önce müdahale etmesi gerektiğini** veriye bakarak belirleyebilir

Kısacası sistem, **“ham trafik verisini” → “aksiyon alınabilir bilgiye” dönüştürür**.

---

## Hangi Problemi Çözer?

Geleneksel trafik yönetiminde:
- İhbarların doğruluğu anında değerlendirilemez  
- Olaylar genellikle manuel ve sezgisel şekilde ele alınır  
- Kaynaklar yanlış bölgelere yönlendirilebilir  

Bu proje, trafik yönetimini **reaktif olmaktan çıkarıp veri odaklı hale getirir**.

---

## Nasıl Çalışır?

```
Vatandaş / Kullanıcı
        ↓
Web Arayüzü (Flask)
        ↓
Veritabanı (Trafik Olayları & İhbarlar)
        ↓
Analiz / Tahmin Katmanı
        ↓
Karar Destek Çıktıları
```

- Kullanıcı trafik olayını bildirir  
- Sistem veriyi kaydeder  
- Analiz katmanı veriyi işler  
- Karar verici, durumu net ve sade bir şekilde görür  

---

## Nerelerde Kullanılabilir?

- Belediyelerin trafik ve ulaşım birimleri  
- Akıllı şehir uygulamaları  
- Trafik yoğunluğu ve olay analizi yapan ekipler  
- Veri bilimi ve karar destek sistemi projeleri  

---

## Proje Yapısı
```
traffic_project/
├─ app.py              # Uygulama giriş noktası
├─ db.py               # Veritabanı işlemleri
├─ tahmin.py           # Analiz / tahmin mantığı
├─ templates/          # Web arayüzü
├─ static/             # Stil ve etkileşim dosyaları
├─ models/             # Model dosyaları
├─ data/               # Veri setleri
```

---

## Çalıştırma

```bash
pip install -r requirements.txt
python app.py
```

Tarayıcıdan:
```
http://127.0.0.1:5000
```

---

## Kullanılan Teknolojiler
- Python  
- Flask  
- HTML / CSS / JavaScript  
- SQL tabanlı veritabanı  
- Veri analizi ve tahmin altyapısı  

---

## Lisans
Akademik ve portföy amaçlı geliştirilmiştir.
