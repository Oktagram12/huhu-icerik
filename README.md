# huhu-icerik

**Huhu Neden Böyle?** Android uygulamasının soru içeriği.

Uygulama `questions.json` dosyasını şu adresten günde en fazla bir kez kontrol eder:
`https://raw.githubusercontent.com/Oktagram12/huhu-icerik/main/questions.json`

## Güncelleme kuralları
- Her değişiklikte `version` değerini **1 artır** (artmazsa uygulama değişikliği almaz).
- Var olan soruların `id` ve `order` değerlerini **değiştirme, silme**. Yeni sorular yalnızca **sona** eklenir (`order` boşluksuz artar).
- Metin düzeltmeleri (açıklama, şık, kaynak) serbesttir.
- `videoUrl` ve kaynak `url` alanları `https://` ile başlamalı ya da `null` olmalı.
- `answerIndex` 0–3 arasında, her soruda 4 şık.
- Yeni sorunun ses dosyası uygulamaya gömülü olmadığı için "Dinle" butonu o soruda görünmez.
