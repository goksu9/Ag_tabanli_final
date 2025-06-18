<<<<<<< HEAD
# SQL Server Performans, Yedekleme ve Güvenlik Projesi

Bu projede SQL Server üzerinde aşağıdaki 7 konu üzerine çalışmalar yapılmıştır:

## 🔹 Proje 1: Veritabanı Performans Optimizasyonu
- DMV ile sorgu analizleri
- İndeks oluşturma ve sorgu iyileştirme
- Ekran görüntüleri ve video ile anlatım

## 🔹 Proje 2: Veritabanı Yedekleme ve Felaketten Kurtarma
- Full, differential, log yedekleri
- Geri yükleme senaryoları
- Test yedekleme ve restore işlemleri

## 🔹 Proje 3: Veritabanı Güvenliği ve Erişim Kontrolü
- Kullanıcı yetkilendirme
- TDE ile veri şifreleme

## 🔹 **Proje 4: Veritabanı Yük Dengeleme ve Dağıtık Yapılar**

- SQL Server Replication ve Database Mirroring konularının uygulanması  
- Always On Availability Groups yapısının incelenmesi  
- Failover (başarısızlık sonrası geçiş) senaryoları simüle edilmiştir  
- Video ve ekran görüntüleriyle desteklenmiştir  

---

## 🔹 **Proje 5: Veri Temizleme ve ETL Süreçleri Tasarımı**

- `dbo.vgsales` tablosu üzerinden veri kalitesi çalışmaları  
- NULL ve tutarsız verilerin temizlenmesi  
- Standartlaştırma ve veri dönüştürme işlemleri  
- Temizlenmiş verilerin `dbo.vgsales_clean` tablosuna yüklenmesi  
- Veri kalitesi çıktıları ve ekran görüntüleriyle raporlanmıştır  

---

## 🔹 **Proje 6: Veritabanı Yükseltme ve Sürüm Yönetimi**

- DDL trigger ile şema değişikliklerinin izlenmesi  
- `SchemaChangeLog` tablosu oluşturularak yapılan her değişiklik loglandı  
- Örnek ALTER işlemleri ile sürüm kontrolü simüle edildi  
- Geri dönüş planı senaryosu teorik olarak açıklandı  

---

## 🔹 **Proje 7: Veritabanı Yedekleme ve Otomasyon Çalışması**

- Manuel `BACKUP DATABASE` komutları ile tam yedek alma  
- SQL Server Agent kullanılarak otomatik job oluşturulması  
- Job içerisine zamanlama (Schedule) ve step eklenmesi  
- Yedekleme başarıyla gerçekleşti, `.bak` dosyası doğrulandı  
