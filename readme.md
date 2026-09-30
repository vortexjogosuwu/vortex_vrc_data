# Como criar um repositório público no GitHub Pages

Guia rápido para criar um repositório público e hospedar arquivos usando o GitHub Pages (`.github.io`).

## 1. Criar o repositório

1. Acesse [GitHub](https://github.com/).
2. Clique em **+ → New repository**.
3. Configure:

   * **Repository name:** `vortex_vrc_data`
   * **Description:** Dados públicos para o VRChat.
   * **Visibility:** Public
   * **Add a README file:** Opcional.
4. Clique em **Create repository**.

## 2. Ativar o GitHub Pages

1. Acesse o repositório criado.
2. Entre em **Settings → Pages**.
3. Em **Build and deployment**, configure:

   * **Source:** Deploy from a branch
   * **Branch:** `main`
   * **Folder:** `/ (root)`
4. Clique em **Save**.

O GitHub publicará automaticamente os arquivos do repositório.

## 3. Adicionar arquivos

Adicione os arquivos que deseja disponibilizar publicamente.

Exemplo de estrutura:

```text
vortex_vrc_data/
├── README.md
├── index.html
├── galleries/
│   └── gallery1.json
└── images/
    └── gallery1/
        ├── image1.jpg
        └── image2.jpg
```

Para adicionar arquivos pelo GitHub:

1. Clique em **Add file → Upload files**.
2. Selecione os arquivos.
3. Clique em **Commit changes**.

## 4. Acessar os arquivos

O endereço do GitHub Pages segue este formato:

```text
https://USUARIO.github.io/REPOSITORIO/
```

Exemplo:

**Página principal:**

```text
https://vortexjogosuwu.github.io/vortex_vrc_data/
```

**Arquivo JSON:**

```text
https://vortexjogosuwu.github.io/vortex_vrc_data/galleries/gallery1.json
```

**Imagem:**

```text
https://vortexjogosuwu.github.io/vortex_vrc_data/images/gallery1/image1.jpg
```

## 5. Atualizar os arquivos

Sempre que adicionar, modificar ou excluir arquivos, faça um novo commit.

O GitHub Pages publicará as alterações automaticamente. A atualização pode levar alguns minutos.

## 6. Observações importantes

* O repositório precisa ser público para utilizar o GitHub Pages gratuitamente.
* Os arquivos publicados podem ser acessados por qualquer pessoa.
* O GitHub Pages suporta arquivos estáticos, como HTML, CSS, JavaScript, JSON e imagens.
* Não executa códigos Python ou PHP no servidor.
* Não funciona como banco de dados ou API para salvar informações.
* Os arquivos são disponibilizados por HTTPS, o que permite seu uso em aplicações compatíveis com URLs seguras, como o VRChat.

## Documentação oficial

[GitHub Pages — Documentação](https://docs.github.com/en/pages)
