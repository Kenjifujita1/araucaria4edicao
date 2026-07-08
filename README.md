# Araucária — Festival de Churrasco · 4ª Edição · Pitanga-PR

Site de captura do **Araucária Festival de Churrasco 2026**.
Venda de ingressos pelo WhatsApp **(44) 99928-3900**.

## Estrutura

- **`index.html` + `assets/`** — o site (fica na **raiz** do repositório, então a
  Vercel publica sem precisar de nenhuma configuração especial).
- **`proposta/`** — proposta comercial da cobertura audiovisual (documento
  interno; não é publicado).

## Publicar na Vercel (grátis)

1. Acesse **vercel.com** e faça login com o **GitHub**.
2. **Add New… → Project** e importe **`araucaria4edicao`**.
3. **Não precisa mexer em Root Directory** — deixe em branco/padrão.
4. Clique em **Deploy**.

> Se você já tinha um projeto e definiu **Root Directory = `site`**, agora
> **apague esse valor** (deixe em branco), porque o site foi movido para a raiz.

Em ~1 minuto o site fica no ar. Qualquer mudança enviada para a branch `main`
é republicada automaticamente.
