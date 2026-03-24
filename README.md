# AWG Manager — списки маршрутизации

> Готовые наборы правил для [AWG Manager](https://t.me/awgmanager).
> Списки собираются **автоматически** из нескольких открытых источников,
> дедублируются и минимизируются — поддомены схлопываются при явном родителе,
> перекрывающиеся CIDR агрегируются.
> Цель проекта: избавить обычного пользователя от необходимости вручную добавлять
> десятки ссылок — достаточно подключить нужные файлы и получить стандартный набор
> соцсетей, мессенджеров, стриминга и AI-сервисов.
> Roblox вынесен в отдельный файл `roblox.lst` — подключайте его при необходимости.
> Bungie (Destiny/Marathon): домены и CIDR для обхода ошибки TAPIR в играх Bungie вынесены в `bungie_notapir.lst` — подключайте при необходимости.
> Sony PlayStation Network: домены и CIDR для PSN вынесены в `sonypsn.lst` — подключайте при необходимости.

© [amatol](https://t.me/amatol_blog) • [Telegram-канал](https://t.me/amatol_blog)

---

## Файлы

| Файл | Записей | Описание |
|------|--------:|----------|
| [domains.lst](domains.lst) | 2249 | Домены для маршрутизации |
| [cidr.lst](cidr.lst)       | 31 | IP-подсети (CIDR) для маршрутизации |
| [roblox.lst](roblox.lst)   | 130 | Домены и IP-подсети Roblox |
| [bungie_notapir.lst](bungie_notapir.lst) | 9 | Домены и IP-подсети Bungie (Destiny/Marathon) |
| [sonypsn.lst](sonypsn.lst) | 13 | Домены и IP-подсети Sony PlayStation Network |

---

## Источники `domains.lst`

Список доменов собирается из следующих источников:

- [ooni_domains.lst  *(из 1andrevich/Re-filter-lists)*](https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/ooni_domains.lst)
- [inside-kvas.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Russia/inside-kvas.lst)
- [community.lst  *(из 1andrevich/Re-filter-lists)*](https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/community.lst)
- [geoblock.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Categories/geoblock.lst)
- [telegram_domain  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/Telegram/telegram_domain)
- [google_play.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/google_play.lst)
- [google_ai.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/google_ai.lst)
- [kino.lst  *(из amatol/xkeen-configuration)*](https://raw.githubusercontent.com/amatol/xkeen-configuration/refs/heads/main/rules/kino.lst)
- [community.lst  *(из amatol/xkeen-configuration)*](https://raw.githubusercontent.com/amatol/xkeen-configuration/refs/heads/main/rules/community.lst)
- [discord.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/discord.lst)
- [hdrezka.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/hdrezka.lst)
- [meta.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/meta.lst)
- [tiktok.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/tiktok.lst)
- [twitter.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/twitter.lst)
- [youtube.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/youtube.lst)

---

## Источники `cidr.lst`

Список IP-подсетей собирается из следующих источников:

- [telegram.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Subnets/IPv4/telegram.lst)
- [telegram.bat  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/Telegram/telegram.bat)

---

## Источники `roblox.lst`

Список доменов и IP-подсетей Roblox:

- [roblox_domain  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/Roblox/roblox_domain)
- [Roblox_0.2.bat  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/Roblox/Roblox_0.2.bat)

---

## Источники `bungie_notapir.lst`

Список доменов и IP-подсетей для обхода ошибки TAPIR в играх Bungie (Destiny/Marathon):

- [bungie_notapir.lst  *(из amatol/xkeen-configuration)*](https://raw.githubusercontent.com/amatol/xkeen-configuration/refs/heads/main/rules/bungie_notapir.lst)
- [bungie_notapir_cidr.lst  *(из amatol/xkeen-configuration)*](https://raw.githubusercontent.com/amatol/xkeen-configuration/refs/heads/main/rules/bungie_notapir_cidr.lst)

---

## Источники `sonypsn.lst`

Список доменов и IP-подсетей Sony PlayStation Network:

- [sonypsn.bat  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/SonyPlaystationNetwork/sonypsn.bat)

---

## Сервисы

Отдельные файлы по сервисам из репозитория [RockBlack-VPN/ip-address](https://github.com/RockBlack-VPN/ip-address/tree/main/Global), обновляются автоматически:

| Сервис | Записей | Последнее обновление |
|--------|--------:|----------------------|
| [2407.pl](services/2407.pl/2407.pl.lst) | 2 | 2026-03-24 13:47:02 |
| [3dwarehouse.sketchup.com](services/3dwarehouse.sketchup.com/3dwarehouse.sketchup.com.lst) | 12 | 2026-03-24 13:47:02 |
| [adobe](services/adobe/adobe.lst) | 33 | 2026-03-24 13:47:02 |
| [airbnb](services/airbnb/airbnb.lst) | 11 | 2026-03-24 13:47:02 |
| [akamai](services/akamai/akamai.lst) | 34 | 2026-03-24 13:47:02 |
| [aliexpress](services/aliexpress/aliexpress.lst) | 7 | 2026-03-24 13:47:02 |
| [allegro.pl](services/allegro.pl/allegro.pl.lst) | 16 | 2026-03-24 13:47:02 |
| [animego.org](services/animego.org/animego.org.lst) | 6 | 2026-03-24 13:47:02 |
| [anthropic.com](services/anthropic.com/anthropic.com.lst) | 1 | 2026-03-24 13:47:02 |
| [anydesk](services/anydesk/anydesk.lst) | 9 | 2026-03-24 13:47:02 |
| [apple](services/apple/apple.lst) | 4 | 2026-03-24 13:47:02 |
| [autodesk](services/autodesk/autodesk.lst) | 133 | 2026-03-24 13:47:02 |
| [bato.to](services/bato.to/bato.to.lst) | 2 | 2026-03-24 13:47:02 |
| [battlefield5](services/battlefield5/battlefield5.lst) | 93 | 2026-03-24 13:47:02 |
| [bestchange](services/bestchange/bestchange.lst) | 3 | 2026-03-24 13:47:02 |
| [bigfangroup.org](services/bigfangroup.org/bigfangroup.org.lst) | 11 | 2026-03-24 13:47:02 |
| [binance](services/binance/binance.lst) | 13 | 2026-03-24 13:47:02 |
| [bing.com](services/bing.com/bing.com.lst) | 15 | 2026-03-24 13:47:02 |
| [bizagi](services/bizagi/bizagi.lst) | 8 | 2026-03-24 13:47:02 |
| [blizzard](services/blizzard/blizzard.lst) | 60 | 2026-03-24 13:47:02 |
| [boosty](services/boosty/boosty.lst) | 8 | 2026-03-24 13:47:02 |
| [canva](services/canva/canva.lst) | 12 | 2026-03-24 13:47:02 |
| [chatgpt(openai)](services/chatgpt(openai)/chatgpt(openai).lst) | 53 | 2026-03-24 13:47:02 |
| [clash_royale](services/clash_royale/clash_royale.lst) | 179 | 2026-03-24 13:47:02 |
| [cloudflare](services/cloudflare/cloudflare.lst) | 15 | 2026-03-24 13:47:02 |
| [coinglass.com](services/coinglass.com/coinglass.com.lst) | 13 | 2026-03-24 13:47:02 |
| [copilot](services/copilot/copilot.lst) | 69 | 2026-03-24 13:47:02 |
| [cs-2](services/cs-2/cs-2.lst) | 94 | 2026-03-24 13:47:02 |
| [dell.com](services/dell.com/dell.com.lst) | 24 | 2026-03-24 13:47:02 |
| [digash.live](services/digash.live/digash.live.lst) | 18 | 2026-03-24 13:47:02 |
| [discord](services/discord/discord.lst) | 27 | 2026-03-24 13:47:02 |
| [duolingo](services/duolingo/duolingo.lst) | 8 | 2026-03-24 13:47:02 |
| [ea](services/ea/ea.lst) | 19 | 2026-03-24 13:47:02 |
| [ebay](services/ebay/ebay.lst) | 32 | 2026-03-24 13:47:02 |
| [element](services/element/element.lst) | 7 | 2026-03-24 13:47:02 |
| [envato.com](services/envato.com/envato.com.lst) | 2 | 2026-03-24 13:47:02 |
| [epic_games](services/epic_games/epic_games.lst) | 6 | 2026-03-24 13:47:02 |
| [etsy.com](services/etsy.com/etsy.com.lst) | 94 | 2026-03-24 13:47:02 |
| [ewelink](services/ewelink/ewelink.lst) | 37 | 2026-03-24 13:47:02 |
| [facebook](services/facebook/facebook.lst) | 107 | 2026-03-24 13:47:02 |
| [facetime](services/facetime/facetime.lst) | 13 | 2026-03-24 13:47:02 |
| [fastly](services/fastly/fastly.lst) | 20 | 2026-03-24 13:47:02 |
| [gemini](services/gemini/gemini.lst) | 13 | 2026-03-24 13:47:02 |
| [ggsel.net](services/ggsel.net/ggsel.net.lst) | 25 | 2026-03-24 13:47:02 |
| [grok](services/grok/grok.lst) | 5 | 2026-03-24 13:47:02 |
| [hay_day](services/hay_day/hay_day.lst) | 55 | 2026-03-24 13:47:02 |
| [hdrezka](services/hdrezka/hdrezka.lst) | 6 | 2026-03-24 13:47:02 |
| [hetzner](services/hetzner/hetzner.lst) | 70 | 2026-03-24 13:47:02 |
| [home-connect](services/home-connect/home-connect.lst) | 9 | 2026-03-24 13:47:02 |
| [hornet](services/hornet/hornet.lst) | 14 | 2026-03-24 13:47:02 |
| [imdb.com](services/imdb.com/imdb.com.lst) | 1 | 2026-03-24 13:47:02 |
| [instagram](services/instagram/instagram.lst) | 98 | 2026-03-24 13:47:02 |
| [intel](services/intel/intel.lst) | 6 | 2026-03-24 13:47:02 |
| [jetbrains.com](services/jetbrains.com/jetbrains.com.lst) | 34 | 2026-03-24 13:47:02 |
| [lampa](services/lampa/lampa.lst) | 15 | 2026-03-24 13:47:02 |
| [lenovo](services/lenovo/lenovo.lst) | 5 | 2026-03-24 13:47:02 |
| [linkedin](services/linkedin/linkedin.lst) | 46 | 2026-03-24 13:47:02 |
| [lostfilm.tv](services/lostfilm.tv/lostfilm.tv.lst) | 4 | 2026-03-24 13:47:02 |
| [lucid](services/lucid/lucid.lst) | 13 | 2026-03-24 13:47:02 |
| [meduza.io](services/meduza.io/meduza.io.lst) | 13 | 2026-03-24 13:47:02 |
| [meta](services/meta/meta.lst) | 23 | 2026-03-24 13:47:02 |
| [microsoft](services/microsoft/microsoft.lst) | 359 | 2026-03-24 13:47:02 |
| [mouser.com](services/mouser.com/mouser.com.lst) | 12 | 2026-03-24 13:47:02 |
| [myanimelist](services/myanimelist/myanimelist.lst) | 38 | 2026-03-24 13:47:02 |
| [netflix](services/netflix/netflix.lst) | 87 | 2026-03-24 13:47:02 |
| [nintendo](services/nintendo/nintendo.lst) | 37 | 2026-03-24 13:47:02 |
| [nnmclub.to](services/nnmclub.to/nnmclub.to.lst) | 3 | 2026-03-24 13:47:02 |
| [notion](services/notion/notion.lst) | 5 | 2026-03-24 13:47:02 |
| [outlook](services/outlook/outlook.lst) | 325 | 2026-03-24 13:47:02 |
| [patreon](services/patreon/patreon.lst) | 15 | 2026-03-24 13:47:02 |
| [patreon.com](services/patreon.com/patreon.com.lst) | 1 | 2026-03-24 13:47:02 |
| [petlibro](services/petlibro/petlibro.lst) | 5 | 2026-03-24 13:47:02 |
| [pinterest](services/pinterest/pinterest.lst) | 9 | 2026-03-24 13:47:02 |
| [pixiv.net](services/pixiv.net/pixiv.net.lst) | 29 | 2026-03-24 13:47:02 |
| [pornhub](services/pornhub/pornhub.lst) | 23 | 2026-03-24 13:47:02 |
| [pubg](services/pubg/pubg.lst) | 28 | 2026-03-24 13:47:02 |
| [qoder](services/qoder/qoder.lst) | 19 | 2026-03-24 13:47:02 |
| [raid_shadow_legends](services/raid_shadow_legends/raid_shadow_legends.lst) | 45 | 2026-03-24 13:47:02 |
| [roblox](services/roblox/roblox.lst) | 11 | 2026-03-24 13:47:02 |
| [rutor.info](services/rutor.info/rutor.info.lst) | 4 | 2026-03-24 13:47:02 |
| [signal](services/signal/signal.lst) | 7 | 2026-03-24 13:47:02 |
| [snapchat](services/snapchat/snapchat.lst) | 13 | 2026-03-24 13:47:02 |
| [soundcloud](services/soundcloud/soundcloud.lst) | 29 | 2026-03-24 13:47:02 |
| [speedtest](services/speedtest/speedtest.lst) | 204 | 2026-03-24 13:47:02 |
| [spotify](services/spotify/spotify.lst) | 78 | 2026-03-24 13:47:02 |
| [squad_busters](services/squad_busters/squad_busters.lst) | 90 | 2026-03-24 13:47:02 |
| [strava.com](services/strava.com/strava.com.lst) | 120 | 2026-03-24 13:47:02 |
| [supercell](services/supercell/supercell.lst) | 266 | 2026-03-24 13:47:02 |
| [telegram](services/telegram/telegram.lst) | 40 | 2026-03-24 13:47:02 |
| [tevas](services/tevas/tevas.lst) | 16 | 2026-03-24 13:47:02 |
| [themoviedb](services/themoviedb/themoviedb.lst) | 2 | 2026-03-24 13:47:02 |
| [thetvdb](services/thetvdb/thetvdb.lst) | 140 | 2026-03-24 13:47:02 |
| [throne_and_liberty](services/throne_and_liberty/throne_and_liberty.lst) | 41 | 2026-03-24 13:47:02 |
| [tidal](services/tidal/tidal.lst) | 59 | 2026-03-24 13:47:02 |
| [tiktok](services/tiktok/tiktok.lst) | 123 | 2026-03-24 13:47:02 |
| [tor](services/tor/tor.lst) | 8 | 2026-03-24 13:47:02 |
| [trae.ai](services/trae.ai/trae.ai.lst) | 18 | 2026-03-24 13:47:02 |
| [twitch](services/twitch/twitch.lst) | 206 | 2026-03-24 13:47:02 |
| [ubiquiti](services/ubiquiti/ubiquiti.lst) | 7 | 2026-03-24 13:47:02 |
| [viber](services/viber/viber.lst) | 101 | 2026-03-24 13:47:02 |
| [videocdn.tv](services/videocdn.tv/videocdn.tv.lst) | 3 | 2026-03-24 13:47:02 |
| [wetransfer.com](services/wetransfer.com/wetransfer.com.lst) | 20 | 2026-03-24 13:47:02 |
| [whatsapp](services/whatsapp/whatsapp.lst) | 32 | 2026-03-24 13:47:02 |
| [windsurf](services/windsurf/windsurf.lst) | 39 | 2026-03-24 13:47:02 |
| [xbox](services/xbox/xbox.lst) | 393 | 2026-03-24 13:47:02 |
| [youtube](services/youtube/youtube.lst) | 11 | 2026-03-24 13:47:02 |
| [zoom](services/zoom/zoom.lst) | 67 | 2026-03-24 13:47:02 |
| [zscaler](services/zscaler/zscaler.lst) | 7 | 2026-03-24 13:47:02 |

---

*Последнее обновление: 2026-03-24 13:53:23*
