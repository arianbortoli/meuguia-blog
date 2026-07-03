---
title: "Teste de publicação automática do blog"
slug: teste-publicacao-automatica-do-blog
publishedAt: "2026-07-03"
category: bastidores
tags:
  - teste
heroImage: "https://images.unsplash.com/photo-1499750310107-5fef28a66643?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=1600"
heroImageAlt: "Mesa com notebook aberto, simbolizando a escrita de um post de blog"
excerpt: "Post temporário para validar de ponta a ponta o fluxo de publicação automática do blog a partir do repositório de conteúdo separado."
metaDescription: "Post temporário para validar a publicação automática do blog do meuguia: um push no repositório de conteúdo dispara o rebuild do site em minutos."
keyword: "publicação automática do blog"
---

Este é um post de teste, temporário e descartável, criado só para validar a publicação automática do blog a partir do repositório de conteúdo separado (`meuguia-blog`). Assim que confirmarmos que ele aparece no ar, será removido.

## Como funciona a publicação automática do blog

O fluxo é simples: um `.md` novo recebe push na `main` do repositório de conteúdo, um GitHub Action dispara o Deploy Hook da Vercel, o site do produto reconstrói e o post fica visível em minutos — sem nenhum commit no repositório do produto.

Se você está lendo isto no ar, o teste funcionou.
