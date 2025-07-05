# AI Trading Signal Agent untuk n8n

Repositori ini berisi template workflow n8n untuk membangun sistem AI trading signal yang komprehensif, dengan fokus khusus pada analisis forex dan XAU/USD.

## Template yang Tersedia

1. **AGI Forex Trading Intelligence System** (`agi_forex_trading_system.json`) - NEW!
   - Sistem trading berbasis AGI dengan analisis multi-dimensi
   - Integrasi data teknikal, sentimen, korelasi, dan ekonomi
   - Sistem self-learning yang meningkatkan akurasi dari waktu ke waktu
   - Analisis multi-timeframe komprehensif dengan identifikasi market regime
   - Rekomendasi trading yang sangat detail dengan manajemen risiko dinamis

2. **Forex AI Trading Signal Agent** (`forex_ai_trading_signal_agent.json`)
   - Menganalisis 11 pasangan forex utama termasuk XAU/USD
   - Menggunakan indikator teknikal dan analisis AI
   - Mengirimkan sinyal trading melalui Telegram
   - Menyediakan analisis multi-timeframe (5m, 15m, 1h, 4h, D)

3. **Advanced Forex SNR Analysis** (`advanced_forex_snr_analysis.json`)
   - Analisis mendalam Support and Resistance (SNR)
   - Identifikasi struktur pasar dan level kunci
   - Rekomendasi setup trading dengan manajemen risiko
   - Analisis seperti pro trader dengan pendekatan price action

## Fitur Utama

- **Analisis Real-time**: Monitoring pergerakan harga secara real-time
- **Analisis SNR**: Identifikasi level support dan resistance kunci
- **Analisis AI**: Menggunakan model AI untuk menganalisis data pasar
- **Multi-timeframe**: Analisis berbagai timeframe untuk konfirmasi sinyal
- **Manajemen Risiko**: Rekomendasi entry, stop loss, dan take profit
- **Notifikasi**: Pengiriman sinyal melalui Telegram

## Cara Menggunakan

1. Import template JSON ke dalam instance n8n Anda
2. Konfigurasi kredensial API yang diperlukan:
   - API Forex untuk data pasar
   - OpenAI API untuk analisis AI
   - Telegram Bot API untuk notifikasi
3. Sesuaikan parameter sesuai kebutuhan Anda
4. Aktifkan workflow dan mulai terima sinyal trading

## Rekomendasi Pengembangan Lebih Lanjut

1. **Integrasi dengan Broker**: Tambahkan node untuk eksekusi otomatis melalui API broker
2. **Dashboard Performa**: Buat dashboard untuk melacak performa sinyal
3. **Analisis Sentimen**: Tambahkan analisis berita dan sentimen pasar
4. **Backtesting**: Implementasikan sistem backtesting untuk validasi strategi
5. **Penyesuaian Risiko**: Tambahkan perhitungan posisi size berdasarkan risk per trade

## Catatan Penting

Template ini disediakan untuk tujuan pendidikan dan pengembangan. Selalu lakukan uji coba dan validasi sebelum menggunakan sinyal untuk trading dengan uang sungguhan. Trading forex dan emas memiliki risiko tinggi dan dapat mengakibatkan kerugian modal.