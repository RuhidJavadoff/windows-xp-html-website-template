# 🖥️ Windows XP Desktop Simulator (Demo)

Bu layihə, HTML, CSS və JavaScript istifadə edilərək klassik **Windows XP** masaüstü mühitinin nostalji görünüşünü və bəzi əsas funksiyalarını yenidən yaratmaq məqsədilə hazırlanmış **demo tətbiqidir**.

> 📌 Layihə yalnız əyləncə və eksperimental məqsədlərlə hazırlanmışdır.

---

## 📸 Ekran Görüntüləri

**1. Yükləmə Ekranı və Masaüstü Görünüşü**

![Loading and Desktop View](https://raw.githubusercontent.com/RuhidJavadoff/windows-xp-html-website-template/main/assets/images/02.png)

**2. Start Menyu, Kontekst Menyu və Bildiriş**

![Start Menu and Notification](https://raw.githubusercontent.com/RuhidJavadoff/windows-xp-html-website-template/main/assets/images/01.png)

---

## 🎯 Əsas Xüsusiyyətlər

- 🔵 **XP Tərzi Yükləmə Ekranı** – Klassik Windows XP açılış animasiyası.
- 🌄 **Masaüstü İnterfeysi** – "Bliss" divar kağızı və XP tipli ikonlar.
- 🖱️ **Draggable İkonlar** – İkonların sürüklənməsi və yenidən yerləşdirilməsi.
- 💾 **Pozisiya Yaddaşı** – İkonların mövqeyi `localStorage` ilə yadda saxlanılır.
- 🟢 **Start Düyməsi və Menyu** – İşlək Start düyməsi və açılan menyu.
- 📋 **Kontekst Menyu** – Sağ klik və ya mobil cihazda uzun basma ilə XP tərzi menyu.
- 🔍 **Ekran Ölçüsü Dəyişikliyi** – 50%-300% arasında miqyas dəyişikliyi imkanı.
- 🔒 **İkon Kilidləmə** – İkonların yerləşməsinin kilidlənməsi funksiyası.
- ⏱️ **Tapşırıq Paneli** – Real vaxt saatı olan klassik XP tapşırıq paneli.
- 🛎️ **Bildiriş Balonu** – Yükləmə bitdikdən sonra bildiriş görünür.
- 🔗 **Linkli İkonlar** – Hər ikon istənilən veb səhifəyə yönləndirilə bilər.
- 📱 **Responsiv Dizayn** – Desktop, planşet və mobil ekranlara uyğunlaşır.

---

## 💻 İstifadə və Quraşdırma

Bu layihə **tamamilə client-side** olaraq işləyir.

### 📥 Addımlar:
1. Layihəni GitHub-dan **yükləyin** və ya **klonlayın**.
2. `index.html` faylını **hər hansı müasir bir brauzerdə** açın.
3. (Opsional) CSS və JavaScript kodlarını `style.css` və `script.js` adlı ayrıca fayllara çıxarıb HTML-də aşağıdakı kimi bağlantı verin:

```html
<head>
    ...
    <link rel="stylesheet" href="style.css">
    ...
</head>
<body>
    ...
    <script src="script.js"></script>
</body>
