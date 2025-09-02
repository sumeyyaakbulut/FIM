# File Integrity Monitoring (FIM)
Bu proje, belirlenen bir klasördeki dosyaların **içerik bütünlüğünü (hash)** takip eden bir **File Integrity Monitoring (FIM)** aracıdır.  
Dosyaların eklenmesi, silinmesi veya değiştirilmesi durumunda **log dosyası** güncellenir ve isteğe bağlı olarak **e-posta bildirimi** gönderilir.

---

## 🚀 Özellikler
- 📂 Klasör içindeki tüm dosyaların **baseline (referans durumu)** oluşturulur.  
- 🔍 Tarama yapılarak **eklenen, silinen, değişen** dosyalar bulunur.  
- ⏱️ Gerçek zamanlı izleme (watchdog ile).  
- 📨 Gmail üzerinden **TLS** ile güvenli e-posta bildirimi.  
- 📜 Tüm olaylar `fim_logs_new_1.txt` dosyasına loglanır.  
- ✍️ Değişen dosyalarda satır bazında **diff (fark)** çıkarılır.
