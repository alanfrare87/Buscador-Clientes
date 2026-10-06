# Buscador de Clientes

Aplicativo web estático para consultar a base de clientes por CNPJ, código, razão social e nome fantasia, com filtros por GV, SV, RV, canal e cluster.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie `index.html` e a pasta `data/` (com `clientes.json`).
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)`.
6. Salve. O GitHub fornecerá o link do site.

## Importante
Esta versão contém os dados da planilha dentro de `data/clientes.json`. Se o repositório for público, qualquer pessoa poderá baixar esses dados. Para dados comerciais ou pessoais, use um repositório privado e/ou uma aplicação com autenticação e banco de dados protegido.
