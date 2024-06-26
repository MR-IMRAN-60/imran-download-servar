# Media Downloader
![Imran-Ahmed](https://i.imgur.com/Qhydmxw.jpeg)
## Installation
```sh
npm i imran-download-servar
```
## Usage 

# Instagram 
```ts
const { igdl } = require('imran-download-servar')

const url = 'https://www.instagram.com/p/ByxKbUSnubS/?utm_source=ig_web_copy_link'
const data = await igdl(url)
console.log(data) // JSON
```          
# Tiktok
```ts
const { ttdl } = require('imran-download-servar') 

const url = 'https://www.tiktok.com/@omagadsus/video/7025456384175017243?is_from_webapp=1&sender_device=pc&web_id6982004129280116226'
// Using tiktokdl
const data = await ttdl(url)
console.log(data) // JSON
```
# Facebook
```ts
const { fbdown } = require('imran-download-servar')

const url = 'https://fb.watch/mcx9K6cb6t/?mibextid=8103lRmnirLUhozF'
const data = await fbdown(url)
console.log(data) // JSON
```
# Twitter
```ts
const { twitter } = require('imran-download-servar')

const url = 'https://twitter.com/gofoodindonesia/status/1229369819511709697'
const data = await twitter(url)
console.log(data) // JSON
```
# YouTube
```ts
const { youtube } = require('imran-download-servar')

const url = 'https://youtube.com/watch?v=C8mJ8943X80'
const data = await youtube(url)
console.log(data) // JSON
```


## Catatan Penting

1. Downloader ini hanya dapat digunakan untuk mengunduh media yang bersifat publik atau dapat diakses oleh umum.
2. Aplikasi ini tidak berafiliasi atau didukung oleh aplikasi manapun.
3. Pastikan bahwa Anda memiliki izin atau hak cipta untuk mengunduh media sebelum menggunakan aplikasi ini.

## Kontribusi dan Pelaporan Masalah

Jika Anda menemukan masalah atau ingin berkontribusi pada pengembangan aplikasi ini, silakan kunjungi halaman [GitHub repository](https://github.com/MR-IMRAN-60) kami.

## Lisensi

btch-downloader dilisensikan di bawah [MIT License](https://opensource.org/licenses/MIT). Silakan merujuk pada file LICENSE untuk informasi lebih lanjut.
