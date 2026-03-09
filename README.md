# AWG Manager — списки маршрутизации

> Готовые наборы правил для [AWG Manager](https://t.me/awgmanager).
> Списки собираются **автоматически** из нескольких открытых источников,
> дедублируются и минимизируются — поддомены схлопываются при явном родителе,
> перекрывающиеся CIDR агрегируются.
> Цель проекта: избавить обычного пользователя от необходимости вручную добавлять
> десятки ссылок — достаточно подключить нужные файлы и получить стандартный набор
> соцсетей, мессенджеров, стриминга и AI-сервисов.

© [amatol](https://t.me/amatol_blog) • [Telegram-канал](https://t.me/amatol_blog)

---

## Файлы

| Файл | Записей | Описание |
|------|--------:|----------|
| [domains.lst](domains.lst) | 2061 | Домены для маршрутизации |
| [cidr.lst](cidr.lst)       | 13 | IP-подсети (CIDR) для маршрутизации |
| [roblox.lst](roblox.lst)   | 0 | Домены и IP-подсети Roblox |

---

## Источники `domains.lst`

Список доменов собирается из следующих источников:

- [ooni_domains.lst  *(из 1andrevich/Re-filter-lists)*](https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/ooni_domains.lst)
- [community.lst  *(из 1andrevich/Re-filter-lists)*](https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/community.lst)
- [geoblock.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Categories/geoblock.lst)
- [kino.lst  *(из amatol/xkeen-configuration)*](https://raw.githubusercontent.com/amatol/xkeen-configuration/refs/heads/main/rules/kino.lst)
- [community.lst  *(из amatol/xkeen-configuration)*](https://raw.githubusercontent.com/amatol/xkeen-configuration/refs/heads/main/rules/community.lst)
- [discord.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/discord.lst)
- [hdrezka.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/hdrezka.lst)
- [meta.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/meta.lst)
- [tiktok.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/tiktok.lst)
- [twitter.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/twitter.lst)
- [youtube.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Services/youtube.lst)
- [roblox_domain  *(из RockBlack-VPN/ip-address)*](https://raw.githubusercontent.com/RockBlack-VPN/ip-address/refs/heads/main/Global/Roblox/roblox_domain)

---

## Источники `cidr.lst`

Список IP-подсетей собирается из следующих источников:

- [telegram.lst  *(из itdoginfo/allow-domains)*](https://raw.githubusercontent.com/itdoginfo/allow-domains/refs/heads/main/Subnets/IPv4/telegram.lst)
- [roblox-ips.lst  *(из amatol/xkeen-configuration)*](https://raw.githubusercontent.com/amatol/xkeen-configuration/refs/heads/main/rules/roblox-ips.lst)

---

## Источники `roblox.lst`

Список доменов и IP-подсетей Roblox (поддерживаются `route add` записи):


---

*Последнее обновление: 2026-03-09 19:41:45*
