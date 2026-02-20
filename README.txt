CALCULADORA RP (SITE) — COMO USAR

✅ O que é
- Um mini site estático (HTML/CSS/JS) que calcula totais a partir de um catálogo (catalog.json).
- Tem modo “somente valor” e botão “Gerar nota” para copiar e enviar no Discord.

⚠️ Importante
- Este projeto é um template genérico para itens de RP. Use de forma responsável e dentro das regras do seu servidor.

1) EDITAR OS ITENS E RECEITAS
Abra o arquivo: catalog.json

Cada item tem:
- id: identificador único (sem espaços)
- name: nome que aparece na tabela
- category: categoria (opcional)
- value_k: valor em "k"
- recipe: materiais por 1 unidade (molas, canos, gatilhos, pratas, bronzes)

Exemplo:
{
  "id": "item_x",
  "name": "Nome do Item",
  "category": "Categoria",
  "value_k": 405,
  "recipe": { "molas": 22, "canos": 20, "gatilhos": 8, "pratas": 48, "bronzes": 0 }
}

2) COLOCAR SEU LOGO
- Substitua o arquivo: assets/logo.png

3) HOSPEDAR (RECOMENDADO)
Como o site carrega catalog.json via fetch, ele precisa estar em um servidor.

Opções grátis:
A) GitHub Pages
B) Netlify (deploy manual arrastando a pasta)

4) USO NO DISCORD
- Fixe o link do site em um canal.
- Clique em “Gerar nota” e copie/cole no chat.

