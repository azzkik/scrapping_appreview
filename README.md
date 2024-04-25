# Scrapping app review
Pada Project kali ini kelompok saya melakukan scrapping riview salah satu aplikasi yang berada di playstore. Aplikasi yang kami ambil sebagai contoh adalah chatGPT dengan ulasan berbahasa inggris. Kami menggunakan package Google Play Scrapper dengan menggunakan `pip install google-play-scraper` dan melakukan imort package dan eksekusinya sebagai berikut:
```yaml
from google_play_scraper import Sort, reviews_all

scrapreview = reviews_all(
    app_id='com.openai.chatgpt',  # ID aplikasi (terletak di akhir link)
    lang='en',  # defaults to ‘en’ (untuk mengatur bahasa)
    country='us',  # defaults to ‘us’ (region ulasan yg diambil)
    sort=Sort.MOST_RELEVANT,  # defaults to Sort.MOST_RELEVANT
    filter_score_with=None  # defaults to None (means all score) (bintang dari ulasan)
)
```
Project kali ini bersifat Final dan telah dikumpulkan untuk dinilai.

## Laporan Project

Untuk laporan dari project yang kelompok saya kerjakan bisa dilihat pada link berikut ini.
[Laporan](https://laporanproj-azki.blogspot.com/2024/01/scrapping-ulasan-playstore-dengan.html)

## Contributors ✨

Terimakasih banyak kepada kelompok saya:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://www.instagram.com/azkiyakmal/"><img src="https://github.com/azzkik/azkiyaakmal/blob/main/images/1.png" width="100px;" alt="Muhammad Azkiya' Akmal"/><br /><sub><b>Muhammad Azkiya' Akmal</b></sub></a><br /></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.instagram.com/larasatiramadhani/"><img src="https://github.com/azzkik/azkiyaakmal/blob/main/images/3.png" width="100px;" alt="Larasati Romadhani Yunita Putri"/><br /><sub><b>Larasati Romadhani Yunita Putri</b></sub></a><br /></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.instagram.com/lrssttt/"><img src="https://github.com/azzkik/azkiyaakmal/blob/main/images/2.png" width="100px;" alt="Larasati"/><br /><sub><b>Larasati</b></sub></a><br /></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.instagram.com/chelliinn/"><img src="https://github.com/azzkik/azkiyaakmal/blob/main/images/5.png" width="100px;" alt="Mirechelin Kristanaya"/><br /><sub><b>Mirechelin Kristanaya</b></sub></a><br /></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.instagram.com/setyobudiiii_/"><img src="https://github.com/azzkik/azkiyaakmal/blob/main/images/4.png" width="100px;" alt="Setyobudi Utomo"/><br /><sub><b>Setyobudi Utomo</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Ucapan Terimakasih

Kami berterimakasih kepada [Nur Anisa Damayanti](https://medium.com/@nuranisad) untuk penjelasan mengenai Google Play Scrapper yang kami gunakan pada project kali ini. Untuk informasi penggunaan lebih lengkapnya dapat dilihat pada Github [JoMingyu](https://github.com/JoMingyu/google-play-scraper).
