# PeatWatch – Smart Peatland Protection

Konsep UI/UX aplikasi pemantauan kawasan gambut yang berpotensi mengalami kebakaran.

**Fitur**

- Monitoring kelembapan gambut (sensor lapangan & tinggi muka air)
- Peta kawasan rawan kebakaran
- Informasi kondisi cuaca & indeks cuaca kebakaran
- Pelaporan kanal atau lahan kering
- Monitoring titik api (data satelit)

## Prototipe

Situs statis tanpa build step. Buka `index.html` untuk melihat semua layar, atau langsung salah satu layar:

| Layar | File |
|---|---|
| Beranda | `beranda.html` |
| Peta rawan kebakaran | `peta.html` |
| Monitoring titik api | `titik-api.html` |
| Kelembapan gambut | `sensor.html` |
| Cuaca & bahaya api | `cuaca.html` |
| Lapor kondisi lahan | `lapor.html` |
| Style guide | `style-guide.html` |

Coba lokal:

```bash
python3 -m http.server 8000
```

lalu buka http://localhost:8000.

## Deploy

Workflow `.github/workflows/pages.yml` men-deploy situs ke GitHub Pages setiap kali ada push ke `main`.
Aktifkan sekali di **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Sumber desain

Folder `design/` berisi file asli dari canvas desain (`*.dc.html` + `canvas.json`).

Semua lokasi, angka sensor, dan data titik api di prototipe ini adalah contoh, bukan data nyata.
