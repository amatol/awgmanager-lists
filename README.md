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

## Сервисы (RockBlack-VPN/ip-address)

Отдельные файлы по сервисам из репозитория [RockBlack-VPN/ip-address](https://github.com/RockBlack-VPN/ip-address/tree/main/Global), обновляются автоматически:

| Сервис | Файл | Записей | Последнее обновление |
|--------|------|--------:|----------------------|
| 2407.pl | [services/2407.pl/2407.pl.lst](services/2407.pl/2407.pl.lst) | 2 | 2026-03-24 13:47:02 |
| 3dwarehouse.sketchup.com | [services/3dwarehouse.sketchup.com/3dwarehouse.sketchup.com.lst](services/3dwarehouse.sketchup.com/3dwarehouse.sketchup.com.lst) | 12 | 2026-03-24 13:47:02 |
| adobe | [services/adobe/adobe.lst](services/adobe/adobe.lst) | 33 | 2026-03-24 13:47:02 |
| airbnb | [services/airbnb/airbnb.lst](services/airbnb/airbnb.lst) | 11 | 2026-03-24 13:47:02 |
| akamai | [services/akamai/akamai.lst](services/akamai/akamai.lst) | 34 | 2026-03-24 13:47:02 |
| aliexpress | [services/aliexpress/aliexpress.lst](services/aliexpress/aliexpress.lst) | 7 | 2026-03-24 13:47:02 |
| allegro.pl | [services/allegro.pl/allegro.pl.lst](services/allegro.pl/allegro.pl.lst) | 16 | 2026-03-24 13:47:02 |
| animego.org | [services/animego.org/animego.org.lst](services/animego.org/animego.org.lst) | 6 | 2026-03-24 13:47:02 |
| anthropic.com | [services/anthropic.com/anthropic.com.lst](services/anthropic.com/anthropic.com.lst) | 1 | 2026-03-24 13:47:02 |
| anydesk | [services/anydesk/anydesk.lst](services/anydesk/anydesk.lst) | 9 | 2026-03-24 13:47:02 |
| apple | [services/apple/apple.lst](services/apple/apple.lst) | 4 | 2026-03-24 13:47:02 |
| autodesk | [services/autodesk/autodesk.lst](services/autodesk/autodesk.lst) | 133 | 2026-03-24 13:47:02 |
| bato.to | [services/bato.to/bato.to.lst](services/bato.to/bato.to.lst) | 2 | 2026-03-24 13:47:02 |
| battlefield5 | [services/battlefield5/battlefield5.lst](services/battlefield5/battlefield5.lst) | 93 | 2026-03-24 13:47:02 |
| bestchange | [services/bestchange/bestchange.lst](services/bestchange/bestchange.lst) | 3 | 2026-03-24 13:47:02 |
| bigfangroup.org | [services/bigfangroup.org/bigfangroup.org.lst](services/bigfangroup.org/bigfangroup.org.lst) | 11 | 2026-03-24 13:47:02 |
| binance | [services/binance/binance.lst](services/binance/binance.lst) | 13 | 2026-03-24 13:47:02 |
| bing.com | [services/bing.com/bing.com.lst](services/bing.com/bing.com.lst) | 15 | 2026-03-24 13:47:02 |
| bizagi | [services/bizagi/bizagi.lst](services/bizagi/bizagi.lst) | 8 | 2026-03-24 13:47:02 |
| blizzard | [services/blizzard/blizzard.lst](services/blizzard/blizzard.lst) | 60 | 2026-03-24 13:47:02 |
| boosty | [services/boosty/boosty.lst](services/boosty/boosty.lst) | 8 | 2026-03-24 13:47:02 |
| canva | [services/canva/canva.lst](services/canva/canva.lst) | 12 | 2026-03-24 13:47:02 |
| chatgpt(openai) | [services/chatgpt(openai)/chatgpt(openai).lst](services/chatgpt(openai)/chatgpt(openai).lst) | 53 | 2026-03-24 13:47:02 |
| clash royale | [services/clash royale/clash royale.lst](services/clash royale/clash royale.lst) | 179 | 2026-03-24 13:47:02 |
| cloudflare | [services/cloudflare/cloudflare.lst](services/cloudflare/cloudflare.lst) | 15 | 2026-03-24 13:47:02 |
| coinglass.com | [services/coinglass.com/coinglass.com.lst](services/coinglass.com/coinglass.com.lst) | 13 | 2026-03-24 13:47:02 |
| copilot | [services/copilot/copilot.lst](services/copilot/copilot.lst) | 69 | 2026-03-24 13:47:02 |
| cs-2 | [services/cs-2/cs-2.lst](services/cs-2/cs-2.lst) | 94 | 2026-03-24 13:47:02 |
| dell.com | [services/dell.com/dell.com.lst](services/dell.com/dell.com.lst) | 24 | 2026-03-24 13:47:02 |
| digash.live | [services/digash.live/digash.live.lst](services/digash.live/digash.live.lst) | 18 | 2026-03-24 13:47:02 |
| discord | [services/discord/discord.lst](services/discord/discord.lst) | 27 | 2026-03-24 13:47:02 |
| duolingo | [services/duolingo/duolingo.lst](services/duolingo/duolingo.lst) | 8 | 2026-03-24 13:47:02 |
| ea | [services/ea/ea.lst](services/ea/ea.lst) | 19 | 2026-03-24 13:47:02 |
| ebay | [services/ebay/ebay.lst](services/ebay/ebay.lst) | 32 | 2026-03-24 13:47:02 |
| element | [services/element/element.lst](services/element/element.lst) | 7 | 2026-03-24 13:47:02 |
| envato.com | [services/envato.com/envato.com.lst](services/envato.com/envato.com.lst) | 2 | 2026-03-24 13:47:02 |
| epic games | [services/epic games/epic games.lst](services/epic games/epic games.lst) | 6 | 2026-03-24 13:47:02 |
| etsy.com | [services/etsy.com/etsy.com.lst](services/etsy.com/etsy.com.lst) | 94 | 2026-03-24 13:47:02 |
| ewelink | [services/ewelink/ewelink.lst](services/ewelink/ewelink.lst) | 37 | 2026-03-24 13:47:02 |
| facebook | [services/facebook/facebook.lst](services/facebook/facebook.lst) | 107 | 2026-03-24 13:47:02 |
| facetime | [services/facetime/facetime.lst](services/facetime/facetime.lst) | 13 | 2026-03-24 13:47:02 |
| fastly | [services/fastly/fastly.lst](services/fastly/fastly.lst) | 20 | 2026-03-24 13:47:02 |
| gemini | [services/gemini/gemini.lst](services/gemini/gemini.lst) | 13 | 2026-03-24 13:47:02 |
| ggsel.net | [services/ggsel.net/ggsel.net.lst](services/ggsel.net/ggsel.net.lst) | 25 | 2026-03-24 13:47:02 |
| grok | [services/grok/grok.lst](services/grok/grok.lst) | 5 | 2026-03-24 13:47:02 |
| hay day | [services/hay day/hay day.lst](services/hay day/hay day.lst) | 55 | 2026-03-24 13:47:02 |
| hdrezka | [services/hdrezka/hdrezka.lst](services/hdrezka/hdrezka.lst) | 6 | 2026-03-24 13:47:02 |
| hetzner | [services/hetzner/hetzner.lst](services/hetzner/hetzner.lst) | 70 | 2026-03-24 13:47:02 |
| home-connect | [services/home-connect/home-connect.lst](services/home-connect/home-connect.lst) | 9 | 2026-03-24 13:47:02 |
| hornet | [services/hornet/hornet.lst](services/hornet/hornet.lst) | 14 | 2026-03-24 13:47:02 |
| imdb.com | [services/imdb.com/imdb.com.lst](services/imdb.com/imdb.com.lst) | 1 | 2026-03-24 13:47:02 |
| instagram | [services/instagram/instagram.lst](services/instagram/instagram.lst) | 98 | 2026-03-24 13:47:02 |
| intel | [services/intel/intel.lst](services/intel/intel.lst) | 6 | 2026-03-24 13:47:02 |
| jetbrains.com | [services/jetbrains.com/jetbrains.com.lst](services/jetbrains.com/jetbrains.com.lst) | 34 | 2026-03-24 13:47:02 |
| lampa | [services/lampa/lampa.lst](services/lampa/lampa.lst) | 15 | 2026-03-24 13:47:02 |
| lenovo | [services/lenovo/lenovo.lst](services/lenovo/lenovo.lst) | 5 | 2026-03-24 13:47:02 |
| linkedin | [services/linkedin/linkedin.lst](services/linkedin/linkedin.lst) | 46 | 2026-03-24 13:47:02 |
| lostfilm.tv | [services/lostfilm.tv/lostfilm.tv.lst](services/lostfilm.tv/lostfilm.tv.lst) | 4 | 2026-03-24 13:47:02 |
| lucid | [services/lucid/lucid.lst](services/lucid/lucid.lst) | 13 | 2026-03-24 13:47:02 |
| meduza.io | [services/meduza.io/meduza.io.lst](services/meduza.io/meduza.io.lst) | 13 | 2026-03-24 13:47:02 |
| meta | [services/meta/meta.lst](services/meta/meta.lst) | 23 | 2026-03-24 13:47:02 |
| microsoft | [services/microsoft/microsoft.lst](services/microsoft/microsoft.lst) | 359 | 2026-03-24 13:47:02 |
| mouser.com | [services/mouser.com/mouser.com.lst](services/mouser.com/mouser.com.lst) | 12 | 2026-03-24 13:47:02 |
| myanimelist | [services/myanimelist/myanimelist.lst](services/myanimelist/myanimelist.lst) | 38 | 2026-03-24 13:47:02 |
| netflix | [services/netflix/netflix.lst](services/netflix/netflix.lst) | 87 | 2026-03-24 13:47:02 |
| nintendo | [services/nintendo/nintendo.lst](services/nintendo/nintendo.lst) | 37 | 2026-03-24 13:47:02 |
| nnmclub.to | [services/nnmclub.to/nnmclub.to.lst](services/nnmclub.to/nnmclub.to.lst) | 3 | 2026-03-24 13:47:02 |
| notion | [services/notion/notion.lst](services/notion/notion.lst) | 5 | 2026-03-24 13:47:02 |
| outlook | [services/outlook/outlook.lst](services/outlook/outlook.lst) | 325 | 2026-03-24 13:47:02 |
| patreon | [services/patreon/patreon.lst](services/patreon/patreon.lst) | 15 | 2026-03-24 13:47:02 |
| patreon.com | [services/patreon.com/patreon.com.lst](services/patreon.com/patreon.com.lst) | 1 | 2026-03-24 13:47:02 |
| petlibro | [services/petlibro/petlibro.lst](services/petlibro/petlibro.lst) | 5 | 2026-03-24 13:47:02 |
| pinterest | [services/pinterest/pinterest.lst](services/pinterest/pinterest.lst) | 9 | 2026-03-24 13:47:02 |
| pixiv.net | [services/pixiv.net/pixiv.net.lst](services/pixiv.net/pixiv.net.lst) | 29 | 2026-03-24 13:47:02 |
| pornhub | [services/pornhub/pornhub.lst](services/pornhub/pornhub.lst) | 23 | 2026-03-24 13:47:02 |
| pubg | [services/pubg/pubg.lst](services/pubg/pubg.lst) | 28 | 2026-03-24 13:47:02 |
| qoder | [services/qoder/qoder.lst](services/qoder/qoder.lst) | 19 | 2026-03-24 13:47:02 |
| raid shadow legends | [services/raid shadow legends/raid shadow legends.lst](services/raid shadow legends/raid shadow legends.lst) | 45 | 2026-03-24 13:47:02 |
| roblox | [services/roblox/roblox.lst](services/roblox/roblox.lst) | 11 | 2026-03-24 13:47:02 |
| rutor.info | [services/rutor.info/rutor.info.lst](services/rutor.info/rutor.info.lst) | 4 | 2026-03-24 13:47:02 |
| signal | [services/signal/signal.lst](services/signal/signal.lst) | 7 | 2026-03-24 13:47:02 |
| snapchat | [services/snapchat/snapchat.lst](services/snapchat/snapchat.lst) | 13 | 2026-03-24 13:47:02 |
| soundcloud | [services/soundcloud/soundcloud.lst](services/soundcloud/soundcloud.lst) | 29 | 2026-03-24 13:47:02 |
| speedtest | [services/speedtest/speedtest.lst](services/speedtest/speedtest.lst) | 204 | 2026-03-24 13:47:02 |
| spotify | [services/spotify/spotify.lst](services/spotify/spotify.lst) | 78 | 2026-03-24 13:47:02 |
| squad busters | [services/squad busters/squad busters.lst](services/squad busters/squad busters.lst) | 90 | 2026-03-24 13:47:02 |
| strava.com | [services/strava.com/strava.com.lst](services/strava.com/strava.com.lst) | 120 | 2026-03-24 13:47:02 |
| supercell | [services/supercell/supercell.lst](services/supercell/supercell.lst) | 266 | 2026-03-24 13:47:02 |
| telegram | [services/telegram/telegram.lst](services/telegram/telegram.lst) | 40 | 2026-03-24 13:47:02 |
| tevas | [services/tevas/tevas.lst](services/tevas/tevas.lst) | 16 | 2026-03-24 13:47:02 |
| themoviedb | [services/themoviedb/themoviedb.lst](services/themoviedb/themoviedb.lst) | 2 | 2026-03-24 13:47:02 |
| thetvdb | [services/thetvdb/thetvdb.lst](services/thetvdb/thetvdb.lst) | 140 | 2026-03-24 13:47:02 |
| throne and liberty | [services/throne and liberty/throne and liberty.lst](services/throne and liberty/throne and liberty.lst) | 41 | 2026-03-24 13:47:02 |
| tidal | [services/tidal/tidal.lst](services/tidal/tidal.lst) | 59 | 2026-03-24 13:47:02 |
| tiktok | [services/tiktok/tiktok.lst](services/tiktok/tiktok.lst) | 123 | 2026-03-24 13:47:02 |
| tor | [services/tor/tor.lst](services/tor/tor.lst) | 8 | 2026-03-24 13:47:02 |
| trae.ai | [services/trae.ai/trae.ai.lst](services/trae.ai/trae.ai.lst) | 18 | 2026-03-24 13:47:02 |
| twitch | [services/twitch/twitch.lst](services/twitch/twitch.lst) | 206 | 2026-03-24 13:47:02 |
| ubiquiti | [services/ubiquiti/ubiquiti.lst](services/ubiquiti/ubiquiti.lst) | 7 | 2026-03-24 13:47:02 |
| viber | [services/viber/viber.lst](services/viber/viber.lst) | 101 | 2026-03-24 13:47:02 |
| videocdn.tv | [services/videocdn.tv/videocdn.tv.lst](services/videocdn.tv/videocdn.tv.lst) | 3 | 2026-03-24 13:47:02 |
| wetransfer.com | [services/wetransfer.com/wetransfer.com.lst](services/wetransfer.com/wetransfer.com.lst) | 20 | 2026-03-24 13:47:02 |
| whatsapp | [services/whatsapp/whatsapp.lst](services/whatsapp/whatsapp.lst) | 32 | 2026-03-24 13:47:02 |
| windsurf | [services/windsurf/windsurf.lst](services/windsurf/windsurf.lst) | 39 | 2026-03-24 13:47:02 |
| xbox | [services/xbox/xbox.lst](services/xbox/xbox.lst) | 393 | 2026-03-24 13:47:02 |
| youtube | [services/youtube/youtube.lst](services/youtube/youtube.lst) | 11 | 2026-03-24 13:47:02 |
| zoom | [services/zoom/zoom.lst](services/zoom/zoom.lst) | 67 | 2026-03-24 13:47:02 |
| zscaler | [services/zscaler/zscaler.lst](services/zscaler/zscaler.lst) | 7 | 2026-03-24 13:47:02 |

---

*Последнее обновление: 2026-03-24 13:47:15*
