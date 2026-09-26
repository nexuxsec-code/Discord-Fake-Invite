# Convite PureBlox #2

Página de convite estilo Discord para o servidor PureBlox #2.

## Estrutura

```
convite-pureblox/
├── index.html          # Página do convite (HTML, CSS e JS)
└── assets/
    └── pureblox-logo.png   # Logo do servidor usada no avatar
```

## Como usar

Abra o arquivo `index.html` diretamente no navegador (duplo clique) para visualizar o convite.

## Edição

- Nome do servidor, contadores e textos: procure pelas tags `<h1 class="invite-title">`, `#onlineCount` e `#totalCount` dentro do `index.html`.
- Cores e estilo: todas as variáveis de cor estão no bloco `:root` no topo do `<style>`.
- Logo: substitua o arquivo `assets/pureblox-logo.png` por outra imagem com o mesmo nome, ou atualize o caminho na tag `<img>` do avatar.
- Altere o endereço para usa webhook do discord nas linhas de index.html
