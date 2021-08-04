<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub İstatistik" />
 <h2 align="center">GitHub İstatistik</h2>
 <p align="center">Okuma dosyalarınızda dinamik olarak oluşturulmuş GitHub istatistiklerini alın!</p>
</p>
  <p align="center">
    <a href="https://github.com/Emre37destan/github-istatistik/actions">
      <img alt="Tests Passing" src="https://github.com/Emre37destan/github-istatistik/workflows/Test/badge.svg" />
    </a>
    <a href="https://codecov.io/gh/Emre37destan/github-istatistik">
      <img src="https://codecov.io/gh/Emre37destan/github-istatistik/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/Emre37destan/github-istatistik/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/Emre37destan/github-istatistik?color=0088ff" />
    </a>
    <a href="https://github.com/Emre37destan/github-istatistik/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/Emre37destan/github-istatistik?color=0088ff" />
    </a>
    <br />
    <br />
    <a href="https://a.paddle.com/v2/click/16413/119403?link=1227">
      <img src="https://img.shields.io/badge/Supported%20by-VSCode%20Power%20User%20%E2%86%92-gray.svg?colorA=655BE1&colorB=4F44D6&style=for-the-badge"/>
    </a>
    <a href="https://a.paddle.com/v2/click/16413/119403?link=2345">
      <img src="https://img.shields.io/badge/Supported%20by-Node%20Cli.com%20%E2%86%92-gray.svg?colorA=61c265&colorB=4CAF50&style=for-the-badge"/>
    </a>
  </p>

  <p align="center">
    <a href="#demo">Demoyu Görüntüle</a>
    ·
    <a href="https://github.com/Emre37destan/github-istatistik/issues/new/choose">Hata Bildir</a>
    ·
    <a href="https://github.com/Emre37destan/github-istatistik/issues/new/choose">Özellik İste</a>
  </p>
  <p align="center">
    <a href="/docs/readme_fr.md">Fransızca</a>
    ·
    <a href="/docs/readme_cn.md">Basitleştirilmiş Çince</a>
    ·
    <a href="/docs/readme_es.md">İspanyol</a>
    ·
    <a href="/docs/readme_de.md">Almanca</a>
    ·
    <a href="/docs/readme_ja.md">Japonca</a>
    ·
    <a href="/docs/readme_pt-BR.md">Brezilya Portekizcesi</a>
    ·
    <a href="/docs/readme_it.md">İtalyan</a>
    ·
    <a href="/docs/readme_kr.md">Koreli</a>
    .
    <a href="/docs/readme_nl.md">Hollanda</a>
    .
    <a href="/docs/readme_np.md">Nepalce</a>
    .
    <a href="/docs/readme_tr.md">Türkçe</a>
  </p>
</p>

<a href="https://indiafightscorona.giveindia.org">
<img src="https://d2wvdrxmr8p0wf.cloudfront.net/static/giveindia.svg" alt="Hindistan logosu ver" width="200" />
</a>

Bana bağış yaparak projeyi desteklemeyi düşünüyor musunuz? Lütfen YAPMAYIN!!

Bunun yerine, Hindistan'ın 2. ölümcül COVID dalgasıyla savaşmasına yardım edin,
Hindistan'da binlerce insan Oksijen ve COVID ile ilgili gerekli altyapı eksikliği nedeniyle ölüyor. 

Ziyaret [https://indiafightscorona.giveindia.org](https://indiafightscorona.giveindia.org) ve covid ile savaşmamıza ve bu krizin üstesinden gelmemize yardımcı olmak için küçük bir bağış yapın.
Küçük yardımın uzun bir yol kat ediyor. :heart:
</p>


# Özellikleri

- [GitHub İstatistik Kartı](#github-stats-card)
- [GitHub Ekstra Pinler](#github-extra-pins)
- [En İyi Diller Kartı](#top-languages-card)
- [Wakatime Hafta İstatistikleri](#wakatime-week-stats)
- [Temalar](#themes)
- [Özelleştirme](#customization)
  - [Ortak Seçenekler](#common-options)
  - [İstatistik Kartına Özel Seçenekler](#stats-card-exclusive-options)
  - [Repo Kartına Özel Seçenekler](#repo-card-exclusive-options)
  - [Dil Kartına Özel Seçenekler](#language-card-exclusive-options)
  - [Wakatime Kartına Özel Seçenek](#wakatime-card-exclusive-options)
- [Kendinizi Dağıtın](#deploy-on-your-own-vercel-instance)

# GitHub İstatistik Kartı

Bunu markdown içeriğinize kopyalayıp yapıştırın, hepsi bu. Basit!

`?username=` değerini GitHub'ınızın kullanıcı adıyla değiştirin.

```md
[![Kral Github istatistik](https://github-readme-stats.vercel.app/api?username=Emre37destan)](https://github.com/Emre37destan/github-istatistik)
```

_Not: Mevcut rütbeler S+ (ilk %1), S (ilk %25), A++ (ilk %45), A+ (ilk %60) ve B+'dır (herkes).
Değerler, taahhütler, katkılar, sorunlar, yıldızlar, çekme istekleri, takipçiler ve sahip olunan depolar kullanılarak [kümülatif dağıtım işlevi](https://en.wikipedia.org/wiki/Cumulative_distribution_function) kullanılarak hesaplanır.
Uygulama şurada incelenebilir: [src/calculateRank.js](./src/calculateRank.js)_

### Bireysel istatistikleri gizleme

Belirli istatistikleri gizlemek için `?hide=` sorgu parametresini virgülle ayrılmış değerlerle iletebilirsiniz.

> Seçenekler: `&hide=stars,commits,prs,issues,contribs`

```md
![Kral Github istatistik](https://github-readme-stats.vercel.app/api?username=Emre37destan&hide=contribs,prs)
```

### Toplam taahhüt sayısına özel katkı sayısı ekleme

Sorgu parametresini kullanarak tüm özel katkılarınızın sayısını toplam taahhüt sayısına ekleyebilirsiniz. `?count_private=true`.

_Not: Bu projeyi kendiniz dağıtıyorsanız, özel katkılar varsayılan olarak sayılacaktır, aksi takdirde özel katkı sayılarınızı paylaşmayı seçmeniz gerekir._

> Seçenekler: `&count_private=true`

```md
![Kral Github istatistik](https://github-readme-stats.vercel.app/api?username=Emre37destan&count_private=true)
```

### Simgeler gösteriliyor

Simgeleri etkinleştirmek için geçebilirsiniz `show_icons=true` sorgu parametresinde şöyle:

```md
![Kral Github istatistik](https://github-readme-stats.vercel.app/api?username=Emre37destan&show_icons=true)
```

### Temalar

Dahili temalarla, herhangi bir [manuel özelleştirme](#customization) yapmadan kartın görünümünü özelleştirebilirsiniz.

Use `?theme=THEME_NAME` parametre şöyle:-

```md
![Kral Github istatistik](https://github-readme-stats.vercel.app/api?username=Emre37destan&show_icons=true&theme=radical)
```

#### All yerleşik temalar :-

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub BeniOku İstatistikleri Temaları" width="600px"/>

için bir önizlemeye bakabilirsiniz [mevcut tüm temalar](./themes/README.md) ya da kontrol et [tema yapılandırma dosyası](./themes/index.js) & **İsterseniz yeni temalara da katkıda bulunabilirsiniz** :D

### Özelleştirme

URL parametreleri ile `Stats Card` veya `Repo Card` ınızın görünümünü istediğiniz gibi özelleştirebilirsiniz.

#### Ortak Seçenekler:

- `title_color` - Card's title color _(hex color)_
- `text_color` - Body text color _(hex color)_
- `icon_color` - Icons color if available _(hex color)_
- `border_color` - Card's border color _(hex color)_. (Does not apply when `hide_border` is enabled)
- `bg_color` - Card's background color _(hex color)_ **or** a gradient in the form of _angle,start,end_
- `hide_border` - Hides the card's border _(boolean)_
- `theme` - name of the theme, choose from [all available themes](./themes/README.md)
- `cache_seconds` - set the cache header manually _(min: 1800, max: 86400)_
- `locale` - set the language in the card _(e.g. cn, de, es, etc.)_
- `border_radius` - Corner rounding on the card_

##### Gradient in bg_color

You can provide multiple comma-separated values in bg_color option to render a gradient, the format of the gradient is :-

```
&bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10
```

> Note on cache: Repo cards have a default cache of 4 hours (14400 seconds) if the fork count & star count is less than 1k, otherwise, it's 2 hours (7200 seconds). Also, note that the cache is clamped to a minimum of 2 hours and a maximum of 24 hours.

#### Stats Card Exclusive Options:

- `hide` - Hides the specified items from stats _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `hide_rank` - _(boolean)_ hides the rank and automatically resizes the card width
- `show_icons` - _(boolean)_
- `include_all_commits` - Count total commits instead of just the current year commits _(boolean)_
- `count_private` - Count private commits _(boolean)_
- `line_height` - Sets the line-height between text _(number)_
- `custom_title` - Sets a custom title for the card
- `disable_animations` - Disables all animations in the card _(boolean)_

#### Repo Card Exclusive Options:

- `show_owner` - Show the repo's owner name _(boolean)_

#### Language Card Exclusive Options:

- `hide` - Hide the languages specified from the card _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `layout` - Switch between two available layouts `default` & `compact`
- `card_width` - Set the card's width manually _(number)_
- `langs_count` - Show more languages on the card, between 1-10, defaults to 5 _(number)_
- `exclude_repo` - Exclude specified repositories _(Comma-separated values)_
- `custom_title` - Sets a custom title for the card

> :warning: **Important:**
> Language names should be uri-escaped, as specified in [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding)
> (i.e: `c++` should become `c%2B%2B`, `jupyter notebook` should become `jupyter%20notebook`, etc.) You can use
> [urlencoder.org](https://www.urlencoder.org/) to help you do this automatically.

#### Wakatime Card Exclusive Options:

- `hide_title` - _(boolean)_
- `line_height` - Sets the line-height between text _(number)_
- `hide_progress` - Hides the progress bar and percentage _(boolean)_
- `custom_title` - Sets a custom title for the card
- `layout` - Switch between two available layouts `default` & `compact`
- `langs_count` - Limit number of languages on the card, defaults to all reported langauges
- `api_domain` - Set a custom API domain for the card, e.g. to use services like [Hakatime](https://github.com/mujx/hakatime) or [Wakapi](https://github.com/muety/wakapi)
- `range` – Request a range different from your WakaTime default, e.g. `last_7_days`. See [WakaTime API docs](https://wakatime.com/developers#stats) for list of available options.

---

# GitHub Extra Pins

GitHub extra pins allow you to pin more than 6 repositories in your profile using a GitHub readme profile.

Yay! You are no longer limited to 6 pinned repositories.

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/Emre37destan/github-istatistik)
```

### Demo

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/Emre37destan/github-istatistik)

Use [show_owner](#customization) variable to include the repo's owner username

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/Emre37destan/github-istatistik)

# Top Languages Card

The top languages card show a GitHub user's most frequently used top language.

_NOTE: Top Languages does not indicate my skill level or anything like that, it's a GitHub metric of which languages have the most code on GitHub. It's a new feature of github-readme-stats._

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/Emre37destan/github-istatistik)
```

### Exclude individual repositories

You can use `?exclude_repo=repo1,repo2` parameter to exclude individual repositories.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&exclude_repo=github-readme-stats,anuraghazra.github.io)](https://github.com/Emre37destan/github-istatistik)
```

### Hide individual languages

You can use `?hide=language1,language2` parameter to hide individual languages.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/Emre37destan/github-istatistik)
```

### Show more languages

You can use the `&langs_count=` option to increase or decrease the number of languages shown on the card. Valid values are integers between 1 and 10 (inclusive), and the default is 5.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&langs_count=8)](https://github.com/Emre37destan/github-istatistik)
```

### Compact Language Card Layout

You can use the `&layout=compact` option to change the card design.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/Emre37destan/github-istatistik)
```

### Demo

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/Emre37destan/github-istatistik)

- Compact layout

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/Emre37destan/github-istatistik)

# Wakatime Week Stats

Change the `?username=` value to your [Wakatime](https://wakatime.com) username.

```md
[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/Emre37destan/github-istatistik)
```

### Demo

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/Emre37destan/github-istatistik)

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/Emre37destan/github-istatistik)

- Compact layout

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/Emre37destan/github-istatistik)

---

### All Demos

- Default

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

- Hiding specific stats

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

- Showing icons

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

- Customize Border Color

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

- Include All Commits

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

- Themes

Choose from any of the [default themes](#themes)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

- Gradient

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

- Customizing stats card

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

- Setting card locale

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

- Customizing repo card

![Customized Card](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

- Top languages

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/Emre37destan/github-istatistik)

- Wakatime card

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/Emre37destan/github-istatistik)

---

### Quick Tip (Align The Repo Cards)

You usually won't be able to layout the images side by side. To do that you can use this approach:

```html
<a href="https://github.com/Emre37destan/github-istatistik">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## Deploy on your own Vercel instance

#### [Check Out Step By Step Video Tutorial By @codeSTACKr](https://youtu.be/n6d4KHSKqGk?t=107)

Since the GitHub API only allows 5k requests per hour, my `https://github-readme-stats.vercel.app/api` could possibly hit the rate limiter. If you host it on your own Vercel server, then you don't have to worry about anything. Click on the deploy button to get started!

NOTE: Since [#58](https://github.com/Emre37destan/github-istatistik/pull/58) we should be able to handle more than 5k requests and have no issues with downtime :D

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/Emre37destan/github-istatistik)

<details>
 <summary><b> Guide on setting up Vercel  🔨 </b></summary>

1. Go to [vercel.com](https://vercel.com/)
1. Click on `Log in`
   ![](https://files.catbox.moe/tct1wg.png)
1. Sign in with GitHub by pressing `Continue with GitHub`
   ![](https://files.catbox.moe/btd78j.jpeg)
1. Sign into GitHub and allow access to all repositories, if prompted
1. Fork this repo
1. Go back to your [Vercel dashboard](https://vercel.com/dashboard)
1. Select `Import Project`
   ![](https://files.catbox.moe/qckos0.png)
1. Select `Import Git Repository`
   ![](https://files.catbox.moe/pqub9q.png)
1. Select root and keep everything as is, just add your environment variable named PAT_1 (as shown), which will contain a personal access token (PAT), which you can easily create [here](https://github.com/settings/tokens/new) (leave everything as is, just name it something, it can be anything you want)
   ![](https://files.catbox.moe/0ez4g7.png)
1. Click deploy, and you're good to go. See your domains to use the API!

</details>

## :sparkling_heart: Projeyi destekleyin

Yapabileceğim hemen hemen her şeyi açık kaynaklı hale getiriyorum ve bu projeleri kullanarak yardıma ihtiyacı olan herkese yanıt vermeye çalışıyorum. Açıkça,
bu zaman alır. Bu hizmeti ücretsiz olarak kullanabilirsiniz.

Ancak, bu projeyi kullanıyorsanız ve bundan memnunsanız veya sadece bir şeyler yaratmaya devam etmem için beni teşvik etmek istiyorsanız, bunu yapmanın birkaç yolu vardır: -

- Benioku üzerinde github-istatistik kullandığınızda uygun kredi vermek, ona geri bağlantı vermek :D
- Projede rol alma ve paylaşma :roket:
- [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:

Teşekkürler! :heart:

---

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)


Katkılara açığız! <3

:heart: ve JavaScript ile yapılmıştır.
