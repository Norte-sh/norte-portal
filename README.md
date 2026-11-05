# norte-portal

Site do NORTE: reúne as ferramentas GNSS, as métricas ionosféricas e troposféricas, a previsão de ROTI e resultados de outros projetos numa navegação só.

| | |
| --- | --- |
| Responsável | time `web` |
| Publicado em | norte-sh.com.br (a definir: Vercel hoje, AWS Amplify quando a conta sair) |
| Situação | repositório novo; recebe o código do site de ferramentas (projetonorte.vercel.app) e, depois, o site de previsão |

## Rodar localmente

```bash
cp .env.example .env.local   # preencher
npm install
npm run dev
```

## Publicação

Merge na `main` publica sozinho. Nada vai para a `main` sem pull request, CI verde e uma aprovação.

## Pastas

- `docs/`: decisões e funcionamento do site
- `.github/workflows/`: CI (segredos, lint e build)
