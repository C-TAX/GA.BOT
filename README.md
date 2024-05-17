<div align="center">
<img src="https://i.ibb.co.com/tDJT66m/zerotwo.jpg" alt="GA.BOT" width="400" />

# GA.BOT
  
> I am very very bored, give me a task to update or develop this bot? feature suggestions?

<p align="center">
 GA.BOT Adalah Bot Whatsapp Pintar Dengan Fitur Yang Berguna Untuk Grup Maupun Pribadi Message
</p>

<a href="https://chat.whatsapp.com/IY8OvPk02qxKb1xd0DXtUR" align="center">
  Nomor Whatsapp Bot
</a>

<h3 align="center">Made with 🧠 by</h3>
<p align="center">
  <a href="https://github.com/C-TAX"><img src="https://avatars.githubusercontent.com/u/122194464?s=400&u=593d22d26b4eb1dc9a359bdfefdfd7ac17484308&v=4" height="128" width="128" /></a>
</p>

<p align="center">
  <a href="https://github.com/C-TAX"><img title="Author" src="https://img.shields.io/badge/Author-KILLA-darkred.svg?style=for-the-badge&logo=github" /></a>
</p>

<p align="center">
  <a href="https://github.com/C-TAX/GA.BOT"><img title="Stars" src="https://img.shields.io/github/stars/C-TAX/GA.BOT?color=black&style=flat-square" /></a>
  <a href="https://github.com/C-TAX/GA.BOT/network/members"><img title="Forks" src="https://img.shields.io/github/forks/C-TAX/GA.BOT??color=pink&style=flat-square" /></a>
  <a href="https://github.com/C-TAX/GA.BOT/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/C-TAX/GA.BOT??label=watchers&color=blue&style=flat-square" /></a> <br>
  <a href="https://www.npmjs.com/package/@open-wa/wa-automate"><img src="https://img.shields.io/npm/v/@open-wa/wa-automate.svg?color=green" /></a>
  <img src="https://img.shields.io/node/v/@open-wa/wa-automate" />
  <img src="https://img.shields.io/github/repo-size/C-TAX/GA.BOT" /> <br>
  <a href="https://www.codefactor.io/repository/github/c-tax/ga.bot"><img src="https://www.codefactor.io/repository/github/c-tax/ga.bot/badge" alt="CodeFactor" /></a>
</p>

<p align="center">
  <a href="https://github.com/C-TAX/GA.BOT#Requirements">Persyaratan</a> •
  <a href="https://github.com/C-TAX/GA.BOT#installation">Cara Penginstalan</a> •
  <a href="https://github.com/C-TAX/GA.BOT#features">Fiturnya</a> •
  <a href="https://github.com/C-TAX/GA.BOT#thanks-to">Terimakasih Kepada</a> •
  <a href="https://github.com/C-TAX/GA.BOT#license">lisensi</a>
</p>

<h4 align="center">
  <a href="https://wa.me/qr/VEMR34P6IBSXH1">Author Contact</a>
</h4>
  
<h4 align="center">
<a href="https://www.youtube.com/watch?v=9xHCd2GhA8c">Cara Install</a>
</h4>
</div>

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://www.gyan.dev/ffmpeg/builds/ffmpeg-release-full.7z) (for sticker GIF command)
* Any text editor
* [Magisk](https://download.imagemagick.org/ImageMagick/download/binaries/ImageMagick-7.0.11-13-Q16-HDRI-x64-dll.exe) (Buat nuliskanan kiri folio kanan kiri)
* [Tesseract-ocr](https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-v5.0.0-alpha.20201127.exe) (Buat Fitur image to text)
* [Python](https://www.python.org/ftp/python/3.9.5/python-3.9.5-amd64.exe) (Buat canvas)

# installation
## 📝 Cloning this repo
```bash
> git clone https://github.com/C-TAX/GA.BOT.git
> cd GA.BOT
```

## ✍️ Edit filenya
Edit value yang diperlukan di `settings/setting.json`.
```json
{
    "limitCount": 10,
    "ownerNumber": "",
    "memberLimit": 10,
    "groupLimit": 50,
    "medialimitCount": "5",
    "prefix": "/",
    "vhtearkey": "Your Apikey In Here",
    "apikeyz": "Your Apikey In Here",
    "lolhuman": "Your Apikey In Here",
    "apizeks": "Your Apikey In Here"
}

```

`ownerBot`: your WhatsApp number.  

`prefix`: bot's prefix.  

`vhtearkey`: VHTear API token. Anda bisa mendapatkannya https://api.vhtear.com/ dengan membeli kunci API Nya dan harga 25k Perbulan.

`apikeyz`: Hujan Api token. Anda Bisa Mendapatkannya https://hujanapi.xyz silahkan daftar untuk mendapatkan apikey ,  limit 100/day.

`lolhuman`: Lolhuman token. Anda bisa Mendapatkannya Di https://lolhuman.herokuapp.com/ silahkan daftar untuk mendapatkan apikey

`apizeks` : Api vinz token. Anda bisa mendapatkanya di https://zeks.xyz/ silahkan daftar untuk mendapatkan apikey 

Untuk Mendapatkan Apikey nya , daftar akun terlebih dahulu di website tersebut

## 🔍 Menginstal dependensi
```bash
> npm install
```

## 🆗 Menjalankan bot
Regular node:
```bash
> npm start
```

PM2:
```bash
> pm2 start index.js
> pm2 monit
```

PM2 with cron job (restart after 5 hours):
```bash
> pm2 start index.js --cron "* */5 * * *"
> pm2 monit
```

Setelah itu pindai kode QR menggunakan WhatsApp Anda di ponsel Anda!

# Features


|     Sticker Maker     | Availability |
| :-------------------: | :----------: |
| Send/reply image      |      ✔️      |
| Send/reply GIF        |      ✔️      |
| Send/reply MP4        |      ✔️      |
| Text to sticker       |      ✔️      |
| Text to sticker GIF   |      ✔️      |
| Take Sticker          |      ✔️      |
| Add  Sticker          |      ✔️      |
| Get  Sticker          |      ✔️      |
| Del  Sticker          |      ✔️      |
| List Sticker          |      ✔️      |
| Sticker to image      |      ✔️      |

|     Money Feature     | Availability |
| :-------------------: | :----------: |
| Money Check           |      ✔️      |
| Buy Limit             |      ✔️      |
| Transfer Money        |     Soon      |

|      Downloader     | Availability |
| :-----------------: | :----------: |
| Facebook video      |      ✔️      |
| YouTube audio/video |      ✔️      |
| Joox                |      ✔️      |
| TikTok              |      ✔️      |
| TikTok NoWm         |      ✔️      |
| Twitter             |      ✔️      |
| Instagram post      |      ✔️      |
| Instagram story     |      ✔️      |
| Layarkaca21 film    |      ✔️      |

|        Other        | Availability |
| :-----------------: | :----------: |
| Say                 |      ✔️      |
| Lyric finder        |      ✔️      |
| Shortlink maker     |      ✔️      |
| Wikipedia           |      ✔️      |
| KBBI search         |      ✔️      |
| IG stalk            |      ✔️      |
| SpekHp              |      ✔️      |
| Food receipt finder |      ✔️      |
| TTS                 |      ✔️      |
| AFK                 |      ✔️      |
| Distance            |      ✔️      |
| Find sticker        |      ✔️      |
| List surah          |      ✔️      |
| Math                |      ✔️      |
| Surah               |      ✔️      |
| Random contact      |      ✔️      |
| Play YouTube        |      ✔️      |
| Tafsir Al-Qur'an    |      ✔️      |
| LK21                |      ✔️      |
| Reminder            |      ✔️      |
| Tebak Gambar        |      ✔️      |
| Truth Of Dare       |      ✔️      |
| Next Kuiz           |      ✔️      |
| Stop Kuiz           |      ✔️      |
| Kuis Mtk            |      ✔️      |
| Stop Mtk            |      ✔️      |
| Point              |      ✔️      |
| Image to URL        |      ✔️      |
| Jadwal sholat       |      ✔️      |
| To Mp3              |      ✔️      |
| Bass                |      ✔️      |
| Line sticker latest |      ✔️      |
| Quiziz Hack         |      ✔️      |
| Image To Text       |      ✔️      |
| Cek ongkir          |      ✔️      |

|          Fun          | Availability |
| :-------------------: | :----------: |
| Send                  |      ✔️      |
| Mutualan              |      ✔️      |
| Harta tahta maker     |      ✔️      |
| Zodiac                |      ✔️      |
| Write on paper        |      ✔️      |
| Missing person maker  |      ✔️      |
| Valentine frame maker |      ✔️      |
| Glitch text maker     |      ✔️      |
| SimSimi               |      ✔️      |
| Blackpink logo maker  |      ✔️      |
| Pornhub logo maker    |      ✔️      |
| Galaxy text maker     |      ✔️      |
| TikTok asupan         |      ✔️      |
| PH comment maker      |      ✔️      |
| Triggered effect      |      ✔️      |
| Deep fry effect       |      ✔️      |
| Kiss someone          |      ✔️      |
| 3D Text               |      ✔️      |
| Freefire logo         |      ✔️      |
| Freefire banner       |      ✔️      |

|      WIBU AREA     | Availability |
| :----------------: | :----------: |
| Random neko girl   |      ✔️      |
| Random wallpaper   |      ✔️      |
| Kusonime scrapper  |      ✔️      |
| Komiku scrapper    |      ✔️      |
| Anime tracer       |      ✔️      |
| Random waifu       |      ✔️      |
| Loli Video         |      ✔️      |

|        Bot       | Availability |
| :--------------: | :----------: |
| Bot usage status |      ✔️      |
| Blocked list     |      ✔️      |
| Ping             |      ✔️      |
| Delete message   |      ✔️      |
| Report bug       |      ✔️      |

|        Owner       | Availability |
| :----------------: | :----------: |
| Broadcast          |      ✔️      |
| Clear all messages |      ✔️      |
| Leave all groups   |      ✔️      |
| Ban                |      ✔️      |
| Add premium user   |      ✔️      |
| Add Sewa group     |      ✔️      |
| Halal & Haram      |      ✔️      |
| Setpictmenu        |      ✔️      |


|    Moderation    | Availability |
| :--------------: | :----------: |
| Add              |      ✔️      |
| Kick             |      ✔️      |
| Promote          |      ✔️      |
| Demote           |      ✔️      |
| Leave bot        |      ✔️      |
| Tag All          |      ✔️      |
| Set Icon Grup    |      ✔️      |
| Anti-group link  |      ✔️      |
| Toogle welcome   |      ✔️      |
| Auto-sticker     |      ✔️      |
| Mute group       |      ✔️      |

|        18+         | Availability |
| :----------------: | :----------: |
| Fetish             |      ✔️      |
| Waifu NSFW         |      ✔️      |
| Waifu 18+          |      ✔️      |
| Xvideos            |      ✔️      |
| Xvidl              |      ✔️      |
| Xnxx               |      ✔️      |
| Xnxxdl             |      ✔️      |
| nHentai downloader |      ✔️      |

## Troubleshooting
Fix Stuck on linux, install google chrome stable: 
```bash
> wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
> sudo apt install ./google-chrome-stable_current_amd64.deb
```

# Thanks to
* [`open-wa/wa-automate-nodejs`](https://github.com/open-wa/wa-automate-nodejs)
* `ALLAH SWT`
* `NABI MUHAMMAD SAW`
* `ORANG TUA`
  
