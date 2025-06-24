# Cours sur les API

### IMDB 🌍 [Imdb](https://www.imdb.com/fr/) 
### OMDB 🌍 [omdb](http://www.omdbapi.com/) 
### TMDB 🌍 [tmdb](https://www.themoviedb.org/?language=fr) 



### Rechecher 🌍 film : Alien 🡺 http://www.omdbapi.com/?apikey=d7194885&t=alien
<details>
  <summary>Resultat</summary>

```javascript
{
  "Title": "Alien",
  "Year": "1979",
  "Rated": "R",
  "Released": "22 Jun 1979",
  "Runtime": "117 min",
  "Genre": "Horror, Sci-Fi",
  "Director": "Ridley Scott",
  "Writer": "Dan O'Bannon, Ronald Shusett",
  "Actors": "Sigourney Weaver, Tom Skerritt, John Hurt",
  "Plot": "After investigating a mysterious transmission of unknown origin, the crew of a commercial spacecraft encounters a deadly lifeform.",
  "Language": "English",
  "Country": "United Kingdom, United States",
  "Awards": "Won 1 Oscar. 19 wins & 22 nominations total",
  "Poster": "https://m.media-amazon.com/images/M/MV5BN2NhMDk2MmEtZDQzOC00MmY5LThhYzAtMDdjZGFjOGZjMjdjXkEyXkFqcGc@._V1_SX300.jpg",
  "Ratings": [
    {
      "Source": "Internet Movie Database",
      "Value": "8.5/10"
    },
    {
      "Source": "Rotten Tomatoes",
      "Value": "93%"
    },
    {
      "Source": "Metacritic",
      "Value": "89/100"
    }
  ],
  "Metascore": "89",
  "imdbRating": "8.5",
  "imdbVotes": "1,015,516",
  "imdbID": "tt0078748",
  "Type": "movie",
  "DVD": "N/A",
  "BoxOffice": "$84,206,106",
  "Production": "N/A",
  "Website": "N/A",
  "Response": "True"
}
```

</details>

### Rechecher 🌍 films : Alien 🡺 http://www.omdbapi.com/?apikey=d7194885&s=alien

<details>
  <summary>Resultat</summary>

```javascript
{
  "Search": [
    {
      "Title": "Alien",
      "Year": "1979",
      "imdbID": "tt0078748",
      "Type": "movie",
      "Poster": "https://m.media-amazon.com/images/M/MV5BN2NhMDk2MmEtZDQzOC00MmY5LThhYzAtMDdjZGFjOGZjMjdjXkEyXkFqcGc@._V1_SX300.jpg"
    },
    {
      "Title": "Alien³",
      "Year": "1992",
      "imdbID": "tt0103644",
      "Type": "movie",
      "Poster": "https://m.media-amazon.com/images/M/MV5BOGZiNmVlZGEtM2VmMi00ZTFkLTliMzEtZDNhYzUzNTcxMGY3XkEyXkFqcGc@._V1_SX300.jpg"
    },
    {
      "Title": "Alien: Covenant",
      "Year": "2017",
      "imdbID": "tt2316204",
      "Type": "movie",
      "Poster": "https://m.media-amazon.com/images/M/MV5BMjhiYWQ4MTAtOGY1Zi00ZjcyLTk1ZDYtODI3ODRhNjE4MzZhXkEyXkFqcGc@._V1_SX300.jpg"
    },
    {
      "Title": "Alien: Resurrection",
      "Year": "1997",
      "imdbID": "tt0118583",
      "Type": "movie",
      "Poster": "https://m.media-amazon.com/images/M/MV5BNDMyNmU5ZGQtNzhiZi00NjRjLTk3NGUtMmQ5YWU4ODlkNTBhXkEyXkFqcGc@._V1_SX300.jpg"
    },
    {
      "Title": "Alien: Romulus",
      "Year": "2024",
      "imdbID": "tt18412256",
      "Type": "movie",
      "Poster": "https://m.media-amazon.com/images/M/MV5BMDU0NjcwOGQtNjNjOS00NzQ3LWIwM2YtYWVmODZjMzQzN2ExXkEyXkFqcGc@._V1_SX300.jpg"
    },
    {
      "Title": "Alien vs. Predator",
      "Year": "2004",
      "imdbID": "tt0370263",
      "Type": "movie",
      "Poster": "https://m.media-amazon.com/images/M/MV5BMTU4MjIwMTcyMl5BMl5BanBnXkFtZTYwMTYwNDA3._V1_SX300.jpg"
    },
    {
      "Title": "Resident Alien",
      "Year": "2021–",
      "imdbID": "tt8690918",
      "Type": "series",
      "Poster": "https://m.media-amazon.com/images/M/MV5BYzczMDI5NzQtODdmYS00NTcwLTg1MTYtNmU5NWY1NDA5ZGRkXkEyXkFqcGc@._V1_SX300.jpg"
    },
    {
      "Title": "My Stepmother Is an Alien",
      "Year": "1988",
      "imdbID": "tt0095687",
      "Type": "movie",
      "Poster": "https://m.media-amazon.com/images/M/MV5BMmNmOWQ2NmUtOTcyZi00MGI5LWI5NDEtYzRkZWMxNWQ5Mjk5XkEyXkFqcGc@._V1_SX300.jpg"
    },
    {
      "Title": "Alien Nation",
      "Year": "1988",
      "imdbID": "tt0094631",
      "Type": "movie",
      "Poster": "https://m.media-amazon.com/images/M/MV5BY2M1ZmY1ODktM2I5NC00OGU0LThiNjAtM2E5NmU1NDE5MzU2XkEyXkFqcGc@._V1_SX300.jpg"
    },
    {
      "Title": "Ben 10: Alien Force",
      "Year": "2008–2010",
      "imdbID": "tt1192169",
      "Type": "series",
      "Poster": "https://m.media-amazon.com/images/M/MV5BOGQ5YWFjYjItODE5OC00ZDQxLTk5ZmYtNzY0YzM4NjIyMWFlXkEyXkFqcGc@._V1_SX300.jpg"
    }
  ],
  "totalResults": "1147",
  "Response": "True"
}
```

</details>

### Rechecher 🌍 films : Alien 🡺 https://api.themoviedb.org/3/search/movie?api_key=aa8b43b8cbce9d1689bef3d0c3087e4d&query=alien
<details>
  <summary>Resultat</summary>

```javascript
{
  "page": 1,
  "results": [
    {
      "adult": false,
      "backdrop_path": "/hdHIjZxq3SWFqpAz4NFhdbud0iz.jpg",
      "genre_ids": [
        27,
        878
      ],
      "id": 348,
      "original_language": "en",
      "original_title": "Alien",
      "overview": "During its return to the earth, commercial spaceship Nostromo intercepts a distress signal from a distant planet. When a three-member team of the crew discovers a chamber containing thousands of eggs on the planet, a creature inside one of the eggs attacks an explorer. The entire crew is unaware of the impending nightmare set to descend upon them when the alien parasite planted inside its unfortunate host is birthed.",
      "popularity": 19.2618,
      "poster_path": "/vfrQk5IPloGg1v9Rzbh2Eg3VGyM.jpg",
      "release_date": "1979-05-25",
      "title": "Alien",
      "video": false,
      "vote_average": 8.164,
      "vote_count": 15359
    },
    {
      "adult": false,
      "backdrop_path": null,
      "genre_ids": [
        878
      ],
      "id": 1187412,
      "original_language": "ta",
      "original_title": "Alien",
      "overview": "how aliens might be in a country like India",
      "popularity": 0.4045,
      "poster_path": null,
      "release_date": "",
      "title": "Alien",
      "video": false,
      "vote_average": 0,
      "vote_count": 0
    },
    {
      "adult": false,
      "backdrop_path": null,
      "genre_ids": [
        878
      ],
      "id": 817189,
      "original_language": "en",
      "original_title": "Alien",
      "overview": "",
      "popularity": 0.7263,
      "poster_path": "/sI5eeqdoiZ62zv11WSMEev6Ynim.jpg",
      "release_date": "2017-05-16",
      "title": "Alien",
      "video": false,
      "vote_average": 6.7,
      "vote_count": 10
    },
    {
      "adult": false,
      "backdrop_path": null,
      "genre_ids": [],
      "id": 881423,
      "original_language": "en",
      "original_title": "Alien",
      "overview": "And from silence and darkness awakes - an all-moving, all-turning being. White, yellow and golden spindles in vigorous synchronised rotation. Twirling in shiny pirouettes in an old workshop full of nooks and crannies, they spin the big thread, sacrificing themselves. In the midst of the heat and noise of the historic machine souls a hunched old man is working, sometimes a cog, sometimes the conductor.",
      "popularity": 0.1745,
      "poster_path": null,
      "release_date": "2017-10-06",
      "title": "Alien",
      "video": false,
      "vote_average": 5.3,
      "vote_count": 3
    },
    {
      "adult": false,
      "backdrop_path": null,
      "genre_ids": [],
      "id": 538467,
      "original_language": "es",
      "original_title": "Alien",
      "overview": "Do we perceive things as they truly are? Can the assumption that we do leads to dangerous positions, as racism or xenophobia? This documentary reflects on issues like migration, border walls, and the restriction of human mobility from the perspective of people whose field of study could hardly be more detached from these issues: astronomers.",
      "popularity": 0.1523,
      "poster_path": "/kCnz4ZS2OHJ36908E3H8BqgQCzI.jpg",
      "release_date": "2017-08-01",
      "title": "Alien",
      "video": false,
      "vote_average": 7.2,
      "vote_count": 4
    },
    {
      "adult": false,
      "backdrop_path": null,
      "genre_ids": [
        18,
        878
      ],
      "id": 1385032,
      "original_language": "tl",
      "original_title": "Alien",
      "overview": "In a dystopian Philippines where people breathe through a bio-helmet, an oxygen concentrator that takes air from plants, a young man embarks on a journey for the promise of a better life.",
      "popularity": 0.3518,
      "poster_path": "/vRw0VBSnoef9nOMDTFEDBXGPKIq.jpg",
      "release_date": "2023-12-06",
      "title": "Alien",
      "video": false,
      "vote_average": 0,
      "vote_count": 0
    },
    {
      "adult": false,
      "backdrop_path": "/sumajFyOoIKubI15POZ0p8Ekpzu.jpg",
      "genre_ids": [
        28,
        878,
        53
      ],
      "id": 593035,
      "original_language": "en",
      "original_title": "Alien Warfare",
      "overview": "A team of Navy Seals investigates a mysterious science outpost only to have to combat a squad of powerful alien soldiers.",
      "popularity": 1.0907,
      "poster_path": "/rJOj0T5DyChfECevDg0xpEGznsl.jpg",
      "release_date": "2019-04-05",
      "title": "Alien Warfare",
      "video": false,
      "vote_average": 4.1,
      "vote_count": 150
    },
    {
      "adult": false,
      "backdrop_path": "/2qluV8y79LnBBHaMpwewCjQ1Htk.jpg",
      "genre_ids": [
        27,
        878,
        53
      ],
      "id": 126889,
      "original_language": "en",
      "original_title": "Alien: Covenant",
      "overview": "The crew of the colony ship Covenant, bound for a remote planet on the far side of the galaxy, discovers what they think is an uncharted paradise but is actually a dark, dangerous world.",
      "popularity": 12.6278,
      "poster_path": "/zecMELPbU5YMQpC81Z8ImaaXuf9.jpg",
      "release_date": "2017-05-09",
      "title": "Alien: Covenant",
      "video": false,
      "vote_average": 6.158,
      "vote_count": 8928
    },
    {
      "adult": false,
      "backdrop_path": null,
      "genre_ids": [
        16,
        27,
        878
      ],
      "id": 272108,
      "original_language": "ja",
      "original_title": "淫獣エイリアン",
      "overview": "The all female crew of the transport ship Muse is on a mission in deep space. They pick up an SOS signal and discover a derelict space cruiser where all the women have died mysteriously. They take the only survivor, a young woman named Flair, and detonate the ghost ship. However, the danger is just beginning. With Flair on the Muse, the romances between the women begin to take a new turn. One by one, the crewmembers are attacked by a mysterious alien presence, desperate to find a way to reproduce with human women!",
      "popularity": 2.1651,
      "poster_path": "/dbxpznxnTpR5MCl0bdDRor7j4qK.jpg",
      "release_date": "1997-01-24",
      "title": "Alien from the Darkness",
      "video": false,
      "vote_average": 6.154,
      "vote_count": 13
    },
    {
      "adult": false,
      "backdrop_path": "/p3ZII4uLzv2y2FV4XUqBYNfmLN6.jpg",
      "genre_ids": [
        16,
        10751
      ],
      "id": 432383,
      "original_language": "de",
      "original_title": "Luis und die Aliens",
      "overview": "The story 11-year-old Luis who makes friends with three loveable little aliens, who crash their UFO into his house. In return for Luis' help in finding the home-shopping channel stuff they came for, they save Luis from boarding school - and an exciting adventure follows.",
      "popularity": 1.1628,
      "poster_path": "/5oq7s5ru4hjp83mi4fWSJ0L7yUA.jpg",
      "release_date": "2018-05-09",
      "title": "Luis and the Aliens",
      "video": false,
      "vote_average": 6.5,
      "vote_count": 179
    },
    {
      "adult": false,
      "backdrop_path": "/akcFhNdibYAsGUOfUhb5y1rFTet.jpg",
      "genre_ids": [
        16,
        10751,
        12,
        878
      ],
      "id": 15512,
      "original_language": "en",
      "original_title": "Monsters vs Aliens",
      "overview": "When Susan Murphy is unwittingly clobbered by a meteor full of outer space gunk on her wedding day, she mysteriously grows to 49-feet-11-inches. The military jumps into action and captures Susan, secreting her away to a covert government compound. She is renamed Ginormica and placed in confinement with a ragtag group of Monsters...",
      "popularity": 7.8228,
      "poster_path": "/hpHarddVj34j53T7NsoUGdKj4mP.jpg",
      "release_date": "2009-03-19",
      "title": "Monsters vs Aliens",
      "video": false,
      "vote_average": 6.22,
      "vote_count": 4732
    },
    {
      "adult": false,
      "backdrop_path": "/t5NBgE5RBCKBP1jy7tGSNKUGKE3.jpg",
      "genre_ids": [
        53
      ],
      "id": 792341,
      "original_language": "mo",
      "original_title": "Fără suflet",
      "overview": "Russia, Current day. Gynecologist Angela Kuhlmann finds herself in a very uncomfortable situation: she has to leave Moscow and start working within a province. The city is experiencing difficult times: because of the newly built highway to Moscow, it sinks into fornication and sin. Soon after Ms. Kuhlmann performs an illegal abortion - the patient claims to carry the Antichrist within her womb and takes the embryo home with her. From that moment on, a series of strange incidents begin to occur within her life.",
      "popularity": 0.2836,
      "poster_path": "/bBQFIoNasf94JsKkTHvdaXoD82u.jpg",
      "release_date": "2025-01-30",
      "title": "The Alienated",
      "video": false,
      "vote_average": 0,
      "vote_count": 0
    },
    {
      "adult": false,
      "backdrop_path": "/fA26YhmFtH5ehSiBB2EirCJCWhO.jpg",
      "genre_ids": [
        35,
        10402,
        10749
      ],
      "id": 413562,
      "original_language": "es",
      "original_title": "El alien y yo",
      "overview": "A punk band decides to hire a keyboard player in order to change their sound, despite the fact that this talented musician has Down Syndrome.",
      "popularity": 0.276,
      "poster_path": "/jNLetImXPLSb2Qr4tX7x2bkDPrM.jpg",
      "release_date": "2016-09-30",
      "title": "The Alien and Me",
      "video": false,
      "vote_average": 5.2,
      "vote_count": 15
    },
    {
      "adult": false,
      "backdrop_path": "/7ZP8HtgOIDaBs12krXgUIygqEsy.jpg",
      "genre_ids": [
        878,
        28,
        14,
        12
      ],
      "id": 601796,
      "original_language": "ko",
      "original_title": "외계+인 1부",
      "overview": "Gurus in the late Goryeo dynasty try to obtain a fabled, holy sword, and humans in 2022 hunt down an alien prisoner that is locked in a human's body. The two parties cross paths when a time-traveling portal opens up.",
      "popularity": 9.3595,
      "poster_path": "/8QVDXDiOGHRcAD4oM6MXjE0osSj.jpg",
      "release_date": "2022-07-20",
      "title": "Alienoid",
      "video": false,
      "vote_average": 6.831,
      "vote_count": 475
    },
    {
      "adult": false,
      "backdrop_path": "/tGoVI5VJpwuDupaqeN3guWuoAke.jpg",
      "genre_ids": [
        35
      ],
      "id": 485346,
      "original_language": "it",
      "original_title": "Tito e gli Alieni",
      "overview": "Professor Biondi is a depressed scientist. After his wife's death, he lives isolated from the world in the Nevada desert, near Area 51. He supposedly works on a top-secret project for the US government, but in actuality, he spends his days on the couch, listening to the sound of the Universe. His only contact with the outside world is Stella, who organizes alien-themed weddings for tourists on the prowl for extra-terrestrials. One day the Professor receives a message from Naples: his dying brother is entrusting him with his two children, so that they may live with him in America.",
      "popularity": 0.676,
      "poster_path": "/wjqGlVG8tvtuZkZvvHNprdgCB1a.jpg",
      "release_date": "2018-07-07",
      "title": "Little Tito and the Aliens",
      "video": false,
      "vote_average": 5.441,
      "vote_count": 59
    },
    {
      "adult": false,
      "backdrop_path": "/fHiulYABlqyxR8MBMCSNd8dzod9.jpg",
      "genre_ids": [
        35,
        14
      ],
      "id": 669122,
      "original_language": "zh",
      "original_title": "外星人事件",
      "overview": "Official Zhao Zhifu is appointed by the leadership to go to Longtan Village to work on poverty alleviation and development. He finds that the only people left in the village are the old, the sick and the disabled, who live on white work. Zhao Zhifu's plan to help the poor is soon challenged and suppressed by the local snake Ma Sanbao.",
      "popularity": 0.2881,
      "poster_path": "/wzurXoLDPrHVHFxSgchfy4v0TPR.jpg",
      "release_date": "2020-01-27",
      "title": "Alien Invasion",
      "video": false,
      "vote_average": 0,
      "vote_count": 0
    },
    {
      "adult": false,
      "backdrop_path": null,
      "genre_ids": [
        878,
        27,
        18,
        35
      ],
      "id": 451096,
      "original_language": "ja",
      "original_title": "幽霊 vs 宇宙人 01",
      "overview": "Horror, gag, entertainment by Keisuke Toyoshima of \"Heller master Shimizu Takashi ×\" \"Kaidan New Ear Bag Nobuhiro\" !! \"Kaidanui watching me ...\" and \"My alien\" are included.",
      "popularity": 0.1305,
      "poster_path": "/6nJb4LD47jGWcK2Pbmvu7fP0YzD.jpg",
      "release_date": "2002-04-07",
      "title": "Ghosts vs. Aliens",
      "video": false,
      "vote_average": 4,
      "vote_count": 1
    },
    {
      "adult": false,
      "backdrop_path": "/vmfOEwQMGllDQE7S9vzufOKwOdq.jpg",
      "genre_ids": [
        27
      ],
      "id": 527014,
      "original_language": "en",
      "original_title": "Alien Psychosis",
      "overview": "Ryan O'Neil, a War Veteran suffering from PTSD after being wounded in combat, returns home to his pregnant wife, Stephanie. Her brother Tony, a corrupt cop, has been helping her out while her husband has been serving the country. Ryan and Tony have never been fond of each other, and things get heated as Tony attempts to meddle with their marriage. But when Ryan starts to have flashes and visions of killers, extraterrestrials, and other strange beings in his house at night, he's not sure whether it is real or if it is just in his mind. Stephanie, already on edge with Ryan, is deeply concerned about her husband's behavior. As the days go by, Ryan will soon find out what sinister presence has been haunting him in his nightmares.",
      "popularity": 0.2393,
      "poster_path": "/zBipFulQKHQTtwv18RKviUap72Z.jpg",
      "release_date": "2018-02-24",
      "title": "Alien Psychosis",
      "video": false,
      "vote_average": 5,
      "vote_count": 8
    },
    {
      "adult": false,
      "backdrop_path": "/iJaSpQNZ8GsqVDWfbCXmyZQXZ5l.jpg",
      "genre_ids": [
        27,
        878
      ],
      "id": 945961,
      "original_language": "en",
      "original_title": "Alien: Romulus",
      "overview": "While scavenging the deep ends of a derelict space station, a group of young space colonizers come face to face with the most terrifying life form in the universe.",
      "popularity": 32.5519,
      "poster_path": "/b33nnKl1GSFbao4l3fZDDqsMx0F.jpg",
      "release_date": "2024-08-13",
      "title": "Alien: Romulus",
      "video": false,
      "vote_average": 7.197,
      "vote_count": 3743
    },
    {
      "adult": false,
      "backdrop_path": "/aIWxdB9N1a1ELdtzYkahpkSVceY.jpg",
      "genre_ids": [
        27,
        878
      ],
      "id": 27909,
      "original_language": "it",
      "original_title": "Alien degli abissi",
      "overview": "Two members of Greenpeace discover that a local factory sheds radioactive waste into an active volcano, which has created a terrifying creature that wreaks havoc in the area.",
      "popularity": 0.4069,
      "poster_path": "/xqYOY76qUL0XVcUy12GlTreqk3F.jpg",
      "release_date": "1989-10-15",
      "title": "Alien from the Deep",
      "video": false,
      "vote_average": 3.808,
      "vote_count": 26
    }
  ],
  "total_pages": 61,
  "total_results": 1202
}
```

</details>

### CodePen 🌍 mario-35 🡺 https://codepen.io/mario-35/pen/qEdQyQo


 
