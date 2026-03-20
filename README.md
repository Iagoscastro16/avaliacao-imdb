### 🎬 Movieverse

Aplicação web para busca de filmes com o tema escuro, desenvolvida com html, css e JavaScript puro, consumindo a OMDb API 

### 🚀 Funcionalidades

- 🔍 Busca por filmes em tempo real

- 🖼️ Exibe pôster, titulo e ano de cada resultado

- ⚠️ Tratamento de erros por ausência de resultados

- 📱 Layout responsivo e centralizado

### 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript (ES6+ com módulos)
- [OMDb API](https://www.omdbapi.com/)

### 📁 Estrutura do projeto
 
```
avaliacao-imdb/
├── index.html
└── assets/
    ├── style.css
    └── js/
        ├── script.js
        └── dadosApi.js
```

### ⚙️ Como usar

1 - Clone o repositório 

2 - Utilize a extensão live server ou semelhantes, pois o projeto necessita de um servidor próprio para funcionar

3 - Digite o nome de um filme no campo de busca e clique em **Buscar** ou pressione `Enter`.

⚠️ Observações

Pelo fato da api ser estrangeira, o nome do filme deve ser pesquisado em inglês.

Por usar módulos ES6 (`type="module"`), o projeto **não funciona** ao abrir o arquivo diretamente via `file://`. Recomenda-se usar um servidor local.

### 🔑 API Key

O projeto utiliza a [OMDb API](https://www.omdbapi.com/). A chave de acesso fica em `assets/js/dadosApi.js`

Caso queira usar sua própria chave, cria uma conta gratuita em [omdbapi.com](https://www.omdbapi.com/apikey.aspx) e substitua o valor em 
```js
// assets/js/dadosApi.js
const chaveApi = "SUA_CHAVE_AQUI";
export default chaveApi;
```

---
 
Desenvolvido por **Iago Castro** ©
