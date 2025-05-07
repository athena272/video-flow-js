# video-flow-js

Uma aplicação web simples que simula uma plataforma de exibição de vídeos, utilizando HTML, CSS e JavaScript puro. Os dados dos vídeos são carregados dinamicamente a partir de um arquivo JSON hospedado externamente.

## 🚀 Link de acesso

👉 [Acesse a aplicação aqui](https://athena272.github.io/video-flow-js/)

## 📸 Preview

![Preview do projeto](./img/VidFlow--Logo-light-mode.png)

![image](https://github.com/user-attachments/assets/6640bee9-380a-48fc-8e92-8a0e9b189799)

## ✨ Funcionalidades

- Interface responsiva para listagem de vídeos.
- Carregamento dinâmico de vídeos via `fetch()` a partir de um arquivo JSON.
- Estilização moderna com CSS Flexbox.
- Layout inspirado em plataformas de streaming de vídeo.

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (com uso de Flexbox)
- JavaScript (ES6+)
- JSON (para armazenamento dos dados dos vídeos)
- GitHub Pages (para deploy)


## 🧠 Como funciona

A aplicação carrega os dados dos vídeos de um arquivo `videos.json` hospedado remotamente. O script JavaScript busca esses dados e renderiza os vídeos dinamicamente na página principal (`index.html`), utilizando o container `.videos__container`.

## 📦 Instalação local

Caso queira rodar o projeto localmente:

```bash
git clone https://github.com/athena272/video-flow-js.git
cd video-flow-js
# abra o arquivo index.html em seu navegador
```

## 📁 Estrutura de Pastas
```
video-flow-js/
├── css/
│ ├── estilos.css
│ ├── flexbox.css
│ └── reset.css
├── img/
│ ├── Favicon.png
│ ├── VidFlow--Logo-light-mode.png
│ └── sidebar/
├── index.html
├── script.js
├── videos.json
└── README.md
```

## 📝 Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.


