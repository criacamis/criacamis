# Publicar no GitHub Pages (uma vez só)

1. Crie um repositório público (ex: `criacamis`).
2. **Add file → Upload files** → envie `index.html` e `dados.json` → **Commit**.
3. **Settings → Pages** → Source: *Deploy from a branch* → `main` / `root` → **Save**.
4. Site no ar em `https://SEU-USUARIO.github.io/criacamis/`.

# Criar o token (uma vez só)
GitHub → foto → **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**
- Repository access: *Only select repositories* → `criacamis`
- Permissions → Repository → **Contents: Read and write**
- Expiração: a que preferir (ex: 1 ano). Copie o token.

# Editar e publicar (dia a dia)
1. Abra `https://SEU-USUARIO.github.io/criacamis/#admin` uma vez. Depois disso, o botão **⚙ editar site** aparece no rodapé só no seu navegador (visitantes não veem).
2. Na primeira vez: **Conexão GitHub** → cole o token (usuário e repositório já vêm preenchidos).
3. Edite trabalhos, textos, fotos, feedbacks e Instagram → **publicar alterações** → **ver site no ar**.

As imagens enviadas vão para a pasta `imagens/` do repositório automaticamente.
