![Logo](https://files.catbox.moe/obf6o0.jpg)

**😼 xey | 1.7.0** | ***create by xey***


```> Simple WhatsApp bot Using Library Baileys```

```javascript
{
  message: Message { conversation: '>_ Welcome to xey' },
  type: 'conversation',
  msg: '>_ Welcome to xey',
  isMedia: false,
  key: {
    remoteJid: '6285165556936@s.whatsapp.net',
    participant: '6285165556936@s.whatsapp.net',
    fromMe: false,
    id: '5780C33F89C0BE600B6D71DF79C4FC02'
  },
  cht: '6285165556936@s.whatsapp.net',
  fromMe: false,
  id: '5780C33F89C0BE600B6D71DF79C4FC02',
  device: 'android',
  isBot: false,
  isGroup: false,
  participant: '6285165556936@s.whatsapp.net',
  sender: '6285165556936@s.whatsapp.net',
  mentions: [],
  body: '>_ Welcome to xey',
  prefix: '',
  command: '>_',
  args: [ 'Welcome', 'to', 'xey' ],
  text: 'Welcome to xey',
  isOwner: true,
  download: [AsyncFunction (anonymous)]
}
```
## ⚙️ Settings Bot ***( settings.js )***

```javascript
const fs = require('node:fs');

const config = {
    owner: ["6285215909004"],
    name: "- xey - Simple WhatsApp bot",
    sessions: "sessions",
    sticker: {
      packname: "Made by ",
      author: "xey"
    },
   messages: {
      wait: "*( Loading )* Tunggu Sebentar...",
      owner: "*( Denied )* Kamu bukan owner ku !",
      premium: "*( Denied )* Fitur ini khusus user premium",
      group: "*( Denied )* Fitur ini khusus group",
   },
   database: "xey-db",
   tz: "Asia/Jakarta"
}

module.exports = config
```


## 👨‍💻 How to install/run


```bash
$ git clone https://github.com/xeyyzuv2/xeyyzuv2.git
$ cd xeyBot
$ npm install
$ npm start
```

## ☘️ Example Features
Berikut cara menambahkan fitur pada bot ini

## 1. Plugins

```javascript

module.exports = {
    command: "tes", //- Nama fitur nya
    alias: ["tesbot", "testing"], //- Short cut command
    category: ["main"], //- Kategori Fitur 
    settings: {
        owner: false, //-  Apakah Fitur ini khusus owner ?
        group: false, // - Apakah Fitur ini khusus group ?
     },
    description: "Tes bot saja", //- Penjelasan tentang fitur nya
    loading: true, //- Ingin menambahkan loading messages ?
 async run(m, { sock, Func, Scraper, text, config }) {
    m.reply("> Bot Online ✓")
  }
}
```
## 2. Case

```javascript
case "tes" : {
     m.reply("> Bot Online ✓")
   }
break
```
## 📢 Discussion 
Jika ingin mengenal seputar Script ini lebih dalam lagi
silahkan mampir ke komunitas kami

[![WhatsApp Group](https://img.shields.io/badge/WhatsApp%20Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/ErlaFMvdnfu5OGxCVGJW8V)

[![WhatsApp channel](https://img.shields.io/badge/WhatsApp%20Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://whatsapp.com/channel/0029Vb0YWvYJ3jusF2nk9U1P)

