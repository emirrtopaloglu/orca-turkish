# orca-turkish

[Orca](https://github.com/stablyai/orca) için Türkçe (tr-TR) dil paketi eklentisi.

**Geliştirici & Katkıda Bulunan:** [Emir Topaloğlu](https://github.com/emirrtopaloglu)

---

## 🇹🇷 Durum & Kapsam

Orca'nın çevrilebilir tüm kullanıcı arayüzü kataloğu eksiksiz olarak Türkçeye kazandırılmıştır:

- **12.270+ / 12.275** çevrilebilir metin (%99.99+ kapsama)
- **Kapsanan Alanlar:**
  - Ayarlar & Yapılandırma panelleri
  - Sol ve sağ kenar çubukları
  - Kod editörü, çalışma alanları (workspaces) ve çalışma ağaçları (worktrees)
  - Dahili terminal ve komut paleti
  - GitHub, GitLab, Linear ve Jira entegrasyonları
  - Karşılama ekranı (onboarding) ve ilk kurulum sihirbazları
  - Mobil eşlikçi uygulama ve pano (dashboard)
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

1. **Geliştirici Odaklı Terminoloji:** Geliştiricilerin aşina olduğu yerleşik terimler (`branch`, `commit`, `worktree`, `workspace`, `pull request`, `merge`, `rebase`, `stash` vb.) GitHub, GitLab ve VS Code Türkçe yerelleştirme standartlarına uygun olarak korunmuş ve doğal Türkçe eklerle harmanlanmıştır.
2. **Değişken & Yer Tutucu Bütünlüğü:** Tüm arayüz şablon değişkenleri (`{{value0}}`, `{{count}}`, HTML/KBD etiketleri vb.) bozulmadan %100 doğrulukla işlenmiştir.
3. **Orca Eklenti Doğrulaması:** Paket, Orca'nın `parsePluginLanguagePackArtifact` çalışma zamanı güvenlik kurallarına (maksimum 20.000 girdi, maksimum derinlik 16, korumalı güvenlik dizeleri muhafazası) tam uyumludur.

---

## 🤝 Katkıda Bulunma

Hata bildirimleri, çeviri iyileştirmeleri ve önerileriniz için:
1. Depoyu fork'layın.
2. `locales/tr-TR.json` dosyasında düzenlemenizi yapın.
3. Pull request (PR) açın.

---

## 👤 Yazar & Katkı Sağlayan

- **Emir Topaloğlu** - [@emirrtopaloglu](https://github.com/emirrtopaloglu)
