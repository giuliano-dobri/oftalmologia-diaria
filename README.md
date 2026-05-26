# Editorial Diário de Nutrologia

Site automatizado com briefing diário e aulas-pílula em nutrologia, geradas com apoio de inteligência artificial.

🔗 Site no ar: https://giuliano-dobri.github.io/nutrologia-diaria/

---

## Como funciona

Uma rotina automatizada (Claude Code Routine) é executada todos os dias às 08h (BRT) e:

1. Pesquisa fontes selecionadas das últimas 24h em nutrologia
2. Gera um briefing matinal com as atualizações
3. Gera uma aula-pílula sobre um tema específico (versão curta + versão longa)
4. Commita os posts neste repositório
5. Envia o briefing por e-mail
6. O site é reconstruído automaticamente pelo GitHub Pages

---

## Estrutura do site

```
/                  → Homepage (posts recentes)
/aulas/            → Listagem cronológica de todas as aulas
/temas/            → Aulas organizadas por tema
/sobre/            → Sobre o projeto
/AAAA/MM/DD/<slug>/  → URL individual de cada post
```

---

## Stack técnica

- **Jekyll** com tema [minimal-mistakes](https://github.com/mmistakes/minimal-mistakes) (skin `air`)
- **GitHub Pages** para hospedagem
- **Claude Code Routine** para geração automatizada de conteúdo
- **Resend** para envio dos e-mails de briefing

---

## Replicar este projeto para outra especialidade

Para criar um site similar (ex: oftalmologia), siga estes passos:

1. **Criar repositório novo** público no GitHub (ex: `oftalmologia-diaria`)
2. **Ativar GitHub Pages**: Settings → Pages → Source: Deploy from a branch → main → /(root)
3. **Habilitar permissões de Actions**: Settings → Actions → General → Workflow permissions: "Read and write permissions"
4. **Copiar todos os arquivos deste repo** para o novo repo
5. **Editar `_config.yml`** — alterar campos marcados com `[REPLICAR]`:
   - `title`, `subtitle`, `description`
   - `url`, `baseurl`, `repository`
6. **Editar este `README.md`** com nome da nova especialidade
7. **Criar Routine no Claude Code** apontando para o novo repositório, adaptando o prompt

---

## Avisos

⚠️ **Conteúdo gerado por inteligência artificial, para fins educativos.**
Este material não substitui consulta a literatura primária nem julgamento clínico individualizado.
