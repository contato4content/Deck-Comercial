# 4Content · Deck Comercial

Apresentação comercial da 4Content (17 slides), na identidade "Luz e grão".

Abra o `index.html` no navegador para ver localmente, ou publique no GitHub Pages
para ter um link compartilhável.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `4content-deck`).
2. Envie **todo o conteúdo desta pasta** para a raiz do repositório
   (o `index.html` precisa ficar na raiz, junto com a pasta `assets`).
   - Pelo site: *Add file → Upload files*, arraste os arquivos e pastas e clique em *Commit changes*.
3. Vá em *Settings → Pages*.
4. Em *Build and deployment → Source*, escolha **Deploy from a branch**,
   branch **main**, pasta **/ (root)** e clique em *Save*.
5. Em 1 a 2 minutos o link aparece no topo da página *Pages*, no formato
   `https://SEU-USUARIO.github.io/4content-deck/`.

> O repositório precisa ser **público** para o GitHub Pages gratuito.
> Tudo o que estiver nele (fotos, vídeos e números) ficará acessível para quem tiver o link.

### Prévia ao compartilhar o link (opcional)

Para o link mostrar a imagem da capa no WhatsApp/LinkedIn, abra o `index.html`,
procure `og:image` e troque `assets/preview.jpg` pelo endereço completo, por exemplo:
`https://SEU-USUARIO.github.io/4content-deck/assets/preview.jpg`.

## Navegação

- **↑ ↓**, *Page Up/Down* ou rolagem: muda de slide
- **Índice** (canto superior direito): lista de todos os slides
- **F**: tela cheia
- **P**: esconde os avisos de pendência (se houver)
- Os vídeos tocam sozinhos, sem som, quando o slide aparece.

## Estrutura

```
index.html                     a apresentação
assets/video/                  capa, media day, media day (celular), torcida na virada
assets/img/                    fotos e logos, nomeados pelo número do slide
assets/fonts/                  Geist, Instrument Serif e JetBrains Mono
assets/preview.jpg             imagem de prévia do link
4Content_Deck_Comercial.pdf    versão em PDF
```
