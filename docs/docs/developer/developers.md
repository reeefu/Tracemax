---
title: Tim Pengembang
---

# Tim Pengembang

TraceMax dikembangkan di **Departemen Geofisika, Universitas Padjadjaran** dan dirilis sebagai perangkat lunak terbuka di bawah lisensi [GNU General Public License v3](https://www.gnu.org/licenses/gpl-3.0.html). Kode sumber, dokumentasi, dan riwayat pengembangan dapat diakses publik di [github.com/reeefu/TraceMax](https://github.com/reeefu/TraceMax).

## Pengembang

<div class="grid cards" markdown>

-   ### Prof. Dr. rer. nat. Yudi Rosandi, M.Si.

    **Pengembang awal**

    Departemen Geofisika, Universitas Padjadjaran

    :material-email: [rosandi@geophys.unpad.ac.id](mailto:rosandi@geophys.unpad.ac.id)

-   ### Arief Rahman Hakim Ritonga

    **Pengembang & pemelihara**

    Departemen Geofisika, Universitas Padjadjaran

    :material-email: [ariefrahman5317@gmail.com](mailto:ariefrahman5317@gmail.com)  
    :material-github: [@reeefu](https://github.com/reeefu)

</div>

## Kontribusi

| Pengembang | Kontribusi |
|---|---|
| Yudi Rosandi | Rancangan dan kode awal TraceMax (2022): editor trace seismik, plotter, dan first-break picking manual |
| Arief Rahman Hakim Ritonga | Refaktor ke struktur modular (`app/`, `core/`, `fileio/`, `plugin/`), sistem plugin dan ML Auto-Picker (BiLSTM / Uni-LSTM), build executable, serta dokumentasi |

## Hak Cipta & Lisensi

```text
Copyright (C) 2022–2026  Rosandi & Arief Ritonga, Universitas Padjadjaran
```

TraceMax adalah perangkat lunak bebas: Anda boleh menggunakan, mempelajari, mendistribusikan ulang, dan memodifikasinya sesuai ketentuan GNU GPL v3. Karya turunan yang didistribusikan wajib menggunakan lisensi yang sama dan menyertakan kode sumbernya. Teks lisensi lengkap ada di berkas [`LICENSE`](https://github.com/reeefu/TraceMax/blob/main/LICENSE).

## Mengutip TraceMax

Jika TraceMax digunakan dalam penelitian, skripsi, atau publikasi, mohon cantumkan sitasi berikut:

=== "Teks"

    Rosandi, Y., & Ritonga, A. R. H. (2026). *TraceMax: Seismic Trace Editor & First-Break Picker* [Perangkat lunak]. Departemen Geofisika, Universitas Padjadjaran. https://github.com/reeefu/TraceMax

=== "BibTeX"

    ```bibtex
    @software{tracemax,
      author       = {Rosandi, Yudi and Ritonga, Arief Rahman Hakim},
      title        = {{TraceMax}: Seismic Trace Editor \& First-Break Picker},
      year         = {2026},
      organization = {Departemen Geofisika, Universitas Padjadjaran},
      license      = {GPL-3.0-or-later},
      url          = {https://github.com/reeefu/TraceMax}
    }
    ```

## Kontak & Kontribusi

- **Laporan bug dan permintaan fitur**: buka [issue di GitHub](https://github.com/reeefu/TraceMax/issues).
- **Kontribusi kode**: fork repositori, buat branch baru, lalu kirim *pull request*. Panduan membuat plugin ada di [Membuat Plugin](creating-plugins.md).
- **Pertanyaan lain**: hubungi pengembang melalui email di atas.
