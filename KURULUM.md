# Gizlilik Politikası - GitHub Pages Kurulumu

## 1. Yeni bir repo aç
GitHub'da yeni bir repo oluştur, örn: `rotaile-privacy-policy` (public olmalı, GitHub Pages
ücretsiz planda sadece public repolarda çalışır).

## 2. index.html'i yükle
Bu klasördeki `index.html` dosyasını repo'nun kök dizinine push et.

```bash
cd rotaile-privacy
git init
git add .
git commit -m "Gizlilik politikası sayfası"
git remote add origin https://github.com/KULLANICI_ADIN/rotaile-privacy-policy.git
git push -u origin main
```

## 3. GitHub Pages'i aç
1. Repo sayfasında **Settings** -> **Pages**'e git.
2. "Source" kısmından **Deploy from a branch** seç.
3. Branch olarak `main`, klasör olarak `/ (root)` seç, kaydet.
4. Birkaç dakika içinde sana şu formatta bir URL verecek:
   ```
   https://KULLANICI_ADIN.github.io/rotaile-privacy-policy/
   ```

## 4. TikTok / Instagram panelinde kullan
Bu URL'i ilgili API başvurusu/sandbox ayarlarındaki "Privacy Policy URL" alanına yapıştır.

## ÖNEMLİ — Düzenlemen gereken yer
`index.html` içindeki iletişim e-postası şu an placeholder:
```
rotailecrew@gmail.com
```
Bunu gerçek iletişim adresinle değiştir. Ayrıca toplanan veri türleri genel bir taslak
olarak yazıldı — uygulaman gerçekte hangi verilere erişiyorsa (örn. sadece video paylaşım
izni mi, yoksa kullanıcı profili de mi), 1. ve 2. başlıkları ona göre netleştirmen iyi olur.
