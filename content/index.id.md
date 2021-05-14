---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "Aksesibilitas Perangkat Seluler W3C"
nav_title: "Aksesibilitas Perangkat Seluler W3C"

description: 

lang: id
last_updated: 2021-05-14
translators: 
- name: "Fri Rasyidi"   # Replace @@ with translator name
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple translators
# contributors:
# - name: "@@"   # Replace @@ with contributor name, or delete this line if none
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple contributors

permalink: /standards-guidelines/mobile/id

changelog: /standards-guidelines/mobile/changelog/

github:
  repository: w3c/wai-mobile
  path: content/index.md

feedbackmail: wai@w3.org

# In the footer below:
# Do not translate or change CHANGELOG or ACKNOWLEDGEMENTS.
# Translate the other words below, including "Date:" and "Editor:"
# Translate the Working Group name. Leave the Working Group acronym in English.
# Do not change the dates in the footer below.
footer: >
  <p><strong>Tanggal:</strong> Diperbarui 14 May 2021. Pertama kali dipublikasikan Januari 2008. CHANGELOG.</p>
  <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Kontributor: <a href="http://www.w3.org/People/Brewer/">Judy Brewer</a>.</p>
  <p>Dikembangkan dengan masukan dari Kelompok Kerja Edukasi dan Pendampingan (<a href="http://www.w3.org/WAI/EO/">EOWG</a>).</p>
ref: /standards-guidelines/mobile/
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Ringkasan" class="full" %}
{:/}

-   **Aksesibilitas perangkat seluler telah dicakup dalam pedoman/standar aksesibilitas W3C WAI**. Tidak ada pedoman terpisah untuk aksesibilitas perangkat seluler.
-   W3C sedang mengembangkan pedoman persyaratan terbaru dan lebih spesifik terkait aksesibilitas perangkat seluler.
-   **Lingkup kerja [Satuan Tugas Aksesibilitas Perangkat Seluler](https://www.w3.org/WAI/GL/mobile-a11y-tf/) WAI mencakup:**
    -   [Aksesibilitas Perangkat Seluler: Bagaimana WCAG 2.0 dan Pedoman W3C/WAI Lainnya Diterapkan pada Perangkat Seluler](http://www.w3.org/TR/mobile-accessibility-mapping/)
    -   Kriteria Sukses dan Teknik WCAG 2
    -   Mengintegrasikan aksesibilitas perangkat seluler di standar W3C yang akan datang

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Daftar Isi" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Lebih dari "Perangkat Seluler" {#intro}

"Aksesibilitas perangkat seluler (*mobile*)" merujuk pada membuat situs dan aplikasi web yang lebih aksesibel untuk penyandang disabilitas ketika mereka menggunakan telepon seluler (ponsel) dan perangkat seluler lainnya. Lingkup kerja WAI pada area ini membahas masalah aksesibilitas saat menggunakan berbagai perangkat untuk berinteraksi dengan web, termasuk:

-   telepon dan tablet
-   TV digital
-   perangkat yang dapat dikenakan seperti jam tangan pintar
-   perangkat pada dasbor mobil dan bagian belakang sandaran kursi pesawat
-   perangkat pada peralatan rumah tangga
-   perangkat "Internet untuk Segala (IoT)" lainnya

Membahas berbagai hal:

-   layar sentuh
-   layar berukuran kecil
-   berbagai mode input, termasuk suara dan sentuhan 3D yang dimungkinkan oleh sensor tekanan
-   perangkat yang digunakan di berbagai situasi, seperti di bawah terik mentari
-   dan sebagainya

## W3C WAI Membahas Aksesibilitas Perangkat Seluler {#covered}

**Standar aksesibilitas WAI terkait aksesibilitas perangkat seluler**:

-   Pedoman Aksesibilitas **Konten Web** ([WCAG](/standards-guidelines/wcag/)) mencakup halaman dan aplikasi web, termasuk konten yang digunakan pada perangkat seluler.
    -   Untuk mempelajari bagaimana WCAG 2.0 dapat diterapkan pada konten web, aplikasi web, aplikasi native, dan aplikasi hibrida yang menggunakan komponen dalam aplikasi native pada perangkat seluler, lihat [Aksesibilitas Perangkat Seluler: Bagaimana WCAG 2.0 dan Pedoman W3C/WAI Lainnya Diterapkan pada Perangkat Seluler](http://www.w3.org/TR/mobile-accessibility-mapping/).
    -   Sumber informasi yang lebih umum mengenai aplikasi perangkat seluler ada di [WCAG2ICT: Menerapkan WCAG 2.0 ke Teknologi Informasi dan Komunikasi Non-Web](/standards-guidelines/wcag/non-web-ict/).
    -   WCAG 2.1, dipublikasikan pada Juni 2018, mencakup persyaratan baru ("kriteria sukses") yang membahas aksesibilitas perangkat seluler. Hal tersebut dikenalkan melalui [[Yang Baru di WCAG 2.1]](/standards-guidelines/wcag/new-in-21/).
-   Pedoman Aksesibilitas **Agen Pengguna** ([UAAG](/standards-guidelines/uaag/)) mencakup browser web dan "agen pengguna" lainnya, termasuk browser pada perangkat seluler.
    -   Sebagai contoh dari bagaimana browser web yang mengikuti UAAG menguntungkan para penyandang disabilitas saat menggunakan Web pada perangkat seluler, lihat [Contoh Aksesibilitas Perangkat Seluler dari UAAG](http://www.w3.org/TR/IMPLEMENTING-UAAG20/mobile).
    -   Bagi yang ingin menjelajahi masalah ini lebih lanjut, lihat [Menerapkan UAAG pada Telepon Seluler](http://www.w3.org/WAI/UA/work/wiki/Applying_UAAG_to_Mobile_Phones).
-   Pedoman Aksesibilitas **Sarana Penulisan** ([ATAG](/standards-guidelines/atag/)) mencakup perangkat lunak yang digunakan untuk membuat halaman dan aplikasi web, termasuk untuk perangkat seluler.
-   **[WAI-ARIA](/standards-guidelines/aria/)** (Aplikasi Internet Kaya yang Aksesibel) membahas cara untuk membuat konten web lebih aksesibel, terutama pada konten dinamis dan kontrol antarmuka tingkat lanjut. Berlaku pula pada aplikasi web dan saat mengakses situs web melalui perangkat seluler.

**W3C membahas aksesibilitas perangkat seluler.** WAI memastikan inti dari teknologi W3C mendukung aksesibilitas, termasuk hal-hal yang esensial dalam web pada perangkat seluler. Semua pekerjaan W3C ditinjau untuk aksesibilitas oleh Kelompok Kerja Arsitektur Platform Aksesibel ([APA](https://www.w3.org/WAI/APA/)) WAI.

Pekerjaan W3C terkait perangkat seluler termasuk [Praktik Terbaik untuk Aplikasi Web pada Perangkat Seluler](http://www.w3.org/TR/mwabp/) dan [Praktik Terbaik untuk Web pada Perangkat Seluler](http://www.w3.org/TR/mobile-bp/). Untuk ringkasan terkait teknologi yang dikembangkan W3C untuk meningkatkan kapabilitas aplikasi web dan bagaimana penerapan spesifiknya pada perangkat seluler, lihat [Standar untuk Aplikasi Web pada Perangkat Seluler](http://www.w3.org/Mobile/mobile-web-app-state/).

## Dapatkan Pemberitahuan {#updates}

Jika Anda ingin mendapatkan notifikasi terkait hasil kerja terbaru seputar aksesibilitas perangkat seluler di W3C WAI, lihat [[Dapatkan Berita WAI]](/news/subscribe/).

## Ikut Terlibat {#involved}

Informasi umum tersedia di [[Berpartisipasi di WAI]](/about/participating/).

Sebagian besar pekerjaan WAI yang berhubungan dengan aksesibilitas perangkat selular melalui [Satuan Tugas Aksesibilitas Perangkat Seluler](https://www.w3.org/WAI/GL/mobile-a11y-tf/). Jika Anda ingin lebih terlibat dengan pekerjaan WAI terkait aksesibilitas perangkat seluler, mohon kirimkan email beserta informasi terkait ketertarikan dan waktu yang bisa Anda luangkan kepada fasilitator Satuan Tugas kami [Kim Patch dan Kathy Wahlbin](mailto:kathy@interactiveaccessibility.com,Kim@redstartsystems.com?cc=wai@w3.org,shadi@w3.org&subject=Mobile%20Accessibility%20Task%20Force%20Enquiry) dengan tembusan (CC) ke Staf WAI (wai@w3.org).

## Tentang W3C dan WAI {#about}

Konsorsium World Wide Web (W3C) adalah konsorsium internasional dimana Anggota organisasi, pekerja tetap, dan publik bekerja sama untuk mengembangkan standar Web. W3C mengejar misinya melalui pembuatan standar dan pedoman Web yang dirancang untuk memastikan pertumbuhan jangka panjang bagi Web. Untuk mempelajari lebih lanjut, lihat [Tentang W3C](http://www.w3.org/Consortium/).

Inisiatif Aksesibilitas Web (WAI) W3C menyatukan individu dan organisasi dari seluruh dunia dalam mengembangkan strategi, pedoman, dan sumber informasi untuk membantu membuat Web yang aksesibel bagi penyandang disabilitas. Untuk mempelajari lebih lanjut, lihat [Situs Web WAI](http://www.w3.org/WAI/).
