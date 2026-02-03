# Bölüm 1: Güç Ünitesi (PSU) Tasarımı

Bu bölüm, direksiyon seti projesinin 12V DC besleme ünitesine ait teorik tasarım süreçlerini ve Altium Designer çizimlerini içerir.

### ⚠️ Önemli Notlar
* **Eğitim Amaçlı:** Bu çalışma eğitim amaçlı hazırlanmıştır; hesaplamalar teorik olup kart fiziksel olarak test edilmemiştir.
* **Verimlilik Analizi:** Yapılan analizler sonucunda lineer kartın Force Feedback (FFB) motoru için gereken yüksek akımlarda verimsiz kalacağı saptanmıştır.
* **SMPS Geçişi:** Projenin çalışan prototipinde, daha hafif ve yüksek verimli bir **SMPS** ünitesi kullanılmasına karar verilmiştir.

### 🛠️ Teknik Özellikler
* **Dönüşüm:** 220V AC → 12V DC (LM7812 ile regüleli).
* **Kritik Bileşenler:** 24V Transformatör, 10.000 µF Filtre Kapasitörü.
* **Güvenlik:** Ters akım koruması için D1 diyotu ve gürültü engelleme için dekuplaj kondansatörleri eklenmiştir.
<p align="center">
  <img width="400" alt="image" src="https://github.com/user-attachments/assets/93eab855-c8ae-4a89-a4d3-68374185f582" />
</p>
