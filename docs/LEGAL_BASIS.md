# Hukukî dayanak ve kanıta dayalı yaklaşım

Bu depo, endüstriyel makine kullanma kılavuzları için bir şablon ve kanıt/izlenebilirlik çerçevesidir.
Hukukî danışmanlık değildir.

## Birincil AB hukuk kaynakları (kılavuz gereklilikleri)
1) 2006/42/EC (Makine Direktifi)
- Ek I §1.7.4 “Instructions” ve özellikle §1.7.4.2 “Contents of the instructions” kılavuz içeriği için temel kontrol listesidir.

2) (EU) 2023/1230 (Makine Tüzüğü)
- 2006/42/EC’nin yerini alır. Genel uygulama tarihi 20 Ocak 2027’dir (bazı hükümler daha erken).
- Talimatların erişilebilirliği/dil gereklilikleri ve DoC erişimi gibi beklentileri güçlendirir.

## Destekleyici standartlar (dokümantasyon ve güvenlik yöntemi)
- IEC/IEEE 82079-1: Kullanım bilgisi hazırlanması — prensipler ve genel gereklilikler.
- ISO 20607: Makine emniyeti — talimat el kitabı — genel yazım ilkeleri.
- ISO 12100: Makine emniyeti — tasarım için genel ilkeler — risk değerlendirmesi ve risk azaltımı.

## Kanıta dayalı konsept
Bir kılavuzun gücü, onu destekleyen kanıtın gücü kadardır. Bu repo şu disiplinleri uygular:
- Uygunluk matrisi: her hukukî gereklilik kalemi → kılavuzda karşılandığı bölüm(ler).
- Kanıt paketleri: belirli bir kılavuz revizyonunu destekleyen zaman damgalı artefakt seti:
  - risk değerlendirmesi özeti,
  - doğrulama/test logları,
  - kılavuzda referans verilen çizimler/şemalar,
  - etiket envanteri (artwork + yerleşim),
  - çeviri ve gözden geçirme artefaktları.
- SHA-256 hash listesi: kanıt dosyaları için kurcalamaya dayanıklı iz.

## Pratik not
Uygulanabilir yükümlülükler; makine sınıfına, amaçlanan kullanıma, kullanıcı profiline, Üye Devlet dil kurallarına,
seçilen standartlara ve teknik dosyanın bütünlüğüne göre değişir.
Bu şablonu kullanın, sonra yetkin uyum profesyonelleriyle doğrulayın.