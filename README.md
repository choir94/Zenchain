##Pastikan wallet jatingan Anda sudah aktif di OKX:

Wallet Anda harus menggunakan ZenChain Testnet sebagai jaringan.
Pastikan memiliki saldo testnet ZEN untuk mengirim transaksi (meskipun dengan jumlah 0).

##Format Input Data
Untuk transaksi, Anda perlu memformat Input Data seperti berikut:

Gunakan metode 0xf1ec919c (method untuk binding session key).
Tambahkan padding untuk session key:
Hapus 0x dari session key.
Pastikan tidak ada spasi atau karakter tambahan.
Total panjang session key harus sesuai spesifikasi (biasanya 192 karakter).
Contoh hasil gabungan dari contract dan session key
0xf1ec919c000000000000000000000000000000000000000000000000000000000000002000000000000000000000000000000000000000000000000000000000000000606ce39921f7b9e3ef7f4687a85e8fc8c371ed0823c310fb658278da71b690b6490e2e80ee88900dbdacdf3544cebeefc4c19d408b6451e14689999d19df6b19eeb046290cd279b196235bd0c439564f8b9b3634d984409a8bab58b24614b0042f
ket: 0x di awal adalah contract dan 6...tanpa 0x adalah session key

##Kirim Transaksi ke Contract
Buka wallet Anda (di OKX atau aplikasi lain).
Kirim transaksi dengan detail berikut:
To:
0x0000000000000000000000000000000000000802
Amount:
0 (tidak ada jumlah yang dikirimkan).
Input Data:
Gunakan input data yang telah diformat di atas.
