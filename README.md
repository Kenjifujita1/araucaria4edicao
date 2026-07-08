# Araucária — Festival de Churrasco · 4ª Edição · Pitanga-PR

Site de captura + proposta comercial do **Araucária Festival de Churrasco 2026**.
Venda de ingressos pelo WhatsApp **(44) 99928-3900**.

## Estrutura

- **`site/`** — Página de captura (é o que vai para o ar). One-page com vídeo,
  galeria, números animados, carrossel de patrocinadores e CTA de WhatsApp.
- **`proposta/`** — Proposta comercial da cobertura audiovisual (documento
  interno para o cliente; **não** é publicado).

## Publicar o site na Vercel (grátis)

1. Acesse **vercel.com** e faça login com o **GitHub**.
2. **Add New… → Project** e importe o repositório **`araucaria4edicao`**.
3. Em **Root Directory**, clique em **Edit** e selecione a pasta **`site`**.
   *(passo importante — é o que faz a Vercel servir o site certo)*
4. Clique em **Deploy**.

Em ~1 minuto o site fica no ar num link tipo `araucaria4edicao.vercel.app`,
pronto para mandar no WhatsApp. Depois dá para conectar um domínio próprio.

## Atualizar o site

Qualquer alteração enviada para a branch `main` no GitHub é publicada
automaticamente pela Vercel.
