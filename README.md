# Geek Knowledge Indonesia

Database fakta singkat berbahasa Indonesia untuk perangkat Waveshare ESP32-S3-GEEK.

## Format data
Setiap file kategori berisi array JSON. Setiap item memiliki:
- `id`: ID unik fakta
- `category`: kategori
- `title`: judul singkat
- `fact`: penjelasan singkat
- `age`: sasaran usia
- `safe`: penanda konten ramah anak
- `reviewed`: status pemeriksaan editorial
- `source_url`: tautan rujukan untuk pemeriksaan fakta

## Kategori
- [animals](./data/animals.json)
- [nature](./data/nature.json)
- [space](./data/space.json)
- [science](./data/science.json)
- [technology](./data/technology.json)
- [history](./data/history.json)
- [general](./data/general.json)
- [ocean](./data/ocean.json)

Indeks: [index.json](./index.json)

## Catatan
Dataset ini adalah batch awal dan akan dikembangkan bertahap. Tautan sumber merupakan rujukan pemeriksaan, bukan klaim bahwa semua kalimat merupakan kutipan langsung dari sumber. Periksa kembali isi dan tautan sebelum rilis produksi.
