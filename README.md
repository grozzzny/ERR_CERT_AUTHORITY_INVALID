# It is not safe to open a site without a certificate (https, ssl) / открыть сайт без сертификата не безопасно (https, ssl)
Open site with NET::ERR_CERT_AUTHORITY_INVALID

Если у вас появилась ошибка «Невозможно установить безопасное соединение» (Your connection is not private) и нет ссылки «Перейти не безопасно» (Proceed to my-site (unsafe)), но в силу рабочих моментов, вам все же необходимо перейти, то можно выполнить команду в консоли (run a command in the console):

```
sendCommand(SecurityInterstitialCommandId.CMD_PROCEED);
```
