# Fener Yolu

Ramazan gecesi bir Anadolu kasabasında geçen, yandan görünümlü bir zıplama oyunu.
Elinde küçük bir fener taşıyan **Kerem** adlı çocuk hurma toplar, iyilik yapar, engellerden kaçar ve cami avlusundaki şadırvana ulaşmaya çalışır.
Oyunda düşman yok, kimseye zarar verilmiyor.

## Nasıl açılır?

Oyunun tamamı tek bir dosyada: `index.html`. Bu dosyaya çift tıklayınca tarayıcıda açılır.
İnternete ya da ücretli bir servise ihtiyaç duymaz.
Kerem'in görselleri Kling ile üretildi (toplam 16 kredi) ve dosyanın içine gömüldü. Diğer görseller ve sesler kodla üretilir. Ortam sesi çalgısızdır; yalnızca rüzgâr, cırcır böceği ve kuş sesinden oluşur.

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
13. **Kuzular Ağıla (yılan tarzı):** Kuş bakışı bir çayırda Kerem kendiliğinden yürür; ok tuşlarıyla ya da telefonda parmak kaydırarak yön verilir. Topladığı her kayıp kuzu arkasına dizilir. Çite, taşa, kendi kuzu sırasına ya da kötü huy bulutuna çarpınca bir can gider. Her 4 kuzu bir iyilik sayılır; 12 kuzu toplanınca ağılın kapısı açılır. Çayır her oyunda yeniden kurulur, telefon dik tutulunca dik bir çayır çıkar.
14. **Deniz Yolculuğu:** 7. ve 11. bölümün şeritli yolculuğu, bu kez kayıkla denizde. Kenarlarda deniz fenerleri, yelkenliler ve adacıklar var; dalgalar yavaşlatır. Sonunda liman var.

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

- Her bölümde iki parlayan **bilgi yaprağı** saklı (bazıları için ikinci zıplama gerekir). Toplanınca kaynaklı bir âyet ya da hadis çıkar; hepsi ana menüdeki **Bilgi Defteri**'nde birikir.
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

Bilgi yapraklarındaki 28 metnin kaynakları: Buhârî, Fezâilü’l-Kur’ân 21 · Zümer 39/9 · Buhârî, Menâkıb 23 · Buhârî, Edeb 69 · Tirmizî, Birr 36 · Ebû Dâvûd, Zekât 41 · Buhârî, Edeb 18 · Buhârî, İlim 11 · Bakara 2/183 · Buhârî, Savm 2 · Buhârî, Savm 45 · Ebû Dâvûd, Savm 21 · Buhârî, Leyletü’l-Kadr 3 · Buhârî, Îmân 25 · Bakara 2/185 · Buhârî, Edeb 28 · Müslim, Îmân 147 · Buhârî, Îmân 4 · Ebû Dâvûd, Salât 50; Tirmizî, Salât 51 · Buhârî, Salât 88; Müslim, Birr 65 · Müslim, Îmân 93 · Müslim, Zikir 38 · Müslim, Tahâret 1 · Rahmân 55/6 · Tirmizî, Birr 16 · Müslim, Sayd 57 · Buhârî, Edeb 76; Müslim, Birr 107 · Bakara 2/153.

## İçerik ilkeleri

- Allah, peygamberler ve sahabe hiçbir şekilde çizilmez ve oynanabilir karakter yapılmaz. Ana karakter Kerem, sıradan bir çocuktur; hiçbir din büyüğünü temsil etmez.
- Şiddet ve düşman öldürme yoktur. Oyuncu engellerden kaçar, eşya toplar ve iyilik yapar.
- Karakter, dünya, bölümler ve sesler bu oyun için özgün olarak üretildi.

## Geliştirici notu

Yalnızca `localhost` üzerinde `?test=3,171` gibi bir adres parametresi, oyunu doğrudan o bölümün o noktasından başlatır (bölüm numarası, karo sütunu).
Yayındaki sitede bu parametre çalışmaz.
