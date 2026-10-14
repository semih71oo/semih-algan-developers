# Semih Algan — Yazılım & Fikirler

Semih Algan için hazırlanmış Türkçe, mobil uyumlu bir yazılım vitrini ve kişisel tanıtım sitesi. Ana sayfada yazılımlar için “çok yakında” duyurusu, biyografi, basketbol ve satranç ilgi alanları ve doğrudan iletişim bağlantıları bulunur.

Bu sürümde ürün listesi, fiyatlar, sepet, satın alma veya ödeme işlemi yoktur. İletişim bölümü e-posta ve telefon uygulamalarını açar; e-posta adresi ayrıca kopyalanabilir. Bilgiler herkese açık olarak gösterilir.

## Teknolojiler

- React 19, TypeScript ve TanStack Start / TanStack Router
- Vite 7 ve Netlify TanStack Start eklentisi
- Tailwind CSS 4 ve özel, duyarlı CSS tasarımı
- Lucide React ikonları; CSS ile oluşturulmuş dekoratif görseller
- Google Fonts üzerinden Manrope ve DM Sans; harici fontlar yüklenemezse yerel sans-serif yedeği

## Yerel geliştirme

Node.js 22 veya üzeri ve pnpm kullanın.

```sh
pnpm install
pnpm dev
```

Site `http://localhost:3000` adresinde açılır. Netlify ortamıyla çalışmak için Netlify CLI kuruluysa:

```sh
netlify dev --port 8889
```

Üretim derlemesi Netlify dağıtım sürecinde otomatik olarak çalıştırılır.

## İçeriği düzenleme

Sayfa metinleri ve iletişim bilgileri `src/routes/index.tsx` dosyasında, paylaşım başlığı ve açıklaması `src/routes/__root.tsx` dosyasında bulunur. Renkler, yerleşimler ve mobil stiller `src/styles.css` dosyasında tanımlanır.

Bu sürüm veri toplamaz ve kalıcı uygulama verisi tutmaz; veritabanı, form veya kimlik doğrulama gerektirmez.
