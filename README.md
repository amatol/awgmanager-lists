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
> KinoPub: домены и CIDR для KinoPub вынесены в `kinopub.lst` — подключайте при необходимости.

© [amatol](https://t.me/amatol_blog) • [Telegram-канал](https://t.me/amatol_blog)

---

## Файлы

| Файл | Записей | Описание |
|------|--------:|----------|
| [domains.lst](domains.lst) | 3298 | Домены для маршрутизации |
| [cidr.lst](cidr.lst)       | 71 | IP-подсети (CIDR) для маршрутизации |
| [roblox.lst](roblox.lst)   | 15 | Домены и IP-подсети Roblox |
| [bungie_notapir.lst](bungie_notapir.lst) | 9 | Домены и IP-подсети Bungie (Destiny/Marathon) |
| [sonypsn.lst](sonypsn.lst) | 67 | Домены и IP-подсети Sony PlayStation Network |
| [blizzard.lst](blizzard.lst) | 129 | Домены и IP-подсети Blizzard Entertainment |
| [kinopub.lst](kinopub.lst) | 23 | Домены и IP-подсети KinoPub |

---

## Источники `domains.lst`

Список доменов собирается из следующих источников:

- [ooni_domains.lst  *(из 1andrevich/Re-filter-lists)*](https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/ooni_domains.lst)
- [inside-kvas.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Russia/inside-kvas.lst)
- [community.lst  *(из 1andrevich/Re-filter-lists)*](https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/community.lst)
- [geoblock.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Categories/geoblock.lst)
- [telegram_domain  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/Telegram/telegram_domain)
- [kino.lst  *(из amatol/xkeen-configuration)*](https://raw.githubusercontent.com/amatol/xkeen-configuration/refs/heads/main/rules/kino.lst)
- [community.lst  *(из amatol/xkeen-configuration)*](https://raw.githubusercontent.com/amatol/xkeen-configuration/refs/heads/main/rules/community.lst)
- [discord.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/discord.lst)
- [meta.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/meta.lst)
- [tiktok.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/tiktok.lst)
- [twitter.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/twitter.lst)
- [youtube.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/youtube.lst)

---

## Источники `cidr.lst`

Список IP-подсетей собирается из следующих источников:

- [telegram.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Subnets/IPv4/telegram.lst)
- [telegram.bat  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/Telegram/telegram.bat)
- [Discord.bat  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/Discord/Discord.bat)

---

## Источники `roblox.lst`

Список доменов и IP-подсетей Roblox:

- [roblox_domain  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/Roblox/roblox_domain)
- [roblox-ips.lst  *(из amatol/xkeen-configuration)*](https://raw.githubusercontent.com/amatol/xkeen-configuration/refs/heads/main/rules/roblox-ips.lst)

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

## Источники `kinopub.lst`

Список доменов и IP-подсетей KinoPub:

- [kinopub.list  *(из MetaCubeX/meta-rules-dat)*](https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/refs/heads/meta/geo/geosite/kinopub.list)
- [kino.lst  *(из amatol/xkeen-configuration)*](https://raw.githubusercontent.com/amatol/xkeen-configuration/refs/heads/main/rules/kino.lst)

---

## Сервисы

Отдельные файлы по сервисам из репозитория [RockBlack-VPN/ip-address](https://github.com/RockBlack-VPN/ip-address/tree/main/Global), обновляются автоматически:

| Сервис | Доменов | CIDR | Последнее обновление |
|--------|--------:|-----:|----------------------|
| [2407_pl](services/2407_pl/2407_pl.lst) | 0 | 4 | 2026-11-08 21:59:09 |
| [3dwarehouse_sketchup_com](services/3dwarehouse_sketchup_com/3dwarehouse_sketchup_com.lst) | 0 | 33 | 2026-11-08 21:59:09 |
| [adobe](services/adobe/adobe.lst) | 0 | 94 | 2026-11-08 21:59:09 |
| [airbnb](services/airbnb/airbnb.lst) | 0 | 23 | 2026-11-08 21:59:09 |
| [akamai](services/akamai/akamai.lst) | 0 | 34 | 2026-03-24 13:47:02 |
| [aliexpress](services/aliexpress/aliexpress.lst) | 0 | 26 | 2026-11-08 21:59:09 |
| [allegro_pl](services/allegro_pl/allegro_pl.lst) | 0 | 19 | 2026-11-08 21:59:09 |
| [anilibria](services/anilibria/anilibria.lst) | 0 | 11 | 2026-11-08 21:59:09 |
| [animego_org](services/animego_org/animego_org.lst) | 0 | 9 | 2026-11-08 21:59:09 |
| [anydesk](services/anydesk/anydesk.lst) | 0 | 23 | 2026-11-08 21:59:09 |
| [apple](services/apple/apple.lst) | 0 | 34 | 2026-11-08 21:59:09 |
| [autodesk](services/autodesk/autodesk.lst) | 0 | 167 | 2026-11-08 21:59:09 |
| [aws_eu_us](services/aws_eu_us/aws_eu_us.lst) | 0 | 1028 | 2026-03-25 13:17:29 |
| [bato_to](services/bato_to/bato_to.lst) | 0 | 9 | 2026-11-08 21:59:09 |
| [battlefield5](services/battlefield5/battlefield5.lst) | 0 | 145 | 2026-11-08 21:59:09 |
| [bestchange](services/bestchange/bestchange.lst) | 0 | 12 | 2026-11-08 21:59:09 |
| [bethesda_net](services/bethesda_net/bethesda_net.lst) | 0 | 42 | 2026-11-08 21:59:09 |
| [bigfangroup_org](services/bigfangroup_org/bigfangroup_org.lst) | 0 | 11 | 2026-03-25 13:17:29 |
| [binance](services/binance/binance.lst) | 0 | 178 | 2026-11-08 21:59:09 |
| [bing_com](services/bing_com/bing_com.lst) | 0 | 31 | 2026-11-08 21:59:09 |
| [bizagi](services/bizagi/bizagi.lst) | 0 | 19 | 2026-11-08 21:59:09 |
| [blizzard](services/blizzard/blizzard.lst) | 0 | 104 | 2026-11-08 21:59:09 |
| [boosty](services/boosty/boosty.lst) | 0 | 10 | 2026-11-08 21:59:09 |
| [brawlstars](services/brawlstars/brawlstars.lst) | 0 | 25 | 2026-11-08 21:59:09 |
| [canva](services/canva/canva.lst) | 0 | 24 | 2026-11-08 21:59:09 |
| [chatgpt_openai](services/chatgpt_openai/chatgpt_openai.lst) | 5 | 56 | 2026-11-08 21:59:09 |
| [cisco](services/cisco/cisco.lst) | 0 | 102 | 2026-11-08 21:59:09 |
| [clash_royale](services/clash_royale/clash_royale.lst) | 0 | 481 | 2026-11-08 21:59:09 |
| [claude](services/claude/claude.lst) | 14 | 42 | 2026-11-08 21:59:09 |
| [cloudflare](services/cloudflare/cloudflare.lst) | 0 | 15 | 2026-03-24 13:47:02 |
| [coinglass_com](services/coinglass_com/coinglass_com.lst) | 0 | 28 | 2026-11-08 21:59:09 |
| [copilot](services/copilot/copilot.lst) | 0 | 96 | 2026-11-08 21:59:09 |
| [cs_2](services/cs_2/cs_2.lst) | 0 | 118 | 2026-11-08 21:59:09 |
| [deepl](services/deepl/deepl.lst) | 0 | 51 | 2026-11-08 21:59:09 |
| [dell_com](services/dell_com/dell_com.lst) | 0 | 37 | 2026-11-08 21:59:09 |
| [demonware_limited](services/demonware_limited/demonware_limited.lst) | 0 | 9 | 2026-11-08 21:59:09 |
| [digash_live](services/digash_live/digash_live.lst) | 0 | 18 | 2026-03-25 13:17:29 |
| [discord](services/discord/discord.lst) | 0 | 49 | 2026-11-08 21:59:09 |
| [dreame](services/dreame/dreame.lst) | 0 | 27 | 2026-11-08 21:59:09 |
| [duolingo](services/duolingo/duolingo.lst) | 0 | 117 | 2026-11-08 21:59:09 |
| [dw](services/dw/dw.lst) | 0 | 26 | 2026-11-08 21:59:09 |
| [ea](services/ea/ea.lst) | 0 | 102 | 2026-11-08 21:59:09 |
| [ebay](services/ebay/ebay.lst) | 0 | 41 | 2026-11-08 22:07:34 |
| [element](services/element/element.lst) | 0 | 17 | 2026-11-08 21:59:09 |
| [envato_com](services/envato_com/envato_com.lst) | 0 | 27 | 2026-11-08 21:59:09 |
| [epic_games](services/epic_games/epic_games.lst) | 0 | 118 | 2026-11-08 21:59:09 |
| [etsy_com](services/etsy_com/etsy_com.lst) | 0 | 103 | 2026-11-08 21:59:09 |
| [eufy](services/eufy/eufy.lst) | 3 | 65 | 2026-11-08 21:59:09 |
| [ewelink](services/ewelink/ewelink.lst) | 0 | 64 | 2026-11-08 21:59:09 |
| [facebook](services/facebook/facebook.lst) | 0 | 123 | 2026-11-08 21:59:09 |
| [facetime](services/facetime/facetime.lst) | 0 | 37 | 2026-11-08 21:59:09 |
| [fastly](services/fastly/fastly.lst) | 0 | 86 | 2026-11-08 21:59:09 |
| [figma](services/figma/figma.lst) | 0 | 80 | 2026-11-08 21:59:09 |
| [gemini](services/gemini/gemini.lst) | 13 | 60 | 2026-11-08 21:59:09 |
| [ggsel_net](services/ggsel_net/ggsel_net.lst) | 0 | 27 | 2026-11-08 21:59:09 |
| [github](services/github/github.lst) | 0 | 69 | 2026-11-08 21:59:09 |
| [google](services/google/google.lst) | 0 | 139 | 2026-11-08 21:59:09 |
| [grok](services/grok/grok.lst) | 0 | 7 | 2026-11-08 21:59:09 |
| [hay_day](services/hay_day/hay_day.lst) | 0 | 409 | 2026-11-08 21:59:09 |
| [hdrezka](services/hdrezka/hdrezka.lst) | 0 | 18 | 2026-11-08 21:59:09 |
| [hetzner](services/hetzner/hetzner.lst) | 0 | 84 | 2026-11-08 21:59:09 |
| [home_connect](services/home_connect/home_connect.lst) | 0 | 21 | 2026-11-08 21:59:09 |
| [hornet](services/hornet/hornet.lst) | 0 | 63 | 2026-11-08 21:59:09 |
| [imdb_com](services/imdb_com/imdb_com.lst) | 0 | 100 | 2026-11-08 21:59:09 |
| [instagram](services/instagram/instagram.lst) | 0 | 59 | 2026-11-08 21:59:09 |
| [intel](services/intel/intel.lst) | 0 | 32 | 2026-11-08 21:59:09 |
| [jetbrains_com](services/jetbrains_com/jetbrains_com.lst) | 0 | 43 | 2026-11-08 21:59:09 |
| [lampa](services/lampa/lampa.lst) | 0 | 24 | 2026-11-08 21:59:09 |
| [lenovo](services/lenovo/lenovo.lst) | 0 | 24 | 2026-11-08 21:59:09 |
| [lg_thinq](services/lg_thinq/lg_thinq.lst) | 51 | 251 | 2026-11-08 21:59:09 |
| [linkedin](services/linkedin/linkedin.lst) | 0 | 60 | 2026-11-08 21:59:09 |
| [logo](services/logo/logo.lst) | 0 | 16 | 2026-11-08 21:59:09 |
| [lostfilm_tv](services/lostfilm_tv/lostfilm_tv.lst) | 0 | 7 | 2026-11-08 21:59:09 |
| [lovable](services/lovable/lovable.lst) | 11 | 14 | 2026-11-08 21:59:09 |
| [lucid](services/lucid/lucid.lst) | 0 | 24 | 2026-11-08 21:59:09 |
| [manus](services/manus/manus.lst) | 0 | 76 | 2026-11-08 21:59:09 |
| [medium](services/medium/medium.lst) | 0 | 7 | 2026-11-08 21:59:09 |
| [meduza_io](services/meduza_io/meduza_io.lst) | 0 | 19 | 2026-11-08 21:59:09 |
| [meta](services/meta/meta.lst) | 0 | 25 | 2026-11-08 21:59:09 |
| [microsoft](services/microsoft/microsoft.lst) | 0 | 424 | 2026-11-08 21:59:09 |
| [miro](services/miro/miro.lst) | 0 | 35 | 2026-11-08 21:59:09 |
| [mouser_com](services/mouser_com/mouser_com.lst) | 0 | 18 | 2026-11-08 21:59:09 |
| [myanimelist](services/myanimelist/myanimelist.lst) | 0 | 45 | 2026-11-08 21:59:09 |
| [netflix](services/netflix/netflix.lst) | 27 | 275 | 2026-11-08 22:07:34 |
| [nintendo](services/nintendo/nintendo.lst) | 0 | 65 | 2026-11-08 21:59:09 |
| [nnmclub_to](services/nnmclub_to/nnmclub_to.lst) | 0 | 8 | 2026-11-08 21:59:09 |
| [notepad](services/notepad/notepad.lst) | 0 | 2 | 2026-11-08 21:59:09 |
| [notion](services/notion/notion.lst) | 5 | 218 | 2026-11-08 21:59:09 |
| [nvidia](services/nvidia/nvidia.lst) | 0 | 84 | 2026-11-08 21:59:09 |
| [outlook](services/outlook/outlook.lst) | 0 | 351 | 2026-11-08 21:59:09 |
| [patreon](services/patreon/patreon.lst) | 0 | 21 | 2026-11-08 21:59:09 |
| [petlibro](services/petlibro/petlibro.lst) | 5 | 8 | 2026-11-08 21:59:09 |
| [pinterest](services/pinterest/pinterest.lst) | 0 | 27 | 2026-11-08 21:59:09 |
| [pixiv_net](services/pixiv_net/pixiv_net.lst) | 0 | 31 | 2026-11-08 21:59:09 |
| [pornhub](services/pornhub/pornhub.lst) | 0 | 30 | 2026-11-08 21:59:09 |
| [protonmail](services/protonmail/protonmail.lst) | 0 | 23 | 2026-11-08 21:59:09 |
| [pubg](services/pubg/pubg.lst) | 0 | 57 | 2026-11-08 21:59:09 |
| [qoder](services/qoder/qoder.lst) | 0 | 46 | 2026-11-08 21:59:09 |
| [raid_shadow_legends](services/raid_shadow_legends/raid_shadow_legends.lst) | 0 | 48 | 2026-11-08 21:59:09 |
| [roblox](services/roblox/roblox.lst) | 11 | 135 | 2026-11-08 21:59:09 |
| [rutor_info](services/rutor_info/rutor_info.lst) | 0 | 5 | 2026-11-08 21:59:09 |
| [rutracker](services/rutracker/rutracker.lst) | 0 | 15 | 2026-11-08 21:59:09 |
| [signal](services/signal/signal.lst) | 0 | 41 | 2026-11-08 21:59:09 |
| [snapchat](services/snapchat/snapchat.lst) | 0 | 36 | 2026-11-08 21:59:09 |
| [sonyplaystationnetwork](services/sonyplaystationnetwork/sonyplaystationnetwork.lst) | 0 | 67 | 2026-11-08 21:59:09 |
| [soundcloud](services/soundcloud/soundcloud.lst) | 0 | 42 | 2026-11-08 21:59:09 |
| [speedtest](services/speedtest/speedtest.lst) | 0 | 225 | 2026-11-08 21:59:09 |
| [spotify](services/spotify/spotify.lst) | 20 | 72 | 2026-11-08 21:59:09 |
| [squad_busters](services/squad_busters/squad_busters.lst) | 0 | 114 | 2026-11-08 21:59:09 |
| [steam](services/steam/steam.lst) | 0 | 40 | 2026-11-08 21:59:09 |
| [strava_com](services/strava_com/strava_com.lst) | 0 | 150 | 2026-11-08 22:07:34 |
| [supercell](services/supercell/supercell.lst) | 0 | 471 | 2026-11-08 21:59:09 |
| [tari_wallet](services/tari_wallet/tari_wallet.lst) | 0 | 8 | 2026-11-08 21:59:09 |
| [telegram](services/telegram/telegram.lst) | 19 | 25 | 2026-11-08 21:59:09 |
| [tevas](services/tevas/tevas.lst) | 0 | 17 | 2026-11-08 21:59:09 |
| [themoviedb](services/themoviedb/themoviedb.lst) | 2 | 15 | 2026-11-08 21:59:09 |
| [thetvdb](services/thetvdb/thetvdb.lst) | 64 | 95 | 2026-11-08 21:59:09 |
| [throne_and_liberty](services/throne_and_liberty/throne_and_liberty.lst) | 0 | 58 | 2026-11-08 21:59:09 |
| [tidal](services/tidal/tidal.lst) | 2 | 90 | 2026-11-08 21:59:09 |
| [tiktok](services/tiktok/tiktok.lst) | 24 | 188 | 2026-11-08 21:59:09 |
| [tor](services/tor/tor.lst) | 0 | 12 | 2026-11-08 21:59:09 |
| [trae_ai](services/trae_ai/trae_ai.lst) | 0 | 56 | 2026-11-08 21:59:09 |
| [tuta_io](services/tuta_io/tuta_io.lst) | 0 | 2 | 2026-11-08 21:59:09 |
| [twitch](services/twitch/twitch.lst) | 11 | 234 | 2026-11-08 22:07:34 |
| [twitter](services/twitter/twitter.lst) | 0 | 70 | 2026-11-08 21:59:09 |
| [ubiquiti](services/ubiquiti/ubiquiti.lst) | 0 | 80 | 2026-11-08 21:59:09 |
| [ubisoft](services/ubisoft/ubisoft.lst) | 0 | 90 | 2026-11-08 21:59:09 |
| [udemy](services/udemy/udemy.lst) | 0 | 16 | 2026-11-08 21:59:09 |
| [viber](services/viber/viber.lst) | 0 | 129 | 2026-11-08 21:59:09 |
| [videocdn_tv](services/videocdn_tv/videocdn_tv.lst) | 0 | 6 | 2026-11-08 21:59:09 |
| [warzone_xbox](services/warzone_xbox/warzone_xbox.lst) | 0 | 88 | 2026-11-08 21:59:09 |
| [wetransfer_com](services/wetransfer_com/wetransfer_com.lst) | 0 | 56 | 2026-11-08 21:59:09 |
| [whatsapp](services/whatsapp/whatsapp.lst) | 0 | 43 | 2026-11-08 21:59:09 |
| [wikipedia](services/wikipedia/wikipedia.lst) | 0 | 7 | 2026-11-08 21:59:09 |
| [windsurf](services/windsurf/windsurf.lst) | 8 | 45 | 2026-11-08 21:59:09 |
| [wot](services/wot/wot.lst) | 0 | 22 | 2026-11-08 21:59:09 |
| [wunderground](services/wunderground/wunderground.lst) | 0 | 52 | 2026-11-08 21:59:09 |
| [xbox](services/xbox/xbox.lst) | 0 | 424 | 2026-11-08 21:59:09 |
| [youtube](services/youtube/youtube.lst) | 14 | 124 | 2026-11-08 21:59:09 |
| [zoom](services/zoom/zoom.lst) | 0 | 76 | 2026-11-08 21:59:09 |
| [zscaler](services/zscaler/zscaler.lst) | 7 | 4 | 2026-11-08 21:59:09 |

---

*Последнее обновление: 2026-11-08 22:07:48*
