> [!CAUTION]
> Não acessem links encurtados sem uma verificação prévia ou sem conhecimento, os links encurtados listados nesse projeto foram usados por golpistas e podem ser redirecionados para páginas maliciosas. 

### BLOCKLIST DE LINKS ENCURTADOS COMUMENTE ENVIADO POR GOLPISTA NO DISCORD

> [!NOTE]
> Registraremos nesse projeto links encurtados comumente enviados por golpista no Discord, veja o exemplo da imagem abaixo:

![img](https://i.imgur.com/6cEB0Tb.png)


> [!IMPORTANT] 
> **️Não pretendemos remover os links encurtados, mesmo que eles não direcionem mais para um(a) IP/página da web válida, pois são e ainda foram criados para phishing/scam. Se o link encurtado não é mais redirecionado para uma página maliciosa, favor informar para a equipe do projeto no [servidor de suporte](https://dsc.gg/t3guide).**
---
Exemplo:
```javascript
const axios = require("axios")
let url = `https://raw.githubusercontent.com/ravenastar-js/shortlinks-scams/main/scams/shortlinks.json`

const fetchData = async () => {
    const response = await axios.get(url);
    return response.data;
};

fetchData()
```
<a href="https://www.npmjs.com/package/axios" target="_blank"><img src="https://img.shields.io/badge/-axios-c40404?style=flat-square&labelColor=c40404&logo=npm&logoColor=white&link=https://www.npmjs.com/package/axios"/></a>

> [!TIP]
> Evidências de que os links encurtados tem/tinha relação com páginas maliciosas será registrada na opção [regex_block_domain_shortlinks](/scams/shortlinks.json) desse projeto a fim de uma possível análise/investigação na veracidade das informações.

