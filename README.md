# scorekeeper-site

Site estático do app **Score Keeper**, publicado pelo GitHub Pages em
`https://scorekeeper.borzanti.com`.

| Caminho | Conteúdo |
| --- | --- |
| `index.html` | Redireciona para a ficha do app na Google Play |
| `privacidade/index.html` | Política de privacidade em PT, EN e ES (link usado na Play Console) |
| `CNAME` | Domínio próprio do GitHub Pages |

A fonte fica no repositório do app, em `site/`. Edite lá e copie para cá.

## Publicação

1. **GitHub → Settings → Pages:** fonte **Deploy from a branch**, branch `main`, pasta `/ (root)`.
2. **DNS do domínio `borzanti.com`:** registro `CNAME` de `scorekeeper` apontando para `<usuário>.github.io`.
3. Quando o certificado sair, marque **Enforce HTTPS**.
4. Confira `https://scorekeeper.borzanti.com/privacidade/` numa janela anônima antes de colar o link na Play Console.
