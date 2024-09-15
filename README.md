<p align="center">
  <a href="" rel="noopener">
 <img width=150px height=50px src="https://sinhalasub.lk/wp-content/uploads/2020/11/2019.10.7.19h56m33sLAY0.png" alt="sinhalasub"></a>
</p>


<h2 align="center">SinhalaSub.LK Movie Downloader</h2>





## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Authors](#authors)

## 🧐 About <a name = "about"></a>

The unofficial Scrap <a href="https://sinhalasub.lk/" > [https://sinhalasub.lk/] </a>

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Installing


```sh
yarn add @DarkYasiyaofc/sinhalasub-movie
```

or

```sh
npm i @DarkYasiyaofc/sinhalasub-movie
```

## 🎈 Usage <a name="usage"></a>

```ts
var { getMovies, getMovieDL, getMoviesSearch }  = require('@DarkYasiyaofc/sinhalasub-movie')

```
## Get Movies/Twshows List 


```ts
// By Search
var text = 'avengers' //movie name
await getMovies(text) 
```
```ts

//The results will look like this.

{
  status: true,
  creator: 'DARK YASIYA',
  result: [
    {
      title: 'Thangalaan (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 7.5',
      year: '2024',
      link: 'https://sinhalasub.lk/movies/thangalaan-2024-sinhala-subtitles/',        
      image: 'https://sinhalasub.lk/wp-content/uploads/2024/08/dAci50FwevkdWIUzQWpdz7kSKHe-150x150.jpg',
      description: 'Thangalaan Sinhala Sub Thangalaan Sinhala Subtitles Thangalaan (2024) Sinhala Sub Thangalaan (2024) Sinhala Subtitles Thangalaan (2024) Sinhala Subtitles | “K.G.F ආරම්භය” | සිංහල උපසිරැසි සමඟ ගැන ...'
    },
    {
      title: 'K.G.F: Chapter 2 (2022) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 8.3',
      year: '2022',
      link: 'https://sinhalasub.lk/movies/k-g-f-chapter-2-2022-sinhala-subtitles/',   
      image: 'https://sinhalasub.lk/wp-content/uploads/2022/05/jxopEOrF2oIOQxsuvjdmgANqDOU-150x150.jpg',
      description: 'KGF 2 Sinhala Subtitles K.G.F: Chapter 2 Sinhala Subtitles K.G.F: 
Chapter 2 (2022) Sinhala Subtitles The blood-soaked land of Kolar Gold Fields (KGF) has a new overlord now – Rocky, whose name ...'
    },
    {
      title: 'K.G.F: Chapter 1 (2018) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 8.3',
      year: '2018',
      link: 'https://sinhalasub.lk/movies/k-g-f-chapter-1-2018-sinhala-subtitles/',   
      image: 'https://sinhalasub.lk/wp-content/uploads/2020/11/ltHlJwvxKv7d0ooCiKSAvfwV9tX-150x150.jpg',
      description: 'KGF 1 (2018) Sinhala Subtitles A period drama set in the 1970s, KGF follows the story of a fierce rebel who rises against the brutal oppression in Kolar Gold Fields and becomes the symbol of hope ...'
    },
    {
      title: 'Yuva (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: '',
      year: '2024',
      link: 'https://sinhalasub.lk/movies/yuva-2024-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2024/04/50qZ0Sdc6vQMgVhYP0WIYaL4ryZ-150x150.jpg',
      description: 'Yuva Sinhala Sub Yuva Sinhala Subtitles Yuva (2024) Sinhala Sub Yuva (2024) Sinhala Subtitles Yuva (2024) – මල්ලවපොර පිටිය ජයගත් ඩිලිවරි කොල්ලා සුබ දවසක
් ෆිල්ම් පිස්සනි… දින දෙකකින් ...'
    },
    {
      title: 'Ooru Peru Bhairavakona (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',   
      imdb: 'IMDB 6.6',
      year: '2024',
      link: 'https://sinhalasub.lk/movies/ooru-peru-bhairavakona-2024-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2024/02/bPqtaVDJI2E8SheBhCgtktyBw6a-150x150.jpg',
      description: 'Ooru Peru Bhairavakona Sinhala Sub Ooru Peru Bhairavakona Sinhala 
Subtitles Ooru Peru Bhairavakona (2024) Sinhala Sub Ooru Peru Bhairavakona (2024) Sinhala Subtitles ආයුබෝවන් ඔයාල හැමෝටම! ඔන්න අද ...'
    },
    {
      title: 'Salaar: Part 1 – Ceasefire (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ'
,
      imdb: 'IMDB 6.6',
      year: '2023',
      link: 'https://sinhalasub.lk/movies/salaar-part-1-ceasefire-2023-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2023/12/bnVmFvn4f2FC2Ja00BApnz9Cmz9-150x150.jpg',
      description: 'Salaar  Sinhala Sub Salaar  Sinhala Subtitles Salaar (2023) Sinhala Sub Salaar (2023) Sinhala Subtitles සුභ දවසක් හැමෝටම!! ඔයාලා හැමෝටම නිදුක් නීරෝගීමත
්, සාමය, සතුට පිරෙන සුබම සුබ අලුත් ...'
    },
    {
      title: 'Japan (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 3.4',
      year: '2023',
      link: 'https://sinhalasub.lk/movies/japan-2023-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2023/11/5Z8hNvpenAJJrtTFONoytov7zW9-150x150.jpg',
      description: 'Japan Sinhala Sub Japan Sinhala Subtitles Japan (2023) Sinhala Sub Japan (2023) Sinhala Subtitles “කර්මය කියන්නේ මොකක්ද කියල ඔයා දන්නවද ? ඔයා ජීවිතයේ ගහ
ල මරපු මැස්සෝටික එක දවසක් ඩයිනෝසරයෙක්වෙලා ...'
    },
    {
      title: 'Ghost (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: '',
      year: '2023',
      link: 'https://sinhalasub.lk/movies/ghost-2023-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2023/11/zRLqjoVrlkUOJ2XTLah6SXsqB89-150x150.jpg',
      description: 'Ghost Sinhala Sub Ghost Sinhala Subtitles Ghost (2023) Sinhala Sub Ghost (2023) Sinhala Subtitles සුභ දවසක් හැමෝටම!! මේ අරං එන්නේ ඔක්තොම්බර් 19 දින ඉදන්
 Pan Indian චිත්‍රපටයක් විදියට ලොව පුරා ...'
    },
    {
      title: 'Red Sandal Wood (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 8',
      year: '2023',
      link: 'https://sinhalasub.lk/movies/red-sandal-wood-2023-sinhala-subtitles/',   
      image: 'https://sinhalasub.lk/wp-content/uploads/2023/10/e3mAfFdiKrdhQ3lHtzGRYBWDggj-150x150.jpg',
      description: 'Red Sandal Wood Sinhala Sub Red Sandal Wood Sinhala Subtitles Red 
Sandal Wood (2023) Sinhala Sub Red Sandal Wood (2023) Sinhala Subtitles සුභ දවසක් හැමෝ
ටම!! වනක්කම් හැමෝටම… ඔන්න අදත් අරන් ආව ...'
    },
    {
      title: 'Jailer (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      year: '2023',
      link: 'https://sinhalasub.lk/movies/jailer-2023-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2023/08/jailer-special-poster-2-150x150.jpg',
      description: 'Jailer Sinhala Sub Jailer Sinhala Subtitles Jailer (2023) Sinhala 
Sub Jailer (2023) Sinhala Subtitles සුභ දවසක් හැමෝටම!! ORIGINAL WEB-DL පිටපත යාවත්කාලීhala 
න (UPDATE) කර ඇත. ඒයි, මෙහේ මම තමයි රජා. මම ...'
    }
  ]
}
PS C:\Users\Win 10\Downloads\sinhalasub-movie> node s
node:internal/modules/cjs/loader:1228
  throw err;
  ^

    at Module._resolveFilename (node:internal/modules/cjs/loader:1225:15)
    at Module._load (node:internal/modules/cjs/loader:1051:27)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:174:12)
    at node:internal/main/run_main_module:28:49 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}

Node.js v20.17.0
PS C:\Users\Win 10\Downloads\sinhalasub-movie> node support
{
  status: true,
  creator: 'Dark Yasiya',
  result: [
    {
      title: 'Avengers: Infinity War (2018) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',   
      imdb: 'IMDB 8.4',
      year: '2018',
      link: 'https://sinhalasub.lk/movies/avengers-infinity-war-2018-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2022/08/7WsyChQLEftFiDOVTGkv3hFpyyt-150x150.jpg',
      description: 'Avengers: Infinity War Sinhala Subtitles Avengers: Infinity War (2018) Sinhala Subtitles'
    },
    {
      title: 'Avengers: Endgame (2019) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',        
      imdb: 'IMDB 8.4',
      year: '2019',
      link: 'https://sinhalasub.lk/movies/avengers-endgame-2019-sinhala-subtitles/',  
      image: 'https://sinhalasub.lk/wp-content/uploads/2020/11/or06FN3Dka5tukK1e9sl16pB3iy-150x150.jpg',
      description: 'Avengers: Endgame Sinhala Subtitles Avengers: Endgame (2019) Sinhala Subtitles'
    },
    {
      title: 'Avengers: Age of Ultron (2015) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',  
      imdb: 'IMDB 7.3',
      year: '2015',
      link: 'https://sinhalasub.lk/movies/avengers-age-of-ultron-2015-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2022/08/4ssDuvEDkSArWEdyBl2X5EHvYKU-150x150.jpg',
      description: 'Avengers: Age of Ultron Sinhala Subtitles Avengers: Age of Ultron 
(2015) Sinhala Subtitles'
    },
    {
      title: 'The Avengers (2012) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 8',
      year: '2012',
      link: 'https://sinhalasub.lk/movies/the-avengers-2012-sinhala-subtitles/',      
      image: 'https://sinhalasub.lk/wp-content/uploads/2022/08/RYMX2wcKCBAr24UyPD7xwmjaTn-150x150.jpg',
      description: 'The Avengers Sinhala Subtitles The Avengers (2012) Sinhala Subtitles'
    },
    {
      title: 'The Marvels (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 5.9',
      year: '2023',
      link: 'https://sinhalasub.lk/movies/the-marvels-2023-sinhala-subtitles/',       
      image: 'https://sinhalasub.lk/wp-content/uploads/2023/12/Ag3D9qXjhJ2FUkrlJ0Cv1pgxqYQ-150x150.jpg',
      description: 'The Marvels Sinhala Sub The Marvels Sinhala Subtitles The Marvels 
(2023) Sinhala Sub The Marvels (2023) Sinhala Subtitles සුභ දවසක් හැමෝටම!! මුලින්ම, සු
බ නත්තලක් වේවා හැමෝටම! හැමෝම හොඳින් ඇති ...'
    },
    {
      title: 'Brave Citizen (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 6.9',
      year: '2023',
      link: 'https://sinhalasub.lk/movies/brave-citizen-2023-sinhala-subtitles/',     
      image: 'https://sinhalasub.lk/wp-content/uploads/2023/11/6Ea5i6APeTfm4hHh6dg5Z733JVS-150x150.jpg',
      description: 'Brave Citizen Sinhala Sub Brave Citizen Sinhala Subtitles Brave Citizen (2023) Sinhala Sub Brave Citizen (2023) Sinhala Subtitles සුභ දවසක් හැමෝටම!! Inf
ormation – විස්තර Movie: Brave Citizen ...'
    },
    {
      title: 'The Creator (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 7.1',
      year: '2023',
      link: 'https://sinhalasub.lk/movies/the-creator-2023-sinhala-subtitles/',       
      image: 'https://sinhalasub.lk/wp-content/uploads/2023/11/vBZ0qvaRxqEhZwl6LWmruJqWE8Z-150x150.jpg',
      description: 'The Creator Sinhala Sub The Creator Sinhala Subtitles The Creator 
(2023) Sinhala Sub The Creator (2023) Sinhala Subtitles සුභ දවසක් හැමෝටම!! ඉතින් මේ අර
ගෙන එන්නේ නියම විද්‍යා ප්‍රබන්ධයක්.  ...'
    },
    {
      title: 'Tiger Zinda Hai (2017) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 5.9',
      year: '2017',
      link: 'https://sinhalasub.lk/movies/tiger-zinda-hai-2017-sinhala-subtitles/',   
      image: 'https://sinhalasub.lk/wp-content/uploads/2023/08/mdzNLFfCfuBoJz43l0SmMWWdu5t-150x150.jpg',
      description: 'Tiger Zinda Hai Sinhala Sub Tiger Zinda Hai Sinhala Subtitles Tiger Zinda Hai (2017) Sinhala Sub Tiger Zinda Hai (2017) Sinhala Subtitles සුභ දවසක් හැමෝ
ටම!! ත්‍රස්තවාදය කියන්නේ මේ ලෝකෙට නුහුරු ...'
    },
    {
      title: 'Shazam! (2019) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 7',
      year: '2019',
      link: 'https://sinhalasub.lk/movies/shazam-2019-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2019/03/YPDlGl2xQ1TQp6aXSEVSJ2XSNy-150x150.jpg',
      description: 'Shazam! Sinhala Sub Shazam! Sinhala Subtitles Shazam! (2019) Sinhala Sub Shazam! (2019) Sinhala Subtitles චිත්‍රපටය ගැන පොඩි විස්තරයක් කරන්නම්. Action, 
Adventure, Comedy, Fantasy, Sci-fi කාණ්ඩ ...'
    },
    {
      title: 'Hansel & Gretel: Witch Hunters (2013) Sinhala Subtitles | සිංහල උපසිරසි 
සමඟ',
      imdb: 'IMDB 6.1',
      year: '2013',
      link: 'https://sinhalasub.lk/movies/hansel-gretel-witch-hunters-2013-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2013/01/1f0Du4l7nIaN2E9OvoA0m4jAjYQ-150x150.jpg',
      description: 'Hansel & Gretel: Witch Hunters Sinhala Sub Hansel & Gretel: Witch 
Hunters Sinhala Subtitles Hansel & Gretel: Witch Hunters (2013) Sinhala Sub Hansel & Gretel: Witch Hunters (2013) ...'
    },
    {
      title: 'Guardians of the Galaxy Vol. 2 (2017) Sinhala Subtitles | සිංහල උපසිරසි 
සමඟ',
      imdb: 'IMDB 7.6',
      year: '2017',
      link: 'https://sinhalasub.lk/movies/guardians-of-the-galaxy-vol-2-2017-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2022/08/y4MBh0EjBlMuOzv9axM4qJlmhzz-150x150.jpg',
      description: 'Guardians of the Galaxy Vol. 2 Sinhala Subtitles Guardians of the 
Galaxy Vol. 2 (2017) Sinhala Subtitles Guardians of the Galaxy තමයි MCU එකේ එහෙමත් නැත
්නම් මාර්වල් සිනමා විශ්වයේ දෙවෙනි සමූහ වීර ...'
    },
    {
      title: 'Guardians of the Galaxy (2014) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',  
      imdb: 'IMDB 8',
      year: '2014',
      link: 'https://sinhalasub.lk/movies/guardians-of-the-galaxy-2014-sinhala-subtitles/',
      image: 'https://sinhalasub.lk/wp-content/uploads/2022/08/r7vmZjiyZw9rpJMQJdXpjgiCOk9-150x150.jpg',
      description: 'Guardians of the Galaxy Sinhala Subtitles Guardians of the Galaxy 
(2014) Sinhala Subtitles ටික කාලයකට පසුව මම අද ඔයාලාට ගෙනාවේ මේ වසරේ Marvel සමාගමේ සාර
්ථකම වාර්තා පිට වාර්තා තැබූ අති දැවැන්ත ...'
    },
    {
      title: 'Extraction (2020) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
      imdb: 'IMDB 6.7',
      year: '2020',
      link: 'https://sinhalasub.lk/movies/extraction-2020-sinhala-subtitles/',        
      image: 'https://sinhalasub.lk/wp-content/uploads/2022/02/nygOUcBKPHFTbxsYRFZVePqgPK6-150x150.jpg',
      description: 'Extraction (2020) Sinhala Subtitles මේ චිත්‍රපටිය Officially Relea
se කරේ අද දවසෙ. ඒ වගේම මේ චිත්‍රපටිය ගොඩක්ම වැදගත් වෙන්න හේතු කීපයක්ම තියෙනවා. ඒවා ඉස්
සරහට දැනගන්න පුළුවන් වෙයි. අපි මුලින්ම බලමු ...'
    }
  ]
}
```
## Get Movie Details and Download Links
```ts
var url = 'https://sinhalasub.lk/movies/rrr-2022-sinhala-subtitles/' // movie url
await SinhalaSub.movie(url)
```
```ts
//result
{
  "status": true,
  "code_creator": {
    "name": "Thisal Sanujaya",
    "github": "@sanuwaofficial"
  },
  "result": {
    "title": "RRR (2022) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
    "subtitle_author": "రౌద్రం రణం రుధిరం",
    "categories": ["Action","Drama","History","Telugu","War"],
    "release_date": "Mar. 24, 2022",
    "country": "India",
    "duration": "187 Min.",
    "director": { "name": "S.S. Rajamouli","link": "https://sinhalasub.lk/director/s-s-rajamouli/"},
    "cast": [
      {"name": "N.T. Rama Rao Jr.","link": "https://sinhalasub.lk/cast/n-t-rama-rao-jr/"},
      {"name": "Ram Charan","link": "https://sinhalasub.lk/cast/ram-charan/"},
      8 more...
    ],
    "desc": "",
    "images": [
      "https://sinhalasub.lk/wp-content/uploads/2022/03/u0XUBNQWlOvrh0Gd97ARGpIkL0-200x300.jpg",
      "https://images.hindustantimes.com/img/2022/04/01/1600x900/RRR-Movie-Review_1648825470847_1648825479894.jpg",
      "https://image.tmdb.org/t/p/original/mQBz0kkJw9gWW1accn1UIPVnvtL.jpg",
     8 more...
    ],
    "dl_links": [
      {
        "quality": "FHD 1080p",
        "size": "4.55 GB",
        "link": "https://001.sinhalaking.tk/0:/Movie/Telugu/RRR%20(2022)/www.SinhalaSub.net%20-%20RRR%20(2022)%20Telugu%20HQ%20HDRip%201080p.mp4"
      },
      {
        "quality": "HD 720p",
        "size": "2.03 GB",
        "link": "https://001.sinhalaking.tk/0:/Movie/Telugu/RRR%20(2022)/www.SinhalaSub.net%20-%20RRR%20(2022)%20Telugu%20HQ%20HDRip%20720p.mp4"
      },
    8 more...
    ]
  }
}

```
## Get Tvshow Details and episode Links
```ts
var url = 'https://sinhalasub.lk/tvshows/money-heist-2017-sinhala-subtitles/' // tvshow url
await SinhalaSub.tvshow(url)
```
```ts
//result

{
  status: true,
  code_creator: { name: 'Thisal Sanujaya', github: '@sanuwaofficial' },
  result: {
    title: 'Money Heist (2017 – 2021) Sinhala Subtitles | සිංහල උපසිරසි සමඟ',
    categories: [ 'Crime', 'Drama', 'Spanish'],
    info: {
      Original_title: "La Casa de Papel",
      TMDb_Rating: " 8.3 16,046 votes ",
      First_air_date: "May. 02, 2017",
      Last_air_date: "Dec. 03, 2021",
      Seasons: "3",
      Episodes: "41",
      Average_Duration: "70 minutes "
    },
    cast: [
           { name: 'Álvaro Morte', link: 'https://sinhalasub.lk/cast/alvaro-morte/' },
           { name: 'Úrsula Corberó', link: 'https://sinhalasub.lk/cast/ursula-corbero/' },
           8 more...
          ],
    links: [ 
            [
             { episode: '1 - 1',
               link: 'https://sinhalasub.lk/episodes/money-heist-s1e1/'},
             {
              episode: '1 - 2',
              link: 'https://sinhalasub.lk/episodes/money-heist-s1e2/' },
             11 more...
           ], 
           [
             { episode: '2 - 1',
               link: 'https://sinhalasub.lk/episodes/money-heist-s2e1/'},
             { episode: '2 - 2',
               link: 'https://sinhalasub.lk/episodes/money-heist-s2e2/' },
             7 more...
           ],
            3 more... 
          ]
  }
}
```
## Get Episode Details and download Links
```ts
var url = 'https://sinhalasub.lk/episodes/money-heist-s2e2/' // episode url
await SinhalaSub.episode(url)
```
```ts
//result
{
  "status": true,
  "code_creator": {
    "name": "Thisal Sanujaya",
    "github": "@sanuwaofficial"
  },
  "result": {
    "title": "Money Heist (2017 – 2021) Sinhala Subtitles | සිංහල උපසිරසි සමඟ: 2x2",
    "desc": "The Professor recruits Martin to put his brother’s plan into action and target the Bank of Spain. First step? Create total chaos.",
    "release_date": "Jul. 19, 2019",
    "images": [
      "https://image.tmdb.org/t/p/original/wg7nd7r0Iptr2W8kW37OSed1C4q.jpg",
      "https://image.tmdb.org/t/p/original/cwFuj35BzUNWSNSoAyOscwpAT2n.jpg"
    ],
    "dl_links": [
      {
        "quality": "HD 720p",
        "size": "470 MB",
        "link": "https://001.sinhalaking.tk/0:/TV/Money%20Heist%20(TV%20Series%202017%E2%80%932021)/S02/www.SinhalaSub.net%20-%20La.Casa.de.Papel.S02E02%20WEBRip%20720p.mp4"
      },
      {
        "quality": "HD 720p",
        "size": "470 MB",
        "link": "https://002.sinhalaking.tk/0:/TV/Money%20Heist%20(TV%20Series%202017%E2%80%932021)/S02/www.SinhalaSub.net%20-%20La.Casa.de.Papel.S02E02%20WEBRip%20720p.mp4"
      },
      {
        "quality": "HD 720p",
        "size": "470 MB",
        "link": "https://003.sinhalaking.tk/0:/TV/Money%20Heist%20(TV%20Series%202017%E2%80%932021)/S02/www.SinhalaSub.net%20-%20La.Casa.de.Papel.S02E02%20WEBRip%20720p.mp4"
      }
    ]
  }
}
```

## ✍️ Authors <a name = "authors"></a>

- [@sanuwaofficial](https://github.com/sanuwaofficial) - scraped project author

See also the list of [contributors](https://github.com/SL-CODE-LORDS/movie-dl/contributors) who participated in this project.
