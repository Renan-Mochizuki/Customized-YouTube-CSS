# CSS customizado para o YouTube

Esse é um código CSS que criei para customizar o YouTube e fazer algumas alterações em seu layout para uso pessoal e melhor usabilidade do site.

## Modificações

- **Barra lateral arco-íris animada (RGB)**

<div align="center">
    <img width="150" src="./img/prints/barralateral.gif" alt="Barra Lateral"> 
</div>

- **Header**

<div align="center">
    <img width="720" src="./img/prints/header.gif" alt="Header">
</div>

- **Mudanças gerais de cor**

<div align="center">
    <img width="720" src="./img/paginavideo.png" alt="Tela vídeo">
</div>

- **Ocultamento dos Shorts da tela de vídeo**

Para ver os Shorts passe o cursor por cima.

<div align="center">
    <img width="720" src="./img/ocultamentoshorts.gif" alt="Ocultamento dos Shorts">
</div>

- **Ocultamento da header quando a tela estiver pequena**

Para acessar, na página de vídeo, passe o cursor na parte superior da página.
Em outras páginas como Home e Shorts, passe o cursor por cima do ícone de olho.

<div align="center">
    <img width="720" src="./img/ocultamentoheader.gif" alt="Ocultamento dos Header">
</div>

**Caso não queira ocultar**

Se não quiser que os Shorts ou a header seja ocultada, basta modificar as váriaveis `--neverhideshorts` e `--neverhideheader` para o valor `1` no código CSS em `:root`.

**Outras mudanças mínimas**

- Adição de ícones nos detalhes da playlist na tela de playlist;

- Adição de brilho nos botões like/dislike e título do vídeo;

- Adição de borda enevoada em alguns botões;

- Remoção dos chips/temas da Home (Para acessar minimize a barra lateral);

- Remoção dos chips/temas da página de vídeo (Para acessar abra/expanda a descrição do vídeo)

- Caixa de descrição transparente.

# Como usar

Para utilizar a customização é necessário uma extensão que permita inserir um código CSS no navegador, como por exemplo:

#### [Stylus](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)

Baixe e abra a extensão na página home do YouTube e uma janela flutuante aparecerá, clique no botão de `+` para escrever um novo estilo para o YouTube.

<div align="center">
    <img width="360" src="./img/prints/stylusadd.png" alt="Print adicionar novo estilo">
</div>

Uma aba será aberta, então copie e cole todo o código do arquivo [`youtube.css`](./youtube.css) nessa aba e clique no botão amarelo `Salvar`.

<div align="center">
    <img width="720" src="./img/prints/styluscodigo.png" alt="Print aba Stylus">
</div>

Você pode ligar e desligar a customização clicando no botão com a logo da extensão da janela flutuante.

<!-- #### [User JavaScript and CSS](https://chromewebstore.google.com/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld)

Baixe e abra a extensão na página home do YouTube e uma janela flutuante aparecerá, clique no botão `New rule` para escrever um novo estilo para o YouTube.

<div align="center">
    <img width="360" src="./img/prints/usercssjsadd.png" alt="Print adicionar novo estilo">
</div>

Uma aba será aberta, então copie e cole todo o código do arquivo [`youtube.css`](./youtube.css) nessa aba, no lado direito, e clique no botão amarelo `Save`.

<div align="center">
    <img width="720" src="./img/prints/usercssjscodigo.png" alt="Print aba Stylus">
</div>

Você pode ligar e desligar a customização clicando no botão alternar na janela flutuante. -->
