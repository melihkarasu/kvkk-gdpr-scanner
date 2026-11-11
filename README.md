# ⚖️ KVKK & GDPR Scanner

**6698 Sayılı KVKK (2024/2026 Reformları), AB GDPR (EU 2016/679), 6563 Sayılı ETK (İYS), 6502 Sayılı TKHK (Mesafeli Sözleşmeler) ve 5651 Sayılı Kanun Uyumlu Kaynak Kod, GitHub Repo ve Canlı Web Sitesi Denetçisi**

- **Kural Seti Temeli:** [`melihkarasu/vibecoding-kvkk-gdpr`](https://github.com/melihkarasu/vibecoding-kvkk-gdpr)
- **4 Tarama Modu:**
  1. **📂 Proje Klasörü / Dosya Seçimi (`webkitdirectory`):** Bilgisayarınızdaki projeyi sunucuya yüklemeden %100 tarayıcı içinde analiz eder.
  2. **🐙 GitHub Repo Tarayıcı:** Herhangi bir GitHub reposunu (`owner/repo`) dosya ağacıyla çekip tüm SQL, React/Next.js, backend ve dokümantasyon dosyalarını denetler.
  3. **💻 Kod / Şema Yapıştır:** SQL migration, form veya backend kodunu anında analiz eder ve uyumlu kod yamasını üretir.
  4. **🌐 Canlı Web Sitesi (URL) Denetimi:** Google Fonts CDN IP sızıntılarını, rızasız çalışan analitik betiklerini, çerez bayraklarını ve form onay kutularını denetler.
- **Tarayıcı İçi LLM Analizi (`kvkk_ai_config`):**
  - Google Gemini (`gemini-3.8-flash`), Google Cloud Vertex AI (`global` bölge, Service Account JSON veya API Key), OpenAI, Anthropic Claude, OpenRouter, Groq, Ollama ve Özel OpenAI-uyumlu uç noktaları destekler.
  - Kod kesitlerini LLM'e göndermeden önce TCKN, IBAN, E-posta, Telefon ve API anahtarlarını deterministik olarak maskeler (`maskPIIAndSecrets`).
  - Tek tıkla **Katmanlı Aydınlatma Metni**, **Açık Rıza Metni**, **`docs/veri-ihlali-mudahale-plani.md` (72 Saat KVK Kurulu Bildirim Planı)** ve **Uygulamalı Kod Yaması** üretir.
