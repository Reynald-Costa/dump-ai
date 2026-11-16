# Dump.ai

Prova de conceito: o usuário escolhe as fotos que separou para o Instagram e a página indica quais postar, com uma nota de 0 a 100 e o motivo de cada nota.

## Como funciona

- Tudo roda no navegador. As fotos não são enviadas para nenhum servidor e somem ao fechar a página.
- A nota combina sete critérios técnicos: nitidez, exposição, contraste, cor, composição, formato e resolução.
- Fotos muito parecidas são agrupadas, e só a de nota maior é recomendada.
- A prévia do perfil mostra a grade em 3:4 com as fotos escolhidas.

Esta versão avalia só a qualidade técnica da foto, não o conteúdo. A próxima etapa é usar um modelo de visão para avaliar assunto, emoção e aderência à marca.

## Publicar no GitHub Pages

1. Envie este repositório para o GitHub (repositório público no plano gratuito).
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. O endereço fica em `https://<usuario>.github.io/<repositorio>/`.

## Rodar localmente

Abra o `index.html` no navegador. Não precisa de servidor nem de instalação.
