> [!CAUTION]
> NÃO ACESSEM LINKS ENCURTADOS SEM UMA VERIFICAÇÃO PRÉVIA OU SEM CONHECIMENTO, OS LINKS ENCURTADOS LISTADOS NESSE PROJETO FORAM USADOS POR GOLPISTAS E PODEM SER REDIRECIONADOS PARA PÁGINAS MALICIOSAS.

> [!WARNING]  
> OS LINKS SÃO ANALISADOS E ADICIONAMOS MANUALMENTE NESSE PROJETO EVITANDO FALSO POSITIVO, TODOS OS LINKS LISTADOS EM [shortlinks.json](/scams/shortlinks.json) FORAM ENVIADOS POR GOLPISTAS EM SERVIDORES DE DISCORD.

### BLOCKLIST DE LINKS ENCURTADOS COMUMENTE ENVIADO POR GOLPISTA NO DISCORD

> [!NOTE]
> Registraremos nesse projeto links encurtados comumente enviados por golpista no Discord, veja o exemplo da imagem abaixo:

![img](https://i.imgur.com/8KHcjBx.png)


> [!IMPORTANT] 
> **️Não pretendemos remover os links encurtados, mesmo que eles não direcionem mais para um(a) IP/página da web válida, pois são e ainda foram criados para phishing/scam. Se o link encurtado não é mais redirecionado para uma página maliciosa, favor informar para a equipe do projeto no [servidor de suporte](https://discord.gg/PGmfDBSXC7).**
---
### Exemplo de como puxar os dados do projeto:
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
> Evidências de que os links encurtados tem/tinha relação com páginas maliciosas será registrada na opção [result_urlscan](/scams/shortlinks.json) desse projeto a fim de uma possível análise/investigação na veracidade das informações.

