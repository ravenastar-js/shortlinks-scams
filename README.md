> [!CAUTION]
> Não acessar links encurtados sem uma verificação prévia ou sem conhecimento, os links listados nesse projeto foram usados por golpistas e são direcionados para páginas maliciosas. 

### BLOCKLIST DE LINKS ENCURTADOS COMUMENTE ENVIADO POR GOLPISTA NO DISCORD

> [!NOTE]
> Registraremos links encurtados comumente enviados por golpista, veja o exemplo da imagem abaixo.

![img](https://i.imgur.com/6cEB0Tb.png)


> [!IMPORTANT] 
> **️Não pretendemos remover os links encurtados, mesmo que eles não direcionem mais para um(a) IP/página da web válida, pois são e ainda foram criados para phishing/scam. Se o link encurtado não é mais redirecionado para uma página maliciosa, favor informar para a equipe do projeto no [servidor de suporte](https://dsc.gg/t3guide).**
---

### SCRIPT PARA PUXAR AS INFORMAÇÕES DA BLOCKLIST
```js
const blocklist = 'https://raw.githubusercontent.com/ravenastar-js/shortlinks-scams/main/scams/shortlinks.json'

const fetch = require('node-fetch')

const response = await fetch(`${blocklist}`);
const data = await response.json();

console.log(data);
```
