# farm-guard-solana
Farm Guard adalah game PvE berbasis pixel-art sederhana yang dibuat menggunakan Godot Engine, di mana pemain berperan sebagai petani yang mempertahankan diri dari serangan musuh. Game ini telah terintegrasi dengan Solana blockchain, memungkinkan pemain untuk menghubungkan wallet Phantom/Backpack langsung dari game, game masih belum selesai.

# Farm Guard – Godot x Solana Web3 Game

<img src="screenshot.png" width="600" />

## Deskripsi

**Farm Guard** adalah game PvE berbasis pixel-art sederhana yang dibuat menggunakan Godot Engine 4.x dan terintegrasi dengan Solana blockchain.

Game ini memungkinkan pemain untuk menghubungkan wallet Solana (Phantom/Backpack) melalui browser, sehingga setiap pemain dapat diverifikasi serta siap untuk sistem reward berbasis blockchain.

## Fitur

- 🎮 Game PvE pixel-art, gameplay sederhana dan adiktif.
- 🔗 **Connect & Disconnect Wallet:**  
  - Integrasi tombol Connect/Disconnect Wallet langsung di menu utama.
  - Mendukung wallet Solana via Phantom/Backpack extension.
- 🌐 **Export HTML5**:  
  - Dapat dimainkan langsung di browser web modern.
- ⚡ **Siap Integrasi Web3**:  
  - Address wallet diterima langsung di game, siap dikembangkan untuk reward/token.

## Teknologi

- **Godot Engine 4.x**
- **Solana JS Wallet Adapter (Phantom/Backpack)**
- **HTML5 + JavaScript Bridge**

## Cara Menjalankan di Lokal

1. Export project ke HTML5 dari Godot (disable Threads di export setting).
2. Jalankan server lokal:
   ```bash
   python3 -m http.server 8080
