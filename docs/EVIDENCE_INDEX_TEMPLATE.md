# Kanıt İndeksi (Evidence Index)

**Ürün:** <MACHINE_DESIGNATION>  
**Doküman ID / Revizyon:** <DOCUMENT_ID> / <REVISION>  
**Kanıt paketi:** evidence/_packs/<TIMESTAMP>_<SLUG>/  

## Okuma kılavuzu
Her kanıt kaleminde şu bilgiler bulunur:
- Evidence ID (EVID-XXXX)
- Yol (relative)
- SHA-256 hash
- Kısa açıklama
- Hangi kılavuz iddialarını desteklediği

| Evidence ID | Yol | SHA-256 | Açıklama | Desteklediği |
|---|---|---|---|---|
| EVID-0001 | assessments/risk_assessment_summary.pdf | <HASH> | Risk değerlendirmesi özeti | Kılavuz §1.2 |
| EVID-0202 | tests/e_stop_test_log.txt | <HASH> | Acil stop test logu | Kılavuz §5.4 |
| EVID-0104 | drawings/lifting_points.pdf | <HASH> | Kaldırma noktaları çizimi | Kılavuz §4.1 |