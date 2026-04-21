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
> Blizzard Entertainment: домены и CIDR для Battle.net, WoW, Diablo, Overwatch и др. вынесены в `blizzard.lst` — подключайте при необходимости.

© [amatol](https://t.me/amatol_blog) • [Telegram-канал](https://t.me/amatol_blog)

---

## Файлы

| Файл | Записей | Описание |
|------|--------:|----------|
| [domains.lst](domains.lst) | 2331 | Домены для маршрутизации |
| [cidr.lst](cidr.lst)       | 80 | IP-подсети (CIDR) для маршрутизации |
| [roblox.lst](roblox.lst)   | 130 | Домены и IP-подсети Roblox |
| [bungie_notapir.lst](bungie_notapir.lst) | 9 | Домены и IP-подсети Bungie (Destiny/Marathon) |
| [sonypsn.lst](sonypsn.lst) | 13 | Домены и IP-подсети Sony PlayStation Network |
| [blizzard.lst](blizzard.lst) | 83 | Домены и IP-подсети Blizzard Entertainment |

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
- [Discord.bat  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/Discord/Discord.bat)
- [discordgg.bat  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/Discord/discordgg.bat)

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

## Источники `blizzard.lst`

Список доменов и IP-подсетей Blizzard Entertainment (Battle.net, WoW, Diablo, Overwatch и др.):

- [blizzard.list  *(из MetaCubeX/meta-rules-dat)*](https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/refs/heads/meta/geo/geosite/blizzard.list)
- [blizzard.bat  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/blizzard/blizzard.bat)

---

## Сервисы

Отдельные файлы по сервисам из репозитория [RockBlack-VPN/ip-address](https://github.com/RockBlack-VPN/ip-address/tree/main/Global), обновляются автоматически:

| Сервис | Доменов | CIDR | Последнее обновление |
|--------|--------:|-----:|----------------------|
| [2407_pl](services/2407_pl/2407_pl.lst) | 0 | 2 | 2026-03-25 13:17:29 |
| [3dwarehouse_sketchup_com](services/3dwarehouse_sketchup_com/3dwarehouse_sketchup_com.lst) | 0 | 12 | 2026-03-25 13:17:29 |
| [adobe](services/adobe/adobe.lst) | 0 | 33 | 2026-03-24 13:47:02 |
| [ai_claude](services/ai_claude/ai_claude.lst) | 14 | 0 | 2026-03-25 13:17:29 |
| [airbnb](services/airbnb/airbnb.lst) | 0 | 11 | 2026-03-24 13:47:02 |
| [akamai](services/akamai/akamai.lst) | 0 | 34 | 2026-03-24 13:47:02 |
| [aliexpress](services/aliexpress/aliexpress.lst) | 0 | 7 | 2026-03-24 13:47:02 |
| [allegro_pl](services/allegro_pl/allegro_pl.lst) | 0 | 16 | 2026-03-25 13:17:29 |
| [anilibria](services/anilibria/anilibria.lst) | 0 | 5 | 2026-03-25 13:10:31 |
| [animego_org](services/animego_org/animego_org.lst) | 0 | 6 | 2026-03-25 13:17:29 |
| [anthropic_com](services/anthropic_com/anthropic_com.lst) | 0 | 1 | 2026-03-25 13:17:29 |
| [anydesk](services/anydesk/anydesk.lst) | 0 | 9 | 2026-03-24 13:47:02 |
| [apple](services/apple/apple.lst) | 0 | 4 | 2026-03-24 13:47:02 |
| [autodesk](services/autodesk/autodesk.lst) | 0 | 133 | 2026-03-24 13:47:02 |
| [aws_eu_us](services/aws_eu_us/aws_eu_us.lst) | 0 | 1028 | 2026-03-25 13:17:29 |
| [bato_to](services/bato_to/bato_to.lst) | 0 | 2 | 2026-03-25 13:17:29 |
| [battlefield5](services/battlefield5/battlefield5.lst) | 0 | 93 | 2026-03-24 13:47:02 |
| [bestchange](services/bestchange/bestchange.lst) | 0 | 3 | 2026-03-24 13:47:02 |
| [bethesda_net](services/bethesda_net/bethesda_net.lst) | 0 | 17 | 2026-03-25 13:17:29 |
| [bigfangroup_org](services/bigfangroup_org/bigfangroup_org.lst) | 0 | 11 | 2026-03-25 13:17:29 |
| [binance](services/binance/binance.lst) | 0 | 13 | 2026-03-24 13:47:02 |
| [bing_com](services/bing_com/bing_com.lst) | 0 | 15 | 2026-03-25 13:17:29 |
| [bizagi](services/bizagi/bizagi.lst) | 0 | 8 | 2026-03-24 13:47:02 |
| [blizzard](services/blizzard/blizzard.lst) | 0 | 60 | 2026-03-24 13:47:02 |
| [boosty](services/boosty/boosty.lst) | 0 | 8 | 2026-03-24 13:47:02 |
| [brawlstars](services/brawlstars/brawlstars.lst) | 0 | 3 | 2026-03-25 13:10:31 |
| [canva](services/canva/canva.lst) | 0 | 12 | 2026-03-24 13:47:02 |
| [chatgpt_openai](services/chatgpt_openai/chatgpt_openai.lst) | 5 | 53 | 2026-03-25 13:17:29 |
| [cisco](services/cisco/cisco.lst) | 0 | 73 | 2026-03-25 13:10:31 |
| [clash_royale](services/clash_royale/clash_royale.lst) | 0 | 404 | 2026-03-25 13:17:29 |
| [claude](services/claude/claude.lst) | 0 | 28 | 2026-03-25 13:10:31 |
| [cloudflare](services/cloudflare/cloudflare.lst) | 0 | 15 | 2026-03-24 13:47:02 |
| [coinglass_com](services/coinglass_com/coinglass_com.lst) | 0 | 13 | 2026-03-25 13:17:29 |
| [copilot](services/copilot/copilot.lst) | 0 | 69 | 2026-03-24 13:47:02 |
| [cs_2](services/cs_2/cs_2.lst) | 0 | 94 | 2026-03-25 13:17:29 |
| [deepl](services/deepl/deepl.lst) | 0 | 49 | 2026-03-25 13:10:31 |
| [dell_com](services/dell_com/dell_com.lst) | 0 | 24 | 2026-03-25 13:17:29 |
| [demonware_limited](services/demonware_limited/demonware_limited.lst) | 0 | 1 | 2026-03-25 13:10:31 |
| [digash_live](services/digash_live/digash_live.lst) | 0 | 18 | 2026-03-25 13:17:29 |
| [discord](services/discord/discord.lst) | 0 | 46 | 2026-03-25 13:17:29 |
| [dreame](services/dreame/dreame.lst) | 0 | 15 | 2026-04-12 03:00:01 |
| [duolingo](services/duolingo/duolingo.lst) | 0 | 8 | 2026-03-24 13:47:02 |
| [dw](services/dw/dw.lst) | 0 | 24 | 2026-03-25 13:10:31 |
| [ea](services/ea/ea.lst) | 0 | 19 | 2026-03-24 13:47:02 |
| [ebay](services/ebay/ebay.lst) | 0 | 32 | 2026-03-24 13:47:02 |
| [element](services/element/element.lst) | 0 | 7 | 2026-03-24 13:47:02 |
| [envato_com](services/envato_com/envato_com.lst) | 0 | 2 | 2026-03-25 13:17:29 |
| [epic_games](services/epic_games/epic_games.lst) | 0 | 6 | 2026-03-24 13:47:02 |
| [etsy_com](services/etsy_com/etsy_com.lst) | 0 | 94 | 2026-03-25 13:17:29 |
| [eufy](services/eufy/eufy.lst) | 3 | 0 | 2026-03-25 13:17:29 |
| [ewelink](services/ewelink/ewelink.lst) | 0 | 37 | 2026-03-24 13:47:02 |
| [facebook](services/facebook/facebook.lst) | 0 | 107 | 2026-03-24 13:47:02 |
| [facetime](services/facetime/facetime.lst) | 0 | 13 | 2026-03-24 13:47:02 |
| [fastly](services/fastly/fastly.lst) | 0 | 20 | 2026-03-24 13:47:02 |
| [figma](services/figma/figma.lst) | 0 | 14 | 2026-03-25 13:10:31 |
| [gemini](services/gemini/gemini.lst) | 13 | 94 | 2026-03-25 13:17:29 |
| [ggsel_net](services/ggsel_net/ggsel_net.lst) | 0 | 25 | 2026-03-25 13:17:29 |
| [github](services/github/github.lst) | 0 | 27 | 2026-03-25 13:10:31 |
| [google](services/google/google.lst) | 0 | 112 | 2026-03-25 13:10:31 |
| [grok](services/grok/grok.lst) | 0 | 5 | 2026-03-24 13:47:02 |
| [hay_day](services/hay_day/hay_day.lst) | 0 | 323 | 2026-03-25 13:17:29 |
| [hdrezka](services/hdrezka/hdrezka.lst) | 0 | 6 | 2026-03-24 13:47:02 |
| [hetzner](services/hetzner/hetzner.lst) | 0 | 70 | 2026-03-24 13:47:02 |
| [home_connect](services/home_connect/home_connect.lst) | 0 | 9 | 2026-03-25 13:17:29 |
| [hornet](services/hornet/hornet.lst) | 0 | 14 | 2026-03-24 13:47:02 |
| [imdb_com](services/imdb_com/imdb_com.lst) | 0 | 1 | 2026-03-25 13:17:29 |
| [instagram](services/instagram/instagram.lst) | 0 | 23 | 2026-03-25 13:10:31 |
| [intel](services/intel/intel.lst) | 0 | 6 | 2026-03-24 13:47:02 |
| [jetbrains_com](services/jetbrains_com/jetbrains_com.lst) | 0 | 55 | 2026-03-25 13:17:29 |
| [lampa](services/lampa/lampa.lst) | 0 | 15 | 2026-03-24 13:47:02 |
| [lenovo](services/lenovo/lenovo.lst) | 0 | 5 | 2026-03-24 13:47:02 |
| [linkedin](services/linkedin/linkedin.lst) | 0 | 46 | 2026-03-24 13:47:02 |
| [logo](services/logo/logo.lst) | 0 | 14 | 2026-03-25 13:10:31 |
| [lostfilm_tv](services/lostfilm_tv/lostfilm_tv.lst) | 0 | 4 | 2026-03-25 13:17:29 |
| [lucid](services/lucid/lucid.lst) | 0 | 13 | 2026-03-24 13:47:02 |
| [manus](services/manus/manus.lst) | 0 | 53 | 2026-03-25 13:10:31 |
| [medium](services/medium/medium.lst) | 0 | 1 | 2026-03-25 13:10:31 |
| [meduza_io](services/meduza_io/meduza_io.lst) | 0 | 13 | 2026-03-25 13:17:29 |
| [meta](services/meta/meta.lst) | 0 | 23 | 2026-03-24 13:47:02 |
| [microsoft](services/microsoft/microsoft.lst) | 0 | 359 | 2026-03-24 13:47:02 |
| [miro](services/miro/miro.lst) | 0 | 30 | 2026-03-25 13:10:31 |
| [mouser_com](services/mouser_com/mouser_com.lst) | 0 | 12 | 2026-03-25 13:17:29 |
| [myanimelist](services/myanimelist/myanimelist.lst) | 0 | 38 | 2026-03-24 13:47:02 |
| [netflix](services/netflix/netflix.lst) | 27 | 317 | 2026-03-25 13:10:31 |
| [nintendo](services/nintendo/nintendo.lst) | 0 | 37 | 2026-03-24 13:47:02 |
| [nnmclub_to](services/nnmclub_to/nnmclub_to.lst) | 0 | 3 | 2026-03-25 13:17:29 |
| [notepad](services/notepad/notepad.lst) | 0 | 1 | 2026-03-28 03:00:01 |
| [notion](services/notion/notion.lst) | 5 | 185 | 2026-03-25 13:17:29 |
| [nvidia](services/nvidia/nvidia.lst) | 0 | 23 | 2026-03-25 13:10:31 |
| [outlook](services/outlook/outlook.lst) | 0 | 325 | 2026-03-24 13:47:02 |
| [patreon](services/patreon/patreon.lst) | 0 | 15 | 2026-03-24 13:47:02 |
| [patreon_com](services/patreon_com/patreon_com.lst) | 0 | 1 | 2026-03-25 13:17:29 |
| [petlibro](services/petlibro/petlibro.lst) | 5 | 0 | 2026-03-24 13:47:02 |
| [pinterest](services/pinterest/pinterest.lst) | 0 | 9 | 2026-03-24 13:47:02 |
| [pixiv_net](services/pixiv_net/pixiv_net.lst) | 0 | 29 | 2026-03-25 13:17:29 |
| [pornhub](services/pornhub/pornhub.lst) | 0 | 23 | 2026-03-24 13:47:02 |
| [protonmail](services/protonmail/protonmail.lst) | 0 | 8 | 2026-03-28 03:00:01 |
| [pubg](services/pubg/pubg.lst) | 0 | 30 | 2026-03-25 13:17:29 |
| [qoder](services/qoder/qoder.lst) | 0 | 19 | 2026-03-24 13:47:02 |
| [raid_shadow_legends](services/raid_shadow_legends/raid_shadow_legends.lst) | 0 | 45 | 2026-03-24 13:47:02 |
| [roblox](services/roblox/roblox.lst) | 11 | 131 | 2026-03-25 13:17:29 |
| [rutor_info](services/rutor_info/rutor_info.lst) | 0 | 4 | 2026-03-25 13:17:29 |
| [rutracker](services/rutracker/rutracker.lst) | 0 | 4 | 2026-03-25 13:10:31 |
| [signal](services/signal/signal.lst) | 0 | 7 | 2026-03-24 13:47:02 |
| [snapchat](services/snapchat/snapchat.lst) | 0 | 13 | 2026-03-24 13:47:02 |
| [sonyplaystationnetwork](services/sonyplaystationnetwork/sonyplaystationnetwork.lst) | 0 | 13 | 2026-03-25 13:10:31 |
| [soundcloud](services/soundcloud/soundcloud.lst) | 0 | 29 | 2026-03-24 13:47:02 |
| [speedtest](services/speedtest/speedtest.lst) | 0 | 215 | 2026-03-25 13:17:29 |
| [spotify](services/spotify/spotify.lst) | 20 | 58 | 2026-03-24 13:47:02 |
| [squad_busters](services/squad_busters/squad_busters.lst) | 0 | 90 | 2026-03-24 13:47:02 |
| [steam](services/steam/steam.lst) | 0 | 16 | 2026-03-25 13:10:31 |
| [strava_com](services/strava_com/strava_com.lst) | 0 | 120 | 2026-03-25 13:17:29 |
| [supercell](services/supercell/supercell.lst) | 0 | 266 | 2026-03-24 13:47:02 |
| [tari_wallet](services/tari_wallet/tari_wallet.lst) | 0 | 6 | 2026-03-25 13:10:31 |
| [telegram](services/telegram/telegram.lst) | 19 | 21 | 2026-03-24 13:47:02 |
| [tevas](services/tevas/tevas.lst) | 0 | 16 | 2026-03-24 13:47:02 |
| [themoviedb](services/themoviedb/themoviedb.lst) | 2 | 0 | 2026-03-24 13:47:02 |
| [thetvdb](services/thetvdb/thetvdb.lst) | 64 | 76 | 2026-03-24 13:47:02 |
| [throne_and_liberty](services/throne_and_liberty/throne_and_liberty.lst) | 0 | 41 | 2026-03-24 13:47:02 |
| [tidal](services/tidal/tidal.lst) | 2 | 57 | 2026-03-24 13:47:02 |
| [tiktok](services/tiktok/tiktok.lst) | 24 | 99 | 2026-03-24 13:47:02 |
| [tor](services/tor/tor.lst) | 0 | 8 | 2026-03-24 13:47:02 |
| [trae_ai](services/trae_ai/trae_ai.lst) | 0 | 18 | 2026-03-25 13:17:29 |
| [tuta_io](services/tuta_io/tuta_io.lst) | 0 | 1 | 2026-03-25 13:17:29 |
| [twitch](services/twitch/twitch.lst) | 11 | 195 | 2026-03-24 13:47:02 |
| [twitter](services/twitter/twitter.lst) | 0 | 13 | 2026-03-25 13:10:31 |
| [ubiquiti](services/ubiquiti/ubiquiti.lst) | 0 | 7 | 2026-03-24 13:47:02 |
| [ubisoft](services/ubisoft/ubisoft.lst) | 0 | 7 | 2026-03-25 13:10:31 |
| [udemy](services/udemy/udemy.lst) | 0 | 2 | 2026-03-25 13:10:31 |
| [viber](services/viber/viber.lst) | 0 | 101 | 2026-03-24 13:47:02 |
| [videocdn_tv](services/videocdn_tv/videocdn_tv.lst) | 0 | 3 | 2026-03-25 13:17:29 |
| [warzone_xbox](services/warzone_xbox/warzone_xbox.lst) | 0 | 60 | 2026-03-25 13:17:29 |
| [wetransfer_com](services/wetransfer_com/wetransfer_com.lst) | 0 | 20 | 2026-03-25 13:17:29 |
| [whatsapp](services/whatsapp/whatsapp.lst) | 0 | 37 | 2026-03-25 13:17:29 |
| [windsurf](services/windsurf/windsurf.lst) | 0 | 39 | 2026-03-24 13:47:02 |
| [wot](services/wot/wot.lst) | 0 | 11 | 2026-03-25 13:10:31 |
| [wunderground](services/wunderground/wunderground.lst) | 0 | 21 | 2026-03-25 13:10:31 |
| [xbox](services/xbox/xbox.lst) | 0 | 393 | 2026-03-24 13:47:02 |
| [youtube](services/youtube/youtube.lst) | 11 | 96 | 2026-03-25 13:17:29 |
| [zoom](services/zoom/zoom.lst) | 0 | 67 | 2026-03-24 13:47:02 |
| [zscaler](services/zscaler/zscaler.lst) | 7 | 0 | 2026-03-24 13:47:02 |

---

*Последнее обновление: 2026-04-22 00:01:50*
