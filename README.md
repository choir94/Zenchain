# Node Zenchain Validator 

**One click installation**
   ```bash
   wget https://raw.githubusercontent.com/choir94/Airdropguide/refs/heads/main/Zen-chain.sh -O Zen-chain.sh
chmod +x Zen-chain.sh
./Zen-chain.sh
   ```
**Jangan lupa Save session Keys**

# Panduan Pengikatan Kunci Sesi dan Transaksi ZenChain

Panduan ini menjelaskan cara mengikat kunci sesi ke dompet Anda dan mengirim transaksi ke kontrak ZenChain menggunakan dompet OKX di testnet ZenChain.

## Prasyarat

Sebelum memulai, pastikan Anda memiliki hal-hal berikut:

1. **Dompet OKX**: Pastikan dompet Anda terhubung ke jaringan testnet ZenChain.
2. **Testnet ZenChain**: Pastikan dompet OKX Anda menggunakan testnet ZenChain.
3. **Session Key**: Session Key yang di dapat dari instalasi node.

## Langkah 1: Pastikan Dompet Anda Terhubung ke Testnet ZenChain

1. Buka **Dompet OKX** Anda.
2. Navigasikan ke bagian **Jaringan** dan pilih **Testnet ZenChain**.

## Langkah 2: Siapkan Data Transaksi

Anda perlu mengirim transaksi ke kontrak ZenChain untuk mengikat kunci sesi Anda. Ikuti langkah-langkah berikut:

### Detail Kontrak:
- **Alamat Tujuan**: `0x0000000000000000000000000000000000000802`
- **Jumlah**: `0` (Tidak ada dana yang diperlukan untuk transaksi ini)
- **Data Input**: Ini adalah data yang akan dikirimkan bersama transaksi. Data ini terdiri dari:

  - **Tanda Tangan Contract**:  
    `0xf1ec919c00000000000000000000000000000000000000000000000000000000000000200000000000000000000000000000000000000000000000000000000000000060`
  
  - **Session Key**: Tambahkan kunci sesi Anda (tanpa awalan `0x` dan tanpa spasi) ke akhir data di atas.
 - Gabungkan tanda tangan contract dengan session key dengan Contoh format 
 '0xf1ec919c00000000000000000000000000000000000000000000000000000000000000200000000000000000000000000000000000000000000000000000000000000060(Session key tanpa 0x)cef646aa3c7a18d0afb82b0aef..hhh'

## DONE

## Support Airdrop Node
Evm wallet

'0x59E997287C18A46a53269A4C599FBf2d2EB1DB31'

https://trakteer.id/AirdropNode/tip

## Join Airdrop Node:  

[Grup Telegram AirdropNode](https://t.me/airdrop_node)
