# orca-turkish

[Orca](https://github.com/stablyai/orca) için Türkçe (tr-TR) dil paketi eklentisi.

**Geliştirici & Katkıda Bulunan:** [Emir Topaloğlu](https://github.com/emirrtopaloglu)

---

## 🇹🇷 Durum & Kapsam

Orca'nın çevrilebilir tüm kullanıcı arayüzü kataloğu eksiksiz olarak Türkçeye kazandırılmıştır:

- **13.230+ / 13.232** çevrilebilir metin (%100 tam kapsam)
- **Kapsanan Alanlar:**
  - Ayarlar & Yapılandırma panelleri
  - Sol ve sağ kenar çubukları
  - Kod editörü, çalışma alanları (workspaces) ve worktree'ler
  - AI Agent oturumları, fleet yönetimi ve skill paylaşımı
  - Dahili terminal ve komut paleti
  - GitHub, GitLab, Linear, Jira ve Bitbucket entegrasyonları
  - Karşılama ekranı (onboarding) ve ilk kurulum sihirbazları
  - Mobil eşlikçi uygulama ve Agent Haritası / Dashboard
  - Sistem tepsisi ve macOS/Windows/Linux uygulama menüleri

---

## 🚀 Kurulum

Orca, dil paketlerini eklenti sistemi üzerinden yükler. Kurulumun belirli bir sürüme sabitlenmesi (pinned) için bir `#ref` (tag veya commit hash) eklenmesi önerilir.

### Eklenti Olarak Ekleme (Önerilen)
1. Orca'da **Settings (Ayarlar) → Plugins (Eklentiler) → Add Plugin Source (Eklenti Kaynağı Ekle)** bölümüne gidin.
2. Sabitlenmiş (pinned) eklenti URL'sini girin:
   ```
   https://github.com/emirrtopaloglu/orca-turkish#v1.0.0
   ```
   *(veya `#v0.1.0` gibi spesifik bir sürüm etiketi)*
3. **Settings → Appearance → Language** (Ayarlar → Görünüm → Dil) sekmesinden **tr-TR — Türkçe (orca-turkish)** seçeneğini aktif edin.

---

## 🛠️ Nasıl Hazırlandı?

Bu dil paketi, yazılım geliştirme ekosisteminde kullanılan terminoloji standartları gözetilerek titizlikle yerelleştirilmiştir:

1. **Geliştirici Odaklı Terminoloji:** Geliştiricilerin aşina olduğu yerleşik terimler (`Agent`, `Branch`, `Commit`, `Push`, `Pull`, `Worktree`, `Workspace`, `Pull Request`, `Merge`, `Rebase`, `Stash`, `Fork`, `Host`, `Port`, `Runtime`, `Prompt`, `CLI` vb.) GitHub, GitLab ve modern IDE standartlarına uygun olarak korunmuş ve doğal Türkçe eklerle harmanlanmıştır. Birebir çeviri ("chicken translation") hataları tamamen temizlenmiştir.
2. **Değişken & Yer Tutucu Bütünlüğü:** Tüm arayüz şablon değişkenleri (`{{value0}}`, `{{count}}`, HTML/KBD etiketleri vb.) bozulmadan %100 doğrulukla işlenmiştir.
3. **Orca Eklenti Doğrulaması:** Paket, Orca'nın eklenti çalışma zamanı güvenlik ve manifest kurallarına tam uyumludur.

---

## 🤝 Katkıda Bulunma

Hata bildirimleri, çeviri iyileştirmeleri ve önerileriniz için:
1. Depoyu fork'layın.
2. `locales/tr-TR.json` dosyasında düzenlemenizi yapın.
3. Pull request (PR) açın.

---

## 👤 Yazar & Katkı Sağlayan

- **Emir Topaloğlu** - [@emirrtopaloglu](https://github.com/emirrtopaloglu)
