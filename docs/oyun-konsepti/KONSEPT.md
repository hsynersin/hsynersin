# KÜL VE TAHT — Oyun Konsept Dokümanı (Taslak v0.1)

> Mobil, 3D, online, orta çağ temalı strateji oyunu.
> Bu doküman beyin fırtınası çıktısıdır; her başlık tartışmaya açıktır.

---

## 1. Tek Cümlelik Vizyon

**"Kral öldü, taht boş, kül dünyayı yutuyor — 12 hafta içinde ya birileri krallığı yeniden kurar, ya da herkes birlikte tarihe gömülür."**

Oyuncuların *gerçek oyunculardan oluşan feodal bir hiyerarşi* kurduğu, *kalıcı ve fiziksel olarak şekillendirilebilen* paylaşımlı bir 3D dünyada geçen, her sezonu bir hikâye perdesi gibi ilerleyip **yazılı bir tarihle (Kronik)** biten strateji oyunu.

---

## 2. Neden Farklı? (Pazar Boşluğu)

Standart mobil stratejiler (Rise of Kingdoms, Clash of Kings vb.) hep aynı döngüye sıkışmış durumda:

| Emsallerin sorunu | Bizim cevabımız |
|---|---|
| Sonsuz üs geliştirme, amaçsız grind | **Sezonluk hikâye ve net bir final**: taht ya alınır ya dünya düşer |
| "İttifak" = chat grubu, mekanik derinliği yok | **Mekanik feodalizm**: gerçek vasallık sözleşmeleri, vergi, isyan, ihanet |
| Harita statik bir arka plan | **Yaşayan dünya**: köprü, baraj, yangın, harabeler herkes için kalıcı |
| Pay-to-win, balina ekonomisi | Sezon sıfırlaması + kozmetik/battle-pass odaklı adil model |
| Kaybeden oyuncu silinip gider | **Miras sistemi**: adın Kronik'e yazılır, hanedanın sonraki sezona itibar taşır |

Hedef kitle: "Bu oyunların hepsi aynı" diyip bırakmış, ama Crusader Kings / Game of Thrones tarzı entrika ve hikâyeyi seven, günde 15-30 dakikası olan yetişkin oyuncu.

---

## 3. Hikâye ve Dünya

### Zemin
Yedi Nehir Krallığı'nın son kralı varis bırakmadan öldü. Aynı gece, haritanın kenarlarından **"Kül"** denen bir çürüme yayılmaya başladı: toprağı zehirliyor, terk edilmiş köyleri yutuyor, ordusuz kaleleri harabeye çeviriyor.

### Sezon = Hikâye Perdesi (10–12 hafta)
Her sunucu sezonu üç perdelik bir dram gibi ilerler:

1. **Perde I — Parçalanma (1.-4. hafta):** Herkes küçük bir beylik. Kül yavaş. Keşif, ilk sözleşmeler, ilk ihanetler.
2. **Perde II — Yükseliş (5.-9. hafta):** Kül hızlanır, güvenli toprak daralır. Büyük feodal piramitler oluşur; taht adayları belirginleşir.
3. **Perde III — Taht ya da Kül (10.-12. hafta):** Başkent açılır. Taht için son savaş — ama Kül de son hızındadır. İki final mümkün:
   - **Taç Giyme:** Bir hanedan (ve vasalları) tahtı alır, sezonu "hanedanın adıyla" kapatır.
   - **Karanlık Çağ:** Kimse başaramazsa Kül başkenti yutar; sunucu tarihi "düşüş" olarak yazılır.

### Kronik (kalıcı miras)
Sezon sonunda sunucunun yaşadıkları **otomatik yazılmış bir tarih metni** olur: "3. Sezon: Ersinoğulları'nın İhaneti ve Kuzey Köprüsü Kuşatması." Oyuncu adları, büyük savaşlar, ihanetler bu metne girer. Yeni sezona herkes sıfır kaynakla ama **hanedan itibarı ve unvanlarıyla** başlar. Grind sıfırlanır, *hikâyen* sıfırlanmaz.

---

## 4. Çekirdek Yenilikçi Mekanikler

### 4.1 Mekanik Feodalizm (oyunun kalbi)
- Herhangi bir oyuncuya **vasallık yemini** teklif edebilirsin (veya alabilirsin). Bu bir chat anlaşması değil, oyun motorunun uyguladığı bir **sözleşmedir**: vergi oranı, asker yükümlülüğü, koruma garantisi maddeleri seçilir.
- Lord, savaşta vasallarının ordusunu **çağırabilir (levy)**; vasal gelmezse sözleşme "yemin bozumu" sayılır.
- **İhanet mümkün ve tasarımın parçası** — ama bedeli var: "Şeref" puanı düşer, düşük şerefli oyuncuyla kimse sözleşme yapmak istemez, tüccarlar pahalı satar, Kronik'e "yeminbozan" olarak geçer.
- İç savaş/isyan: Vasallar birleşip lordlarını devirebilir. Taht'a giden meşru yol da budur — kral olmak için illa en güçlü olman gerekmez, en iyi **piramidi kuran** kazanır.

### 4.2 Yaşayan, Şekillendirilebilir 3D Dünya
- Tek büyük paylaşımlı harita; herkes aynı dünyada.
- Kalıcı müdahale: **köprü kurarsan herkes geçer, yakarsan kimse geçemez.** Nehre baraj → aşağı havza kurur, tarlalar verim kaybeder. Orman yakılır → geçici geçit ama kereste kaynağı ölür.
- Kuşatma izleri kalır: Yıkılan kale **harabe** olur; harabeler haydut/Kül yuvası olur. Dünya, sezonun sonunda oyuncuların verdiği kararların fiziksel kaydıdır.
- 3D burada süs değil mekanik: yükseklik avantajı, vadi pusuları, nehir geçitleri gerçek taktik unsurlar.

### 4.3 Hanedan Sistemi (kahraman değil, aile)
- Tek bir "hero" değil, yaşlanan ve **ölen** karakterlerden oluşan bir hanedan yönetirsin.
- Karakterler savaşta ölebilir, yaşlanır; varisler ebeveynlerinden özellik + kusur alır.
- **Oyuncular arası evlilik ittifakı:** İki gerçek oyuncunun hanedanı evlilikle bağlanır → otomatik saldırmazlık + veraset hakları. (Diplomasiyi chat'ten mekanik alana taşıyan ikinci araç.)

### 4.4 Bilgi Savaşı (sis, casus, sahte istihbarat)
- Savaş sisi klasik "görünmez alan" değil; **istihbarat bir kaynak**.
- Casuslar rapor getirir ama raporlar **sahte olabilir**: Oyuncu, düşman casuslarına yanlış ordu bilgisi "sızdırabilir" (gerçekte 500 asker varken 5.000 gösterebilir).
- Karşı istihbarat, çift ajan, tüccar dedikoduları... Blöf, savaşın kendisi kadar önemli.

### 4.5 Hayalet Komutan (mobil-asenkron savunma)
- Çevrimdışıyken kalen otomatik değil, **senin öğrettiğin doktrinle** savunulur: "Okçular köprü düşene kadar burçta kalsın, süvari doğu kapısından çıksın" gibi kurallar tanımlarsın.
- Kuşatma **tekrar izlenebilir**: sabah kalkınca gece olan savaşı 3D sahne olarak izler, doktrinini güncellersin. Kayıp bile içerik üretir.

### 4.6 Kül'e Karşı Zorunlu İşbirliği
- Kül, sadece PvP olan oyunlardaki "güçlü ezer, zayıf silinir" ölüm sarmalını kırar: bazen can düşmanınla **aynı seddi savunmak** zorundasın.
- Küçük/yeni oyuncu için anlamlı rol: Kül hattında görev alan beylikler, savaşamasa da Kronik'te ve ödül sisteminde yer bulur.

---

## 5. Mobil Oyun Döngüsü

- **Hedef seans: 5–15 dakika.** Emirler kuyruğa yazılır (yürüyüş, inşaat, casus görevi), gerçek zamanlı refleks istemez.
- Bildirimler "gel de bak" değil "karar an'ı" bildirir: *"Vasalın Kara Berk yemin bozdu — 6 saat içinde tepki ver."*
- Günlük döngü: sabah raporları oku (kuşatma tekrarı, casus raporları) → 2-3 stratejik emir → akşam savaş sonuçları.
- Uzun oturum isteyene: canlı kuşatma anları, konsey toplantıları (sesli/yazılı), harita üzerinde plan çizme.

---

## 6. Teknoloji Önerisi

> Profilin: Node.js, Next.js/React, MSSQL/MySQL, kurumsal mimari. 3D tecrübesi yok. Buna göre:

### Önerilen: Unity (istemci) + Node.js tabanlı otoriter sunucu

**İstemci — Unity 6 (C#):**
- Mobil 3D için en olgun ekosistem; iOS+Android tek kod tabanı.
- C#, TypeScript bilen biri için en yumuşak geçiş (tip sistemi, async/await, LINQ ≈ array metotları).
- **3D tecrübesizliğini kapatan sır: low-poly stilize sanat.** Synty gibi hazır asset paketleriyle modelleme öğrenmeden profesyonel görünüm alınır; düşük poligon mobilde performans da demek. (Örnek görsel referans: Bad North, Northgard.)

**Sunucu — Colyseus (Node.js/TypeScript) veya Nakama:**
- Bu oyun twitch-shooter değil; savaşlar **sunucuda deterministik simüle edilir**, istemci sonucu 3D oynatır. Yani netcode yükü düşük, "otoriter API + WebSocket" mimarisi yeter — bu tam senin sahan.
- Colyseus = Node/TS, mevcut becerinle sunucuyu ilk günden sen yazarsın. Kalıcı veri: PostgreSQL (veya bildiğin MySQL).
- Alternatif: Nakama (Go tabanlı, Unity SDK'sı hazır, ölçekleme dahili) — kod yazmak yerine hazır oyun-backend istersen.

**Alternatif istemciler (değerlendirildi, önerilmedi):**
- *Godot 4:* Ücretsiz ve hafif ama mobil online ekosistemi Unity kadar olgun değil.
- *React Three Fiber / Expo:* React bilgin doğrudan işe yarar ama üretim kalitesinde mobil 3D oyun için performans/araç seti yetersiz. **Yalnızca 1 haftalık görsel konsept prototipi** için mantıklı olabilir.

### Mimari özet
```
[Unity İstemci (iOS/Android)]
   │  WebSocket + REST
[Colyseus Oyun Sunucusu (Node/TS)]  ← savaş simülasyonu, sözleşme/yemin motoru, Kül ilerleyişi
   │
[PostgreSQL: dünya durumu, hanedanlar, Kronik]   [Redis: canlı oturum/kuyruk]
```

---

## 7. Yol Haritası (hobi temposu, tahmini)

| Faz | Süre | Çıktı |
|---|---|---|
| **0. Kağıt prototip** | 1-2 hafta | Feodalizm + Kül döngüsünü masa üstünde/spreadsheet'te test et. Mekanik eğlenceli mi? |
| **1. Dikey dilim** | 2-3 ay | Unity'de tek harita parçası: yürü, kuşat, savaş sonucunu izle. Tek oyunculu, sahte veri. |
| **2. Online çekirdek** | 2-3 ay | Colyseus sunucu, 2-10 oyuncu aynı haritada, vasallık sözleşmesi + vergi çalışıyor. |
| **3. Sezon alfa** | 3-4 ay | Kül ilerleyişi, hanedan/ölüm, kapalı test (20-50 kişi), 2 haftalık mini sezon. |
| **4. Soft launch** | — | Tek ülke/TR mağaza yayını, battle-pass, gerçek sezon. |

İlk Unity adımları için somut başlangıç: Unity Learn "Junior Programmer" + bir low-poly RTS kamera/tıklama tutorial'ı → 2 hafta içinde haritada birim yürütüyor olursun.

---

## 8. Monetizasyon İlkesi (özet)

- **Asla:** güç satan paketler, hızlandırma enflasyonu.
- **Evet:** sezonluk battle-pass (kozmetik + Kronik'te süslü unvan), hanedan armaları/kale görünümleri, sezon sonu "tarih kitabı" fiziksel/dijital koleksiyon ürünü.
- Sezon sıfırlaması pay-to-win'i yapısal olarak da öldürür: satın alınan güç 12 haftada buharlaşır, kimse duvara toslamış hissetmez.

---

## 9. Açık Sorular (birlikte karar vereceklerimiz)

1. Sunucu başına oyuncu ölçeği: 100'lük samimi sunucular mı, 1000+ epik sunucular mı? (Tasarımı kökten etkiler.)
2. Savaşlar tamamen asenkron mu, yoksa "randevulu canlı kuşatma" pencereleri olsun mu?
3. Tek büyük küresel dünya mı, dil/bölge bazlı sunucular mı (TR pazarı odaklı başlamak mı)?
4. Hanedan ölümü ne kadar acımasız olmalı? (Tam permadeath vs. yumuşatılmış varis sistemi)
5. İsim: "Kül ve Taht" çalışma adı — alternatifler açık.
