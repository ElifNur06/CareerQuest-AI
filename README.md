# CareerQuest AI 🚀

CareerQuest AI, Flutter tabanlı, otonom kariyer yönetimi ve kişisel gelişim asistanıdır. Bilişsel yük yönetimi, oyunlaştırılmış öğrenme (Gamification) ve yapay zeka destekli otonom araçlarla kullanıcının kariyer yolculuğunu profesyonel ve sürdürülebilir kılmayı hedefler.

## 🌟 Öne Çıkan Özellikler

### 🤖 Otonom İstihbarat & Pro Araçlar
* **Otonom Teklif Motoru:** İlan bazlı, ton seçilebilir ve PDF ihracı destekli teklif üretici.
* **Holografik Tarayıcı:** İş ilanlarını analiz ederek yetenek uyumluluk skoru hesaplar.
* **İş Kasası (Job Vault) & GitOps:** Başvuru süreçlerini takip eden otonom Kanban panosu.
* **Otomatik Chunking:** 60 dakikadan uzun eğitim kaynaklarını mikro-öğrenme (30dk) parçalarına böler.
* **Akıllı Link Çözümleyici:** YouTube, GitHub, Medium linklerini otomatik tanır ve native ikonlarla görselleştirir.

### 🧠 Bilişsel Yük ve Sağlık Yönetimi
* **Rage Quit Koruması:** Quizlerde stres yönetimi için otomatik "öfke molası" (AlertDialog) sistemi.
* **Yorgunluk Yönetimi:** Reaksiyon süresi testi ile bilişsel yorgunluk skorlama.
* **Kutu Nefesi & Beyin Çöplüğü:** Görsel odaklanma egzersizi ve zihinsel dağınıklık temizleme alanı.
* **AFK Modu:** 15 dakikalık zorunlu mola ve su içme hatırlatıcıları.

### 🎮 Gamification (Oyunlaştırma)
* **Streak & Rozet Sistemi:** Ardışık çalışma takibi ve başarı nişanları.
* **Yetenek Ağacı (Skill Tree):** Proje odaklı gelişim görselleştirme.
* **XP ve Ganimet (Loot):** Günlük konfeti efektli sürpriz ödüller.

## ⚙️ Teknik Mimari

* **State Management:** `Provider` desenini temel alan ölçeklenebilir yapı.
* **Veri Katmanı (Type-Safe):** `fromMap`/`toMap` fabrika metodları ile JSON serileştirme.
* **UX Haptics:** Etkileşimlerde `HapticFeedback` ile dokunsal geri bildirim.
* **Responsive Design:** `MediaQuery` ve `SingleChildScrollView`/`Flex` ile tüm cihazlarda kusursuz uyum.
* **İçerik Veritabanı:** 1000+ teknik soru içeren `lib/data/quiz_data.dart` ve adaptif zorluk filtreleme (QuizDataHelper).

## Görseller
<img width="465" height="823" alt="image" src="https://github.com/user-attachments/assets/eb9b9f0d-9c30-4b6b-94e0-6a10d5dbf702" />
<img width="464" height="826" alt="image" src="https://github.com/user-attachments/assets/1189cc81-92a8-4b3f-9e83-9701635d756a" />
<img width="465" height="823" alt="image" src="https://github.com/user-attachments/assets/277bcd67-3feb-4462-a6f1-d840905b45be" />
<img width="462" height="823" alt="image" src="https://github.com/user-attachments/assets/cc2f22d8-76b6-4439-934d-26d77acfb26f" />
<img width="465" height="823" alt="image" src="https://github.com/user-attachments/assets/cbbfdc82-01db-4442-973f-b6af9e024382" />
<img width="463" height="822" alt="image" src="https://github.com/user-attachments/assets/8566c557-148f-457e-a0b5-f2f7cdf631ef" />
<img width="466" height="826" alt="image" src="https://github.com/user-attachments/assets/ffde160f-2815-42b9-8638-02e699a8193e" />
<img width="464" height="825" alt="image" src="https://github.com/user-attachments/assets/69f2d2cd-981e-4c64-9a0d-166eef0e131c" />
<img width="465" height="825" alt="image" src="https://github.com/user-attachments/assets/b96ee68b-452e-4458-a185-d4f7de01fa3f" />
<img width="460" height="822" alt="image" src="https://github.com/user-attachments/assets/6e20c955-36a8-4966-b1ef-e1c6fbb2864f" />
<img width="464" height="826" alt="image" src="https://github.com/user-attachments/assets/4a172d98-da6d-44aa-8036-d216d326d9f1" />
<img width="463" height="812" alt="image" src="https://github.com/user-attachments/assets/3ff53601-5388-480d-bde1-9bf1d860591f" />
<img width="464" height="825" alt="image" src="https://github.com/user-attachments/assets/b9444e4b-a16c-4e4b-9a20-432090e38e19" />
<img width="463" height="824" alt="image" src="https://github.com/user-attachments/assets/b4e3252f-5ae8-42eb-bed6-b9e131b2c633" />
<img width="465" height="825" alt="image" src="https://github.com/user-attachments/assets/bdd3a317-092f-4b7c-b7c4-ea161711a751" />
<img width="464" height="824" alt="image" src="https://github.com/user-attachments/assets/1aea0282-9bf2-44d2-b162-4ffbb09f45c1" />
<img width="463" height="823" alt="image" src="https://github.com/user-attachments/assets/6fcd3275-d8c0-47bf-bf28-b2263e804ff9" />
<img width="466" height="827" alt="image" src="https://github.com/user-attachments/assets/c5634af7-e092-4e28-b61f-f3cfe4020208" />
<img width="468" height="825" alt="image" src="https://github.com/user-attachments/assets/3ded1ee6-fb9e-4257-a24f-9e465abb8e83" />



## 📁 Dosya Yapısı

```text
lib/
├── main.dart             # Uygulama giriş noktası ve konfigürasyon
├── providers/            # State Management (SkillAgentProvider)
├── models/               # Serializable veri modelleri (QuizQuestion, etc.)
├── screens/              # UI Katmanı (Dashboard, Quiz, ProTools, vb.)
├── services/             # Yapay zeka planlama ve analiz simülasyonları
├── widgets/              # Yeniden kullanılabilir dashboard ve pro widgetlar
└── data/                 # 1000+ soruluk statik içerik veritabanı
