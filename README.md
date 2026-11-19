# Fener Yolu

Ramazan gecesi bir Anadolu kasabasında geçen, yandan görünümlü bir zıplama oyunu.
Elinde küçük bir fener taşıyan **Kerem** adlı çocuk hurma toplar, iyilik yapar, engellerden kaçar ve cami avlusundaki şadırvana ulaşmaya çalışır.
Oyunda düşman yok, kimseye zarar verilmiyor.

## Nasıl açılır?

Oyunun tamamı tek bir dosyada: `index.html`. Bu dosyaya çift tıklayınca tarayıcıda açılır.
İnternete ya da ücretli bir servise ihtiyaç duymaz.
Kerem'in görselleri Kling ile üretildi (toplam 16 kredi); güvercin ve meyve görselleri de Kling ile üretildi (2 kredi) ve dosyanın içine gömüldü. Menüdeki kapak resmi, 50 bölümün küçük resimleri ve mini oyunların 4 arka planı (gündüz, gece, gün batımı, kar) da Kling ile üretildi (11 kredi). Bölüm resimleri 3x3 ızgaralar hâlinde üretilip kesildi. "Fener Yolu" yazısı resim değil, sayfa yazısıdır. Diğer görseller ve sesler kodla üretilir. Ortam sesi çalgısızdır; yalnızca rüzgâr, cırcır böceği ve kuş sesinden oluşur.

Bilgisayarda yerel bir sunucuyla açmak için:

```bash
python -m http.server 8765 --directory oyun
```

Ardından tarayıcıda `http://localhost:8765` adresine gidin.

## İnternette

Oyun GitHub Pages'te herkese açık olarak yayında: https://redrumania19.github.io/fener-yolu/

Ayrıca Claude üzerinde de bir kopyası var: https://claude.ai/artifact/Y4vJUqVt2ywSxhfa6818Np
Bütün bölümler baştan açıktır, kilit yoktur. Bağlantı başta yalnızca sahibine açıktır; başkalarının açabilmesi için sayfadaki **Paylaş (Share)** menüsünden herkese açık yapılmalıdır.

## Kontroller

- **Bilgisayar:** ◀ ▶ ok tuşları veya A / D ile yürünür. Boşluk, ↑ veya W ile zıplanır (uzun basınca daha yükseğe). Havadayken bir kez daha basınca ikinci kez zıplanır. P veya Esc ile oyun duraklatılır.
- **Telefon:** (Yarış ve labirent bölümleri, yani 7, 8, 10 ve 11, tuşsuz, parmak hareketiyle oynanır; aşağıya bakın.) Sol alttaki ◀ ▶ tuşları ile yürünür, sağ alttaki ZIPLA tuşu ile zıplanır; havadayken bir kez daha dokununca ikinci kez zıplanır. Parmak ◀ ile ▶ arasında kaydırılabilir. Telefon yan tutulunca en rahat şekilde oynanır.

## Bölümler

Bölümler, farklı oyun türleri art arda gelsin diye **karışık sırada** oynanır. Oyundaki sıra:

1. Çarşı
2. Meyve Eşleştirme
3. Dede Evine Yolculuk
4. Hafıza Kartları
5. Damlar
6. Kandil Avı
7. Kuzular Ağıla
8. Üç Taş
9. Uçurtma Bayramı
10. Kayan Yapboz
11. Sahura Doğru
12. Yağmur Kovası
13. Kursa Giden Yol
14. Fener Sırası
15. Mektup Güvercini
16. Karşıya Geçiş
17. İftar Sofrası
18. Kelime Avı
19. Bereket Bahçesi
20. Dedeyle Top
21. Gece Bekçisi Fener
22. Koli İtme
23. Engel Atlama
24. Kadir Gecesi
25. Su Yolu
26. Bulut Dağıtma
27. Kızak Yarışı
28. Harf Tahmini
29. Işıkları Yak
30. Hurma Labirenti
31. Bayram Sabahı
32. Dört Fener
33. Yardım Kolisi
34. Balon İnişi
35. Deniz Yolculuğu
36. Renk Şifresi
37. Taş Duvar
38. Ağaç Dikme Şenliği
39. Tarla Taşları
40. Bahçe Birleştirme
41. Pide Dağıtımı
42. Fener Balonları
43. Mangala
44. Fenerleri Yak
45. Kiremit Boyama
46. Kutu Kapmaca
47. Buzda Kayma
48. Ters Çevir
49. Resim Bulmaca
50. Bilgi Yarışması

Aşağıdaki açıklamalar bölümleri yapılış sırasına ve türüne göre gruplar; oradaki numaralar yapılış sırasıdır.


1. **Çarşı:** Su tasını bul, susamış kediye götür.
2. **Damlar:** Kuş yavrusunu kiremitli çatılardan geçirip yuvasına götür.
3. **Sahura Doğru:** Güvercinlere yem, kediye su götür, gün ağarmadan camiye var.
4. **İftar Sofrası:** Gün batarken kediye su, yaşlı komşuya iftarlık pide götür. Zıplama minderleri var.
5. **Kadir Gecesi:** Karlı tepelerde güvercinlere yem ver, üşüyen yavru kediye battaniyeli kutu götür. Saçaktan kar düşer, kartopları yuvarlanır.
6. **Bayram Sabahı:** Süslü sokaklarda yaşlı komşuyla bayramlaş, komşu çocuklarına bayram şekeri dağıt.
7. **Dede Evine Yolculuk (yarış):** Kamera Kerem'in tahta arabasının arkasında; yol virajlarla ve tepelerle ufka doğru uzanır. Yolda 3 şerit var. Araba kendiliğinden ilerler; ◀ ▶ ile şerit değiştirilir, ↑ / Boşluk ile zıplanır, ↓ ile kayılır. Yüksekte duran bulutların altından kayarak geçilir. Telefonda tuş yoktur, parmak hareketiyle oynanır: sağa-sola kaydırınca şerit değişir (parmak kaldırılmadan devam edilirse bir şerit daha), yukarı kaydırınca ya da dokununca zıplanır, aşağı kaydırınca kayılır. Yalan, Öfke, Kıskançlık gibi kötü huy bulutlarına çarpınca yavaşlanır; Sabır, Doğruluk, Merhamet gibi güzel huylar hızlandırır ve arkadan kovalayan kara bulutu geri iter. Kara bulut dikiz aynasında görünür; yetişirse bir can gider. 3-2-1 geri sayımıyla başlar.
8. **Kursa Giden Yol (labirent):** Kuş bakışı, çiçekli çitlerden bir bahçe labirenti; her oyunda yeni bir labirent kurulur. Ok tuşları / W A S D ile dört yöne yürünür. Telefonda parmak kaydırılır: Kerem o yöne duvara kadar yürür; parmak kaldırılmadan başka yöne çekilirse ilk açıklıkta o yöne döner; dokununca durur. Sağ üstteki harita gezilen yerleri ve kursun kapısını gösterir. Üç iyilik: yavru kediyi annesine götürmek, kurumuş fidanı sulamak, güvercinlere yem vermek. Kötü huy bulutları can almaz, sadece geri iter.
9. **Uçurtma Bayramı (uçuş):** Kerem uçurtmaya tutunup kendiliğinden ilerler. ZIPLA / Boşluk basılı tutulunca yükselir, bırakılınca süzülür. Ağaç dallarına ve kötü huy bulutlarına çarpınca bir can gider. Ağaçlara takılmış üç uçurtmayı kurtarmak iyiliktir.
10. **Gece Bekçisi Fener (karanlık labirent):** 8. bölüm gibi, ama elektrikler gitmiş; yalnızca Kerem'in feneri etrafı aydınlatır. Kapı, kayıp ışıklar ve bilgi yaprakları uzaktan hafifçe parlar. Üç iyilik: yavru kediyi annesine, mumu yaşlı komşunun karanlık evine, battaniyeli kutuyu üşüyen yavru kediye götürmek. Her oyunda yeni labirent.
11. **Kızak Yarışı:** 7. bölümün kamerası ve şeritleri, bu sefer karlı dağda kızakla. Buz parçaları yavaşlatır; sonunda sıcak çorbalı dağ evi var.
12. **Ağaç Dikme Şenliği:** Çorak bir tepeye fidan dikilir ve çöp toplanır (hurma yerine çöp). Her dikilen fidanla çimen, tepeler ve çiçekler biraz daha yeşerir. Kuru dal topları yuvarlanır.
13. **Kuzular Ağıla (yılan tarzı):** Kuş bakışı bir çayırda Kerem kendiliğinden yürür; ok tuşlarıyla ya da telefonda parmak kaydırarak yön verilir. Topladığı her kayıp kuzu arkasına dizilir. Çite, taşa, kendi kuzu sırasına ya da kötü huy bulutuna çarpınca bir can gider. Her 4 kuzu bir iyilik sayılır; 12 kuzu toplanınca ağılın kapısı açılır. Bölüm (ve her çarpmadan sonra) **▶ Başla** tuşuyla başlar. Çayır her oyunda yeniden kurulur, telefon dik tutulunca dik bir çayır çıkar.
14. **Deniz Yolculuğu:** 7. ve 11. bölümün şeritli yolculuğu, bu kez kayıkla denizde. Kenarlarda deniz fenerleri, yelkenliler ve adacıklar var; dalgalar yavaşlatır. Sonunda liman var.
15. **Mektup Güvercini:** Dokun ve uç tarzı: ekrana dokundukça (ya da Boşluk / ↑ ile) güvercin kanat çırpar. Bacalar ve kötü huy bulutları arasındaki boşluklardan geçip dedenin evine mektup götürür; yolda yem taneleri ve 3 mektup toplanır.
16. **Bereket Bahçesi:** Meyve kesme tarzı: Kur'an'da adı geçen meyveler (hurma, üzüm, nar, incir, zeytin) havaya fırlar; parmakla (bilgisayarda fareye basılı tutarak) üstlerinden kaydırınca kesilir. Kötü huy bulutlarını kesmek bir can götürür. Her 15 meyve bir iyilik sayılır.
17. **Meyve Eşleştirme:** Üçlü eşleştirme: yan yana iki meyveyi yer değiştirip aynı meyvelerden üç (ya da daha fazla) tane dizerek 22 hamlede 100 meyve toplanır. 4'lü eşleşmeler kayıp ışık verir.
18. **Kayan Yapboz:** Üç resim (cami silueti, iftar sofrası, çayır) karışık parçalardan kaydırılarak tamamlanır.
19. **Hafıza Kartları:** Üç masada kartlar çevrilir, aynı resimli eşler bulunur.
20. **Su Yolu:** Borular döndürülerek çeşmeden bahçeye su yolu kurulur; her oyunda yeni bulmaca.
21. **Kelime Avı:** Harf tablosunda SABIR, ŞÜKÜR, MERHAMET gibi güzel kelimeler sürüklenerek bulunur; iki de gizli kelime var.
22. **Fenerleri Yak:** Top ve raketle sönük fenerler yakılır; top kaçarsa bir can gider.
23. **Bilgi Yarışması:** Bilgi Defteri'ndeki kaynaklı sözlerden 10 soru: âyet hangi sûrede, hadis hangi kitapta?
24. **Yardım Kolisi:** Sallanan koli tam zamanında bırakılarak 12 koli üst üste dizilir.
25. **Bahçe Birleştirme:** Kaydırarak aynı bitkiler birleştirilir: tohum, filiz, fidan, genç ağaç, ağaç, meyveli ağaç.
26. **Kandil Avı:** Pencerelerde beliren kandillere çabuk dokunulur; kötü huy bulutlarına dokunmamak gerekir.

### 27-50. bölümler: eski oyunlardan ilham alan bölümler

Bu bölümler eski (retro) oyun türlerinden ilham alır; karakterleri, adları ve görselleri bu oyuna özgüdür.

27. **Dedeyle Top** (raketli top) · 28. **Karşıya Geçiş** (yol ve dere geçme) · 29. **Hurma Labirenti** (noktaları topla, bulutlardan kaç) · 30. **Bulut Dağıtma** (fenerle ışık at) · 31. **Taş Duvar** (düşen taşlarla sıra tamamlama) · 32. **Fener Sırası** (sırayı hatırla)
33. **Tarla Taşları** (komşu taş sayıları) · 34. **Işıkları Yak** (fener ve komşularını değiştir) · 35. **Koli İtme** (kolileri yerine it) · 36. **Balon İnişi** (yumuşak iniş) · 37. **Yağmur Kovası** (damla yakalama) · 38. **Kiremit Boyama** (her kiremide bas)
39. **Pide Dağıtımı** (bisikletle kapılara pide) · 40. **Üç Taş** (dedeyle XOX) · 41. **Dört Fener** (dört tanesini hizala) · 42. **Renk Şifresi** (renk sırasını bul) · 43. **Harf Tahmini** (güzel kelimeyi bul) · 44. **Fener Balonları** (aynı renkleri birleştir)
45. **Engel Atlama** (koş, zıpla, kay) · 46. **Kutu Kapmaca** (noktaları birleştir) · 47. **Ters Çevir** (bulutları fenere çevir) · 48. **Mangala** (geleneksel Türk zekâ oyunu) · 49. **Buzda Kayma** (kayaya çarpana kadar kay) · 50. **Resim Bulmaca** (sayılarla resmi bul)

Bu bölümlerin sonundaki âyet ve hadisler: Hucurât 49/10 · Tirmizî, Birr 15 · Buhârî, Savm 9 · Nûr 24/43 · Nahl 16/90 · Bakara 2/152 · Mülk 67/15 · Bakara 2/257 · Müslim, İmâre 133 · Âl-i İmrân 3/190 · Kâf 50/9 · İnşirâh 94/5 · Nisâ 4/36 · Müslim, Kader 34 · Âl-i İmrân 3/103 · Rûm 30/22 · Kalem 68/1 · Rahmân 55/13 · Bakara 2/286 · Haşr 59/9 · Fussilet 41/34 · Buhârî, Zekât 18 · Yâsîn 36/40 · Hûd 11/88

## Kullanıcı adı ve lider tablosu

- Oyunu ilk açan herkes önce bir kullanıcı adı seçer (3-16 harf; uygunsuz kelimeler kabul edilmez). Ad, menüdeki **Değiştir** ile değiştirilebilir.
- Her bölüm bitince sonuç kartında da kısa bir lider tablosu çıkar: ilk 5 oyuncu ve oyuncunun kendi sırası.
- **Lider Tablosu**, her oyuncunun bölümlerdeki en iyi puanlarının toplamına göre ilk 50 kişiyi gösterir (hurma 1, kayıp ışık 5, iyilik 10 puan).
- Puanlar ücretsiz Firebase (Google) projesinde saklanır: `fener-yolu-99e3b`. Her oyuncu isimsiz (anonim) bir girişle yalnızca kendi satırını yazabilir. Güvenlik kuralları `firebase/firestore.rules` dosyasındadır.
- Uygunsuz bir adı silmek için Firebase konsolunda **Firestore Database → skorlar** altından o satır silinir.
- Lider tablosu GitHub sitesinde çalışır; Claude linkindeki kopyada güvenlik kısıtları yüzünden bağlanamaz.

## Yıldızlar ve zorluk

- Her bölümde 3 yıldız var: bölümü bitirmek, bütün iyilikleri yapmak, bütün ışıkları ve hurmaların (12. bölümde çöplerin) en az dörtte üçünü toplamak.
- Ana menüde her bölümün en iyi yıldızı ve toplam yıldız görünür.
- **Kolay mod:** 5 can olur, engeller daha yavaş hareket eder.

## Bilgi yaprakları, rozetler, süre

- Her bölümde iki parlayan **bilgi yaprağı** saklı (bazıları için ikinci zıplama gerekir). Toplanınca oyun durmaz; kısa bir yazı çıkar ve yaprak bölüm sonu kartında okunur. Hepsi ana menüdeki **Bilgi Defteri**'nde birikir.
- 9 **rozet** var (ör. hiç can kaybetmeden bitirmek, hedef sürenin altında bitirmek, bütün bilgi yapraklarını toplamak).
- Her bölümün **en iyi süresi** saklanır ve menüde görünür.

Her bölüm bitince kaynağıyla birlikte bir âyet ya da hadis gösterilir:

- “…İyilik edin. Şüphe yok ki Allah, iyilik edenleri sever.” (Bakara Sûresi, 2/195)
- “Her yaş ciğer sahibi canlıya yapılan iyilikte sevap vardır.” (Buhârî, Müsâkât 9; Müslim, Selâm 153)
- “Sahur yapınız; çünkü sahurda bereket vardır.” (Buhârî, Savm 20; Müslim, Sıyâm 45)
- “Oruçluya iftar ettiren kimse, oruçlunun sevabında bir eksilme olmaksızın, oruçlunun alacağı kadar sevap alır.” (Tirmizî, Savm 82; İbn Mâce, Sıyâm 45)
- “Kadir gecesi, bin aydan daha hayırlıdır.” (Kadr Sûresi, 97/3)
- “Her milletin bir bayramı vardır. Bu da bizim bayramımızdır.” (Buhârî, Îdeyn 3; Müslim, Salâtü’l-Îdeyn 16)
- “…Şüphesiz iyilikler, kötülükleri giderir.” (Hûd Sûresi, 11/114)
- “Kim ilim öğrenmek için bir yola girerse, Allah ona cennete giden yolu kolaylaştırır.” (Müslim, Zikir 38)
- “Üstlerinde kanatlarını açıp yumarak uçan kuşları görmüyorlar mı? Onları Rahmân’dan başkası tutmuyor…” (Mülk Sûresi, 67/19)
- “Allah göklerin ve yerin nûrudur…” (Nûr Sûresi, 24/35)
- “Sizden biri, kendisi için istediğini kardeşi için de istemedikçe iman etmiş olmaz.” (Buhârî, Îmân 7; Müslim, Îmân 71)
- “Bir Müslüman bir ağaç diker veya ekin eker de ondan bir insan, hayvan veya kuş yerse, bu onun için sadaka olur.” (Buhârî, Hars 1; Müslim, Müsâkât 12)
- “Hepiniz çobansınız; hepiniz güttüğünüz sürüden sorumlusunuz…” (Buhârî, Cum’a 11; Müslim, İmâre 20)
- “Denizde yüce dağlar gibi yükselen gemiler de O’nundur.” (Rahmân Sûresi, 55/24)
- “Eğer siz Allah’a hakkıyla tevekkül etseydiniz, kuşları rızıklandırdığı gibi sizi de rızıklandırırdı…” (Tirmizî, Zühd 33; İbn Mâce, Zühd 14)
- “…Üzüm bağları, zeytin ve nar bahçeleri çıkardık… Meyve verdiği zaman meyvesine ve olgunlaşmasına bakın!…” (En’âm Sûresi, 6/99)
- 17-26. bölümler: Nahl 16/11 · Âl-i İmrân 3/191 · Tâhâ 20/114 · Enbiyâ 21/30 · Alak 96/1 · İbrâhim 14/1 · Zümer 39/9 · Mâide 5/2 · Bakara 2/261 · En’âm 6/160

Bilgi yapraklarındaki 32 metnin kaynakları: Buhârî, Fezâilü’l-Kur’ân 21 · Zümer 39/9 · Buhârî, Menâkıb 23 · Buhârî, Edeb 69 · Tirmizî, Birr 36 · Ebû Dâvûd, Zekât 41 · Buhârî, Edeb 18 · Buhârî, İlim 11 · Bakara 2/183 · Buhârî, Savm 2 · Buhârî, Savm 45 · Ebû Dâvûd, Savm 21 · Buhârî, Leyletü’l-Kadr 3 · Buhârî, Îmân 25 · Bakara 2/185 · Buhârî, Edeb 28 · Müslim, Îmân 147 · Buhârî, Îmân 4 · Ebû Dâvûd, Salât 50; Tirmizî, Salât 51 · Buhârî, Salât 88; Müslim, Birr 65 · Müslim, Îmân 93 · Müslim, Zikir 38 · Müslim, Tahâret 1 · Rahmân 55/6 · Tirmizî, Birr 16 · Müslim, Sayd 57 · Buhârî, Edeb 76; Müslim, Birr 107 · Bakara 2/153 · Tirmizî, Radâ 11 · Buhârî, Zekât 10; Müslim, Zekât 66 · A’râf 7/31 · Tîn 95/1.

## İçerik ilkeleri

- Allah, peygamberler ve sahabe hiçbir şekilde çizilmez ve oynanabilir karakter yapılmaz. Ana karakter Kerem, sıradan bir çocuktur; hiçbir din büyüğünü temsil etmez.
- Şiddet ve düşman öldürme yoktur. Oyuncu engellerden kaçar, eşya toplar ve iyilik yapar.
- Karakter, dünya, bölümler ve sesler bu oyun için özgün olarak üretildi.

## Geliştirici notu

Yalnızca `localhost` üzerinde `?test=3,171` gibi bir adres parametresi, oyunu doğrudan o bölümün o noktasından başlatır (bölüm numarası, karo sütunu).
Yayındaki sitede bu parametre çalışmaz.
