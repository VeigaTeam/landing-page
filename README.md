# CT Veiga Team — Landing page

Site de uma página da academia de artes marciais CT Veiga Team (Paulínia/SP). HTML, CSS e JavaScript puros, sem build e sem dependências.

## Arquivos

- `index.html` — todo o conteúdo (textos, horários, depoimentos, contatos)
- `styles.css` — visual (cores do logo em `:root`)
- `script.js` — menu mobile, destaque do dia atual nos horários, ano no rodapé
- `assets/logo.jpg` — logo usado no site; `assets/logo-original.jpg` é o arquivo original em alta resolução
- `assets/favicon.png` — ícone da aba

## Como editar

- **WhatsApp:** procure por `wa.me/5519993927371` no `index.html` e troque o número (55 + DDD + número).
- **Horários:** edite as linhas da tabela na seção `#horarios`. O `data-day` (0 = domingo … 6 = sábado) serve para destacar o dia de hoje.
- **Modalidades e depoimentos:** cada card é um bloco `<article>` ou `<blockquote>` na seção correspondente.
- **Cores:** variáveis `--bg`, `--red`, `--text` no topo do `styles.css`.

## Ver localmente

```bash
python3 -m http.server 8080
```

Depois abra http://localhost:8080.

## Publicar

É um site estático: basta enviar a pasta para Vercel, Netlify, GitHub Pages ou qualquer hospedagem.
