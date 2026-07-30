# meuguia-blog

Conteúdo do blog do meuguia (posts em Markdown). Push na main dispara o rebuild do site via Deploy Hook.

## `title` e `seoTitle`

`title` é o H1 do post — pode ser longo e rico, na página tem espaço.

`seoTitle` é opcional e serve para o `<title>` da aba, o resultado do Google e o card
social. Use quando o H1 passar do que o Google mostra: o site acrescenta ` | meuguia`
e o total precisa caber em 60 caracteres. O `blog:lint` reprova o build se passar, e
exige que a `keyword` apareça também no `seoTitle` — é ele que vai para a busca.

```yaml
title: "Madri, melhor destino da Europa em 2026: o que vender além do Prado"
seoTitle: "Madri: melhor destino da Europa em 2026"
```
