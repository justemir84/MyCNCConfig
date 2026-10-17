# MyCNCConfig — CNCVerse Bridge (Kişisel Kurulum)

Bu repo, **CNCVerse Bridge** addon'u için kişisel kurulum sayfası ve notlarıdır.
Addon'un kendisi canlı sunucuda çalışır; buradaki dosyalar kuruluma yönlendirme içindir.

## 🚀 Kurulum (Nuvio)

1. Kurulum adresini kopyala:

   `https://cncverse.dpdns.org/u/pqb9urbx0tan6/manifest.json`

2. Nuvio → **Ayarlar → Eklentiler → Eklenti ekle (URL ile)** → adresi yapıştır ve onayla.
3. Eklenti listesini yenile; gerekirse Nuvio'yu kapat-aç. Arama ve yayın akışları hazır olacak.

## 🚀 Kurulum (Stremio)

- **Tek tık:** [Stremio'ya kur](stremio://cncverse.dpdns.org/u/pqb9urbx0tan6/manifest.json)
- ya da: Stremio → Addons → yukarıdaki `https://` adresini yapıştır.

## ❗ Önemli: GitHub adresi neden çalışmıyor?

Bu repoda daha önce duran `manifest.json` **statik bir kopyaydı**. CNCVerse Bridge, katalog ve yayın akışlarını (`/catalog`, `/stream`) her istekte **canlı sunucuda** üretir; GitHub ise yalnızca sabit dosya sunar. Bu yüzden GitHub adresiyle kurulunca:

- Kataloglar/eklentiler listede görünür (manifest okunur),
- Ama içerik istekleri 404 döner ve arama sonsuz **"yükleniyor"** durumunda kalır.

👉 Kurulum her zaman **yukarıdaki canlı adresle** yapılır. Bu nedenle statik `manifest.json` dosyası bu repodan kaldırıldı.

## 🔧 Katalogları ve kaynakları değiştirme

1. https://cncverse.dpdns.org adresine gir (profilin hazır: **Profile**).
2. Kaynakları, katalogları, kalite filtrelerini ve görünümü istediğin gibi düzenle.
3. Değişiklikler **otomatik senkronize olur**; kurulum adresi aynı kalır, yeniden eklemene gerek yok.
   (Adresi her zaman sitedeki **"Copy"** butonundan da alabilirsin.)

## 📱 Alternatif: Uygulama ile yerel kullanım

CNCVerse Bridge uygulamasını (Android/Windows) kurup çalıştırırsan Nuvio yerel bridge'i **otomatik algılar**; adres eklemene gerek kalmaz.
Uygulama indirme: https://github.com/NivinCNC/CNCVerse-Bridge/releases

## ℹ️ Notlar

- Profil kimliği: `pqb9urbx0tan6` — adresin bir parçası. Adresi paylaşırsan bu profili de paylaşmış olursun.
- İçerik listesi profil ayarlarına göre otomatik güncellenir; bu repoyu güncellemen gerekmez.
- Kurulum sayfası (GitHub Pages açıksa): https://justemir84.github.io/MyCNCConfig/
