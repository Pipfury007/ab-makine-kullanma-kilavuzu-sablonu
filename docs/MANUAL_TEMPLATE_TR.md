# KULLANMA TALİMATLARI / KULLANMA KILAVUZU
**Makine:** <MACHINE_DESIGNATION>  
**Model/Tip:** <MODEL_TYPE>  
**Seri aralığı:** <SERIAL_RANGE>  
**Doküman ID:** <DOCUMENT_ID>  
**Revizyon:** <REVISION>  
**Yayın tarihi:** <RELEASE_DATE>  
**Dil:** <LANGUAGE>  

## Bu dokümanın hukukî statüsü
- Bu doküman **Orijinal talimatlar** veya **Orijinal talimatların çevirisi** olarak sağlanır (uygun olanı seçin ve geçerli kurallara uyun).
- Çeviri ise, gerekli durumlarda orijinal talimatlarla birlikte sağlanmalıdır.

## Üretici ve yetkili temsilci
**Üretici:** <MANUFACTURER_NAME>  
**Adres:** <MANUFACTURER_ADDRESS>  
**Yetkili temsilci (varsa):** <AUTH_REP_NAME_AND_ADDRESS>  

## AB Uygunluk Beyanı (DoC)
Aşağıdakilerden birini sağlayın:
- Ek’te AB Uygunluk Beyanı, VEYA
- Şu adreste erişilebilir: <EU_DECLARATION_URL_OR_QR>

---

# İçindekiler
1. Güvenlik bilgileri
2. Amaçlanan kullanım ve öngörülebilir yanlış kullanım
3. Makine tanımı ve teknik veriler
4. Taşıma, elleçleme ve depolama
5. Kurulum / montaj / devreye alma
6. Kullanım
7. Temizlik ve bakım
8. Arıza giderme
9. Yedek parça ve sarf malzemeleri
10. Hizmet dışı bırakma ve bertaraf
11. Ekler (DoC, çizimler, şemalar, kablolama vb.)
12. Revizyon geçmişi

---

# 1. Güvenlik bilgileri

## 1.1 Güvenlik uyarı seviyeleri
Tutarlı şekilde tanımlayın ve kullanın:
- **DANGER (TEHLİKE):** ciddi yaralanma/ölüm ile sonuçlanır
- **WARNING (UYARI):** ciddi yaralanma/ölüm riski oluşturur
- **CAUTION (DİKKAT):** hafif/orta yaralanma riski oluşturur
- **NOTICE (BİLGİ):** mal hasarı / kalite kaybı riski

## 1.2 Artık riskler ve kullanıcı önlemleri
Tasarım/koruyucu önlemler sonrası kalan artık riskleri listeleyin.
Her artık risk için:
- Tehlike tanımı
- Nerede/ne zaman oluşur
- Sonuç
- Gerekli KKD ve davranış
- Kanıt referansı (risk değerlendirmesi kalemi)

| Artık risk | Nerede/ne zaman | Sonuç | Kullanıcı önlemi | Kanıt |
|---|---|---|---|---|
| <RISK_1> | <WHEN_WHERE> | <CONSEQUENCE> | <MEASURE> | EVID-0001 |
| <RISK_2> | <WHEN_WHERE> | <CONSEQUENCE> | <MEASURE> | EVID-0002 |

## 1.3 Güvenlik işaretleri, piktogramlar, etiketler
Makine üzerindeki etiket envanteri:
- Konum
- Anlam
- Değişim/bakım kuralı
- Kanıt: etiket artwork + yerleşim çizimi

---

# 2. Amaçlanan kullanım ve öngörülebilir yanlış kullanım

## 2.1 Amaçlanan kullanım
Kesin olarak tanımlayın:
- Makinenin tasarlandığı süreç/görev
- İzin verilen malzemeler/girdiler
- Çevresel sınırlar (sıcaklık, nem, patlayıcı ortam vb. varsa)
- Kullanıcı profili (profesyonel / profesyonel olmayan)

## 2.2 Öngörülebilir yanlış kullanım (mutlaka ele alınmalı)
Makul şekilde gerçekleşebilecek yanlış kullanım kalıplarını listeleyin ve açıkça yasaklayın.
Sonuçları ve önleme yöntemlerini açıklayın.

---

# 3. Makine tanımı ve teknik veriler

## 3.1 Genel bakış
Sağlayın:
- Genel tanım
- Ana alt sistemler
- Çalışma prensibi
- Operatörün bulunması muhtemel iş istasyonları (pozisyonları tarif edin)

## 3.2 Teknik veriler
| Parametre | Değer | Birim | Not / Kanıt |
|---|---:|---|---|
| Besleme | <VALUE> | <UNIT> | EVID-0101 |
| Anma güç | <VALUE> | <UNIT> | EVID-0102 |
| Gürültü emisyonu | <VALUE> | dB(A) | EVID-0103 |
| Kütle | <VALUE> | kg | EVID-0104 |

---

# 4. Taşıma, elleçleme ve depolama
## 4.1 Ambalaj ve kaldırma noktaları
Kaldırma ve sabitleme için çizimler/şemalar ekleyin.
## 4.2 Depolama koşulları
Kabul edilebilir aralıkları ve sapma sonuçlarını tanımlayın.

---

# 5. Kurulum / montaj / devreye alma
## 5.1 Saha gereksinimleri
- Zemin yükü, açıklıklar, havalandırma
- Güvenlik mesafeleri ve erişim kontrolü
## 5.2 Mekanik kurulum
Tork değerleri, bağlantı elemanları, hizalama kontrolleri ile adım adım prosedür.
## 5.3 Elektrik/pnömatik/hidrolik bağlantılar
- Bağlantı şemaları
- Topraklama talimatı
- Enerji vermeden önce doğrulama kontrolleri
## 5.4 İlk çalıştırma / devreye alma kontrol listesi
| Kontrol | Kabul | Sonuç | Kanıt |
|---|---|---|---|
| Koruyucular takılı | Evet/Hayır | <RESULT> | EVID-0201 |
| Acil stop çalışıyor | Geçti/Kaldı | <RESULT> | EVID-0202 |

---

# 6. Kullanım
## 6.1 Kontroller ve göstergeler
Tüm kontrol elemanlarını, modları ve göstergeleri açıklayın.
## 6.2 Normal kullanım
Güvenli başlatma ve durdurma dahil adım adım prosedür.
## 6.3 Olağandışı durumlar
- Sıkışma giderme
- Güç kaybı
- Acil stop reset prosedürü
## 6.4 Yasaklı işlemler
Açık liste.

---

# 7. Temizlik ve bakım
## 7.1 Bakım güvenliği
Enerji izolasyonu, kilitleme/etiketleme, soğuma, depolanmış enerji.
## 7.2 Bakım planı
| İş | Periyot | Aletler | Sarflar | Kanıt |
|---|---|---|---|---|
| <TASK> | <INTERVAL> | <TOOLS> | <CONS> | EVID-0301 |

## 7.3 Onarım ve parça değişimi
Şemalar ve kabul kontrolleri ekleyin.

---

# 8. Arıza giderme
| Belirti | Olası neden | Çözüm | Kanıt |
|---|---|---|---|
| <SYMPTOM> | <CAUSE> | <REMEDY> | EVID-0401 |

---

# 9. Yedek parça ve sarf malzemeleri
Parça numaraları, uyumluluk notları, sipariş bilgileri.

---

# 10. Hizmet dışı bırakma ve bertaraf
- Güvenli söküm
- Atık akışları
- Çevresel notlar

---

# 11. Ekler
A. AB Uygunluk Beyanı (veya URL/QR)
B. Çizimler ve şemalar
C. Kablolama şemaları
D. Etiket artwork
E. Revizyon kaydı

---

# 12. Revizyon geçmişi
| Revizyon | Tarih | Değişiklik özeti | Onaylayan |
|---|---|---|---|
| <REV> | <DATE> | <SUMMARY> | <NAME> |