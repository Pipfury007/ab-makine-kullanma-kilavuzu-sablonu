# Stil Rehberi (Docs-as-Code)

## Token politikası (yayın öncesi TAMAMI değiştirilmeli)
Aşağıdaki token’ların tamamını yayın öncesi gerçek bilgilerle değiştirin:
- <MANUFACTURER_NAME>
- <MANUFACTURER_ADDRESS>
- <MACHINE_DESIGNATION>
- <MODEL_TYPE>
- <SERIAL_RANGE>
- <DOCUMENT_ID>
- <REVISION>
- <RELEASE_DATE>
- <LANGUAGE>
- <EU_DECLARATION_URL_OR_QR>
- <INTENDED_USE_SUMMARY>

## Kanıt referansı (evidence)
Mühendislik gerçeğine dayanan bir güvenlik iddiası veya talimat yazıyorsanız şu üçlüyü ekleyin:
- Evidence ID: EVID-XXXX
- Evidence path: evidence/_packs/.../...
- Hash: SHA256:...

## Minimum kalite kuralları
- Net, anlaşılır, okunaklı dil.
- Eksiksiz ama gereksiz yük yaratmayan içerik.
- Öngörülebilir yanlış kullanımları ele alın.
- DANGER / WARNING / CAUTION / NOTICE seviyelerini tanımlayıp tutarlı kullanın.