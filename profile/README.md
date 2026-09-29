# Bí-Bor belső appok

Minden app a **dashboardból** indul: ott van a közös belépés és az
alkalmazásválasztó. Az appok a dashboard moduljai, de mindegyik külön repó,
külön domainen, saját verziószámmal.

```
dashboard            hub: közös belépés, app-lista (apps.php)
 ├─ webstat          statisztika és riportok
 ├─ cashsky          pénzügyi áttekintés
 ├─ pultpilot        bolti kasszaeladások
 ├─ samurai          UNAS AI-asszisztens
 ├─ speedsky         Skylon gyors lekérdező, hitelkeretek, Pricer
 └─ bphub            palack forecast, készlet, beszerzés, rendelés
```

| | Repó | Élő oldal |
| --- | --- | --- |
| **Hub** | [dashboard](https://github.com/bi-bor/dashboard) | https://dashboard.bi-bor.hu |
| Modul | [webstat](https://github.com/bi-bor/webstat) | https://webstat.bi-bor.hu |
| Modul | [cashsky](https://github.com/bi-bor/cashsky) | https://cashsky.bi-bor.hu |
| Modul | [pultpilot](https://github.com/bi-bor/pultpilot) | https://pult.bi-bor.hu |
| Modul | [samurai](https://github.com/bi-bor/samurai) | https://samurai.bi-bor.hu |
| Modul | [speedsky](https://github.com/bi-bor/speedsky) | https://speedsky.bi-bor.hu |
| Modul | [bphub](https://github.com/bi-bor/bphub) | https://palack.bi-bor.hu |

Az app-listában szerepel még a Beszerző (procura.bi-bor.hu); ennek nincs
repója ebben a szervezetben.

Új modul: külön repó `modul` topickal, bejegyzés a dashboard
`login/apps.php`-jába, és egy sor ebbe a táblázatba.
