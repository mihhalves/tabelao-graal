# Tabelão Graal

Página do Tabelão Graal: empreendimentos, valores, incentivos, comissão e contatos da coordenação.

## Arquivos

| Arquivo | O que é |
|---|---|
| `index.html` | A página (layout). Não precisa mexer. |
| `data.json` | Todos os dados do tabelão (gerado a partir da planilha do Google). |
| `tabelao-graal.pdf` | O PDF do botão "Baixar PDF". |
| `logos/` | Logos da Graal, da Move House e de cada empreendimento. |
| `.nojekyll` | Arquivo vazio que faz o GitHub Pages publicar os arquivos como estão. Não apague. |

## Publicar no GitHub Pages (uma vez só)

1. Entre em github.com e crie um repositório novo (botão **New**), por exemplo `tabelao-graal`, marcado como **Public**.
2. No repositório, clique em **Add file → Upload files**, arraste **todo o conteúdo desta pasta** (incluindo a pasta `logos`) e clique em **Commit changes**.
3. Vá em **Settings → Pages**. Em **Source**, escolha **Deploy from a branch**; em **Branch**, escolha **main** e a pasta **/ (root)**; clique em **Save**.
4. Em 1 a 2 minutos o site fica no ar em `https://SEU-USUARIO.github.io/tabelao-graal/`.

## Usar o domínio fracaparcerias.com.br (opcional)

1. Em **Settings → Pages → Custom domain**, digite o domínio (por exemplo `tabelao.fracaparcerias.com.br`) e salve.
2. No painel onde o domínio está registrado (Registro.br ou a hospedagem), crie um registro **CNAME** de `tabelao` apontando para `SEU-USUARIO.github.io`.
3. Depois que o domínio funcionar, marque **Enforce HTTPS** em Settings → Pages.

## Atualizar o tabelão

1. Atualize a planilha do Google e peça ao Claude: "atualiza o tabelão".
2. O Claude envia os arquivos novos (`data.json` e `tabelao-graal.pdf`, e logos novos quando houver produto novo).
3. No repositório, clique em **Add file → Upload files**, arraste os arquivos novos (eles substituem os antigos com o mesmo nome) e clique em **Commit changes**. O site atualiza em 1 a 2 minutos.
