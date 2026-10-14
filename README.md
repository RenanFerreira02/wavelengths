# Wavelengths · Álbuns que me formaram

Página de estudo da Fase 1 do portfólio (HTML + CSS). Ela apresenta álbuns que marcaram minha formação e é construída etapa por etapa, um conceito por commit, para ser usada em aula.

## Como abrir

Não precisa instalar nada: abra o arquivo `index.html` no navegador.

Para ver a página como ela estava em uma etapa, use `git log --oneline` e depois `git checkout <hash>`. Para voltar ao fim do projeto, `git checkout main`.

## Etapas

- `00-ponto-de-partida`: esqueleto do documento HTML.
- `01-estrutura-semantica`: header, nav, main, sections, footer e o conteúdo dos álbuns.
- `02-imagens`: capas com `img`, `alt`, `width` e `height`.
- `03-seletores`: `style.css` com seletores de tag, classe, id e descendente.
- `04-pseudo-classes`: `:hover` e `:focus-visible`.
- `05-cascata-e-heranca`: herança a partir do `body`, `inherit` e especificidade.
- `06-box-model`: `margin`, `padding`, `border` e `box-sizing`.
- `07-cores-e-tipografia`: paleta com contraste conferido e fontes do Google Fonts.
- `08-variaveis-css`: `--color-accent` próprio de cada álbum.
- `09-flexbox`: header, menu, etiquetas de gênero e clima do álbum em linha.
- `10-grid`: layout do hero e de cada álbum, com a capa alternando de lado.
- `11-css-nesting`: o `style.css` reescrito com CSS nesting nativo.

## Navegadores

A partir da etapa `11-css-nesting`, o `style.css` usa CSS nesting nativo, suportado no Chrome 120+, Firefox 117+ e Safari 17.2+. Em navegadores mais antigos, as regras aninhadas são ignoradas e a página perde parte do estilo.

## Créditos das capas

As capas ficam na pasta `covers/`, em baixa resolução (500 × 500 px), só para fins educacionais. Os direitos pertencem aos artistas e às gravadoras. As imagens vêm do [Cover Art Archive](https://coverartarchive.org/), via MusicBrainz.

- `hybrid-theory.jpg`: *Hybrid Theory* (2000), Linkin Park. Gravadora: Warner Bros. Records.
- `meteora.jpg`: *Meteora* (2003), Linkin Park. Gravadora: Warner Bros. Records.
- `blink-182.jpg`: *blink-182* (2003), blink-182. Gravadora: Geffen Records.
- `a-fever-you-cant-sweat-out.jpg`: *A Fever You Can’t Sweat Out* (2005), Panic! at the Disco. Gravadoras: Decaydance e Fueled by Ramen.
- `riot.jpg`: *Riot!* (2007), Paramore. Gravadora: Fueled by Ramen.
- `brand-new-eyes.jpg`: *Brand New Eyes* (2009), Paramore. Gravadora: Fueled by Ramen.
- `paramore.jpg`: *Paramore* (2013), Paramore. Gravadora: Fueled by Ramen.
- `thats-the-spirit.jpg`: *That’s the Spirit* (2015), Bring Me the Horizon. Gravadora: RCA Records (Sony Music).
## Licença

Código sob a licença MIT. Veja o arquivo [LICENSE](LICENSE).
