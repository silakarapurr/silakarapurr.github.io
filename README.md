# Sıla Karapur - Kişisel Biyografi & Portfolyo Web Sitesi

Modern, responsive (mobil uyumlu), karanlık/aydınlık tema destekli kişisel biyografi ve portfolyo web sitesi.

## 🚀 İçerik & Özellikler

- **Hakkımda (Biyografi):** Kendinizi, vizyonunuzu ve çalışma prensiplerinizi anlatan bölüm.
- **Kariyer & Eğitim:** Zaman çizelgesi (timeline) ile geçmiş ve güncel rolleriniz.
- **Yetenekler & Uzmanlıklar:** Kategorize edilmiş teknoloji ve beceri etiketleri.
- **Projeler:** Öne çıkarmak istediğiniz çalışmalar için modern kartlar.
- **İletişim:** Doğrudan e-posta ve sosyal medya bağlantıları.
- **Karanlık / Aydınlık Tema:** Kullanıcı tercihini tarayıcıda hatırlayan tema geçişi.
- **Sıfır Bağımlılık (Zero Dependencies):** Saf HTML5, CSS3 ve JavaScript (Ekstra kurulum/derleme gerektirmez).

---

## 🌐 GitHub Pages ile Ücretsiz Yayına Alma Adımları

Web sitenizi **`https://<kullanici-adiniz>.github.io`** adresiyle tamamen ücretsiz yayınlamak için:

### Yöntem 1: GitHub CLI ile (En Hızlı)

1. Terminalde GitHub oturumunuzu açın:
   ```bash
   gh auth login
   ```
2. Deponuzu oluşturup tek seferde yükleyin (burada `<kullanici-adiniz>` yerine GitHub kullanıcı adınızı yazın):
   ```bash
   gh repo create <kullanici-adiniz>.github.io --public --source=. --remote=origin --push
   ```
3. Birkaç saniye içinde siteniz `https://<kullanici-adiniz>.github.io` adresinde canlıya geçecektir!

---

### Yöntem 2: GitHub Web Sitesi Üzerinden

1. [github.com](https://github.com) adresine girin ve **New Repository** (Yeni Depo) butonuna tıklayın.
2. Depo adını tam olarak şu formatta yazın:
   `kullanici-adiniz.github.io` (Örn: `silakarapur.github.io`)
3. Depoyu **Public** olarak işaretleyin ve **Create repository** deyin.
4. Terminalde bu proje klasöründeyken (`personal-website`) şu komutları çalıştırın:
   ```bash
   git remote add origin https://github.com/<kullanici-adiniz>/<kullanici-adiniz>.github.io.git
   git branch -M main
   git push -u origin main
   ```
5. GitHub deponuzun **Settings > Pages** sekmesine gidin, Source kısmının **Deploy from a branch** ve Branch'in **main / root** olarak seçili olduğunu doğrulayın.
6. Tebrikler! Siteniz artık yayında.
