# Rekod Penggunaan AI Code Assistant

## Nama AI Code Assistant
ChatGPT

## Prompt yang digunakan
Terangkan cara menggunakan pandas untuk menapis rekod
yang mempunyai nilai confidence 0.70 dan ke atas.

## Cadangan yang diberikan oleh AI
AI mencadangkan penggunaan:

filtered_data = data[data["confidence"] >= threshold]

## Bahagian kod yang dibantu
Fungsi filter_data() dalam fail analysis.py.

## Perubahan yang saya lakukan
Saya menambah pengesahan untuk memastikan nilai threshold
berada antara 0 hingga 1. Saya juga menggunakan .copy()
supaya data asal tidak diubah.

## Cara saya menguji kod
Saya menjalankan aplikasi menggunakan nilai threshold 0.70.
Program menghasilkan tujuh rekod dan saya membandingkan
keputusannya dengan data asal.

## Satu manfaat AI Code Assistant
AI dapat membantu menerangkan sintaks pandas dan memberikan
cadangan penyelesaian dengan lebih cepat.

## Satu batasan AI Code Assistant
Cadangan AI mungkin mengandungi kesalahan atau tidak memenuhi
keperluan tugasan. Semua kod perlu difahami, disemak dan diuji
oleh pelajar.