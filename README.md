# Safari em Realidade Aumentada — aula de 30 minutos

Projeto WebAR com quatro animais estilizados em 3D: leão, elefante, tubarão e águia.

## Arquivos

- `index.html` — experiência de realidade aumentada.
- `cartoes.html` — cartões para imprimir; gera QR Codes automaticamente depois que o projeto estiver hospedado.
- `preview.html` — atalhos para testar cada animal.

## Como colocar no ar

A câmera do navegador exige uma origem segura. Publique a pasta em um serviço HTTPS, como GitHub Pages, Netlify ou outro servidor HTTPS.

Depois:
1. Abra `cartoes.html` usando o endereço publicado.
2. Imprima os quatro cartões.
3. No celular, escaneie o QR Code do animal.
4. Permita o acesso à câmera.
5. Aponte para o marcador preto do cartão.
6. O animal 3D aparecerá preso ao marcador.

## Aula sugerida — 30 minutos

- 0–5 min: demonstração do professor.
- 5–20 min: grupos recebem cartões diferentes e exploram os animais.
- 20–25 min: trocam os cartões entre si.
- 25–30 min: discussão: como o celular sabe onde colocar o objeto virtual?

## Observações

- O projeto usa A-Frame e AR.js carregados pela internet.
- Os animais são construídos com formas geométricas 3D dentro do próprio HTML.
- Boa iluminação e o marcador impresso sem reflexos melhoram o rastreamento.
- Se o marcador estiver pequeno na câmera, aproxime o celular.


## GitHub Pages

Este pacote já inclui `.github/workflows/pages.yml`.

Depois de criar um repositório público vazio no GitHub:

1. Envie todos os arquivos desta pasta para a branch `main`.
2. Vá em **Settings > Pages**.
3. Em **Build and deployment > Source**, selecione **GitHub Actions**.
4. O workflow `Deploy GitHub Pages` fará a publicação.
5. A URL ficará no formato:
   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

Depois de publicado, abra `cartoes.html` pela URL do GitHub Pages e imprima os cartões. Os QR Codes serão gerados com a URL correta da publicação.
