# Artes publicadas no Instagram

As imagens dos carrosséis de @meuguia.turismo, servidas por raw.githubusercontent.com.
A Graph API não aceita upload de arquivo no feed orgânico: ela baixa a imagem de uma URL
pública, e este repo é público — por isso a arte mora aqui.

**Este branch NUNCA é mergeado na main.** O workflow de deploy escuta só a main, e um push
lá reconstruiria o site do produto a cada carrossel publicado.

A fonte de verdade da arte é `meuguia-content/artes/<slug>/`, no repo meuguia-ops.
O que está aqui é espelho, escrito por scripts/conteudo/publicar-meta.mjs no momento da
publicação — só os arquivos do post que está indo ao ar.
