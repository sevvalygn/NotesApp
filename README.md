# # Not Uygulaması 

Genel bir not uygulaması. Not ekleyebilir, listeleyebilir, düzenleyebilir ve silebilirsiniz. Veriler tarayıcıda **localStorage** ile saklanır.

---

## Özellikler

- **Not ekleme** — Textarea’ya yazılan notlar (başlık + içerik) kaydedilir ve listelenir
- **Renk seçimi** — Yeni not eklerken veya düzenlerken 8 renkten biri seçilebilir
- **Renkte listeleme** — Kayıt öncesi seçilen renk, listede o notun kartında (kenar çizgisi ve arka plan tonu) gösterilir
- **Filtre** — “Notlarda ara” input’u ile başlık veya içerikte arama yapılarak notlar filtrelenir
- **Not düzenleme / silme** — Düzenle ve Sil butonları; veriler localStorage’da kalır

---

## Proje yapısı

```
NoteApp/
├── index.html   # Tek sayfa: form, not listesi, JS
└── README.md    # Bu dosya
```

---

## Nasıl çalıştırılır?

1. **Tarayıcıda:** `index.html` dosyasına çift tıklayın.
2. **Yerel sunucu ile:**
   ```bash
   cd NoteApp
   npx serve -l 3334 .
   ```
   Tarayıcıda **http://localhost:3334** açın.

---

## Kullanılan teknolojiler

- **HTML**
- **CSS3** — Layout, kartlar, form
- **Vanilla JavaScript** — CRUD, localStorage

Kurulum veya build gerekmez.
