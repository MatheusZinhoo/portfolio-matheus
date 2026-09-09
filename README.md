# Portfólio — Matheus Cardozo e Silva

Portfólio pessoal e três projetos de demonstração. HTML, CSS e JavaScript puro:
sem framework, sem build, sem dependência além das fontes do Google Fonts.
Qualquer arquivo abre com dois cliques.

```
.
├─ index.html              portfólio
├─ projetos/
│  ├─ cafeteria.html       Torra Nove — site de cafeteria
│  ├─ painel.html          Corte Reto — painel de gestão de barbearia
│  └─ bot.html             Agenda no Zap — bot de WhatsApp (interativo)
└─ README.md
```

## Publicar no GitHub Pages

Com o repositório já no GitHub:

1. Abra **Settings → Pages** no repositório.
2. Em *Source*, escolha **Deploy from a branch**.
3. Branch: `main`, pasta: `/ (root)`. Salve.
4. Em um ou dois minutos o site sai em
   `https://matheuszinhoo.github.io/portfolio-matheus/`.

Para atualizar depois, basta editar os arquivos e:

```powershell
git add .
git commit -m "ajusta contato"
git push
```

## O que trocar antes de divulgar

Tudo em `index.html`:

| Procurar por | Situação |
|---|---|
| `5547996559713` (2x) | preenchido |
| `(47) 99655-9713` | preenchido |
| `MatheusZinhoo` (2x) | preenchido |
| `Jaraguá do Sul, SC` (3x) | preenchido |
| `seu-usuario` (2x) | **pendente** — endereço do seu LinkedIn |

Revise também:

- **Ferramentas** (seção `processo.md`) — deixe só o que você realmente usa.
  Listar coisa que não domina é o jeito mais rápido de queimar uma reunião.
- **Prazos** nas dúvidas — ajuste para a sua realidade.
- **Ficha técnica** (seção `sobre.md`) — suporte, formato de entrega, status.

Nenhuma página fala de preço. O assunto fica para a conversa.

## Sobre os projetos de demonstração

Marcas fictícias (Torra Nove, Corte Reto), e está escrito na própria página que são
demonstrações. Conforme fechar trabalhos reais, substitua um a um — o cartão em
`index.html` é um bloco `<a class="repo">`, é só trocar título, descrição,
miniatura e link.

## Domínio próprio

O GitHub Pages aceita domínio personalizado de graça. Compre em
[registro.br](https://registro.br) (`.com.br` sai por volta de R$ 40/ano) e
configure em **Settings → Pages → Custom domain**.
