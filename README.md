# Список публичных DNS серверов

## Что такое Dns?

Коротко:
> DNS (англ. Domain Name System «система доменных имён») — компьютерная распределённая система для получения информации о доменах.

Подробнее:
- [Здесь](https://ru.wikipedia.org/wiki/DNS)

## Установка для Windows

> Поиск - Панель Управления - Сеть и Интернет - Центр управления сетями - Изменение параметров адаптера - Беспроводная Сеть(П.К) - Свойства - IpV4 - Свойства

## Установка для Android 10+

> Настройки - Сеть и интернет - Дополнительно - Персональный DNS-сервер

## Установка для IOS

> Настройки - Wi-Fi - Выбрать сеть(свою) - Настройки DNS - Вручную

## Установка для Chrome, Firefox

### Chrome
> Перейти -> chrome://settings/security - Использовать безопасный DNS-сервер - Использовать 

### Firefox
> Перейти -> about:preferences - Параметры сети(настроить) - Включить DNS через HTTPS

## DNS Сервера

### Google DNS

1. 8.8.8.8
2. 8.8.4.4

- dns.google.com
- https://dns.google/dns-query

### CloudFlare

1. 1.1.1.1
2. 1.0.0.1

- 1dot1dot1dot1.cloudflare-dns.com
- https://security.cloudflare-dns.com/dns-query
- https://family.cloudflare-dns.com/dns-query

### OpenDNS

1. 208.67.222.222
2. 208.67.220.220

- https://doh.opendns.com/dns-query

### Quad9

Secured(Default) Malware Blocking, DNSSEC Validation
1. 9.9.9.9
2. 149.112.112.112
- dns.quad9.net
- https://dns.quad9.net/dns-query
- tls://dns.quad9.net

ECS enabled
1. 9.9.9.11
2. 149.112.112.11
- https://dns11.quad9.net/dns-query
- tls://dns11.quad9.net

Unsecured: No Malware blocking, no DNSSEC validation
1. 9.9.9.10
2. 149.112.112.10
- https://dns10.quad9.net/dns-query
- tls://dns10.quad9.net

### AdGuard

Default
1. 94.140.14.14
2. 94.140.15.15

Non-filtering
1. 94.140.14.140
2. 94.140.14.141

Family protection
1. 94.140.14.15
2. 94.140.15.16

- dns.adguard-dns.com
- unfiltered.adguard-dns.com
- family.adguard-dns.com

- https://dns.adguard-dns.com/dns-query
- https://unfiltered.adguard-dns.com/dns-query
- https://family.adguard-dns.com/dns-query

### NextDNS

1. Получать на [сайте](https://my.nextdns.io/)

- dns.nextdns.io (TLS)
- https://dns.nextdns.io/ (HTTPS)

### Snopyta DNS (Finland)

- https://fi.doh.dns.snopyta.org/dns-query

### KeepSolid DNS

1. 62.210.136.158
2. 69.162.67.202

### NordVPN DNS

1. 103.86.96.100
2. 103.86.99.100

### Comodo Secure DNS

1. 8.26.56.26
2. 8.20.247.20

### AT&T DNS

- https://dohtrial.att.net

### Level3DNS

1. 4.2.2.1
2. 4.2.2.2

### DNS.Watch

1. 84.200.69.80
2. 84.200.70.40

### Verising

1. 64.6.64.6
2. 64.6.65.6

### Symantec Norton DNS

1. 199.85.126.10
2. 199.85.127.10
