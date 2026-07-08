# Como publicar o site na Vercel

O site é 100% estático (HTML + fotos + vídeo). Não precisa de build. Escolha **um** dos caminhos abaixo.

> ⚠️ **Antes de publicar:** troque o número do WhatsApp no arquivo `index.html`.
> Procure a linha `var WHATSAPP = "5544900000000";` (perto do fim, dentro de `<script>`)
> e coloque o número real no formato **55 + DDD + número** (ex.: `5542999998888`).
> Aproveite e ajuste também o preço do 1º lote (`R$ 00,00`) e a data.

---

## Opção A — Arrastar e soltar (mais fácil, sem instalar nada)

1. Acesse **https://vercel.com** e crie/entre na conta (pode usar login com Google).
2. No painel, clique em **Add New… → Project → Deploy** (ou procure a opção de deploy manual).
3. **Arraste a pasta `site/` inteira** para a área de upload.
4. Aguarde alguns segundos. Pronto — a Vercel te dá um link tipo
   `https://araucaria-xxxx.vercel.app` pra você mandar no WhatsApp.

> Dica: dá pra apontar um domínio próprio depois (ex.: `araucariafestival.com.br`)
> em **Project → Settings → Domains**.

---

## Opção B — Pela linha de comando (Vercel CLI)

No terminal, dentro da pasta `site/`:

```bash
cd "site"
npx vercel          # primeira vez: faz login e pergunta as configs (pode aceitar tudo)
npx vercel --prod   # publica a versão final (produção)
```

Na primeira vez ele abre o navegador pra você logar. Depois é só repetir
`npx vercel --prod` sempre que atualizar algo.

---

## Atualizar o site depois

- **Opção A:** arraste a pasta `site/` de novo (ou reconecte via Git).
- **Opção B:** rode `npx vercel --prod` novamente.

## O que tem na pasta

```
site/
├── index.html                 ← a página (edite textos/WhatsApp aqui)
├── vercel.json                ← config de cache (não precisa mexer)
└── assets/
    ├── logo.jpg
    ├── fotos/                 ← 22 fotos otimizadas do evento 2025
    └── video/
        ├── araucaria-2025.mp4 ← aftermovie (29 MB)
        └── poster.jpg
```
