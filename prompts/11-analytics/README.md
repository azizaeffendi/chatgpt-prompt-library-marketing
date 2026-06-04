# 📊 Analitik & Pelaporan Prompts

> 25+ prompt untuk interpretasi data, membuat laporan, dan insight dari analytics.

## Prompt Utama

---

## 1. INTERPRETASI DATA MARKETING — INSIGHT ACTIONABLE

```
Bantu saya interpretasi data marketing berikut dan berikan insight actionable:

DATA:
[paste data Anda di sini — bisa dalam format tabel, angka, atau deskripsi]

Contoh data:
- CTR Google Ads: 2.1% (benchmark industri: 3.5%)
- Conversion rate landing page: 1.8%
- Email open rate: 18% (turun dari 24% bulan lalu)
- Bounce rate website: 72%
- Top traffic source: Organic (45%), Paid (30%), Social (15%), Direct (10%)
- Best performing page: /blog/cara-marketing-ai (1200 views/bulan)

ANALISIS:
1. Apa yang berjalan baik? (pertahankan dan scale)
2. Apa yang perlu diperbaiki segera? (quick wins)
3. Apa yang perlu diinvestigasi lebih dalam? (anomali)
4. 3 prioritas aksi minggu ini berdasarkan data ini
5. Metrik apa yang seharusnya saya track tapi belum ada di sini?

KONTEKS BISNIS: [deskripsi singkat bisnis dan goal saat ini]
```

---

## 2. LAPORAN MARKETING BULANAN — TEMPLATE

```
Buat template laporan marketing bulanan untuk [BISNIS].

PERIODE: [bulan dan tahun]
AUDIENCE LAPORAN: [owner / investor / klien / tim internal]
TOOLS YANG DIGUNAKAN: [Google Analytics / Meta Ads / dll]

STRUKTUR LAPORAN:

EXECUTIVE SUMMARY (1 halaman):
- KPI utama bulan ini vs target vs bulan lalu
- Top 3 win bulan ini
- Top 3 masalah/tantangan
- Rekomendasi utama untuk bulan depan

CHANNEL BREAKDOWN:
Untuk setiap channel (SEO / Paid / Social / Email):
- Metrik utama
- Perbandingan dengan bulan lalu (% naik/turun)
- Insight: mengapa naik/turun
- Next action

CONTENT PERFORMANCE:
- Konten terbaik (top 5 berdasarkan traffic/engagement/conversion)
- Insight: format/topik apa yang paling efektif

CONVERSION FUNNEL:
- Visualisasi funnel (awareness → consideration → conversion)
- Bottleneck terbesar di mana

RENCANA BULAN DEPAN:
- 3 fokus utama
- Budget allocation
- Eksperimen yang akan dicoba

Format output: Siap untuk di-copy ke Google Docs / Notion.
```

---

## 3. UTM TRACKING STRATEGY

```
Buat UTM tracking strategy lengkap untuk [BISNIS].

CAMPAIGN YANG AKAN DITRACK:
- [Campaign 1: nama dan channel]
- [Campaign 2: nama dan channel]

BUAT:

1. UTM NAMING CONVENTION:
Format: utm_source / utm_medium / utm_campaign / utm_content / utm_term
Standar penamaan yang konsisten (lowercase, underscore, bahasa Inggris)

2. UTM BUILDER TABLE:
| Campaign | Source | Medium | Campaign | Content | Term |
|----------|--------|--------|----------|---------|------|
| [contoh untuk setiap channel]

3. GOOGLE ANALYTICS SETUP:
- Goals/Conversions yang harus ditrack
- Custom dimensions yang disarankan
- Dashboard template yang berguna

4. REPORTING DASHBOARD:
Metrik apa yang harus ada di dashboard utama dan bagaimana membacanya.
```