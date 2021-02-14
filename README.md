## g-webhook-spamer
- como usar:
```js
/*
infos:
https://discord.com/api/webhooks/805058800944021544/-WtLuInCLBKWw1o9wTAekR8W-czlB0rLVsZVtZFfATtHrwOptviHP0CR4FrGiHDBkcCc
                                  /\/\/\/\/\/\/\/\         /\/\/\/\/\/\/\/\/\/\
                                           ID                     TOKEN
*/
const {send, spam, start} = require('g-webhook_spamer')
// Caso queira flodar(demora um pouco pra começar)
spam(
'mensagem',
100//quantidade de mensagens, minimo 100 max 100.000
)
// Caso queira mandar só 1 vez
send(
'mensagem'
)
// pra configurar o webhook
start(
'id do webhook',
'token do webhook'
)
```
