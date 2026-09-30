<div align="center">

  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=26&pause=1000&color=7C3AED&center=true&vCenter=true&width=760&lines=Transpar%C3%ADncia+pol%C3%ADtica+com+dados+p%C3%BAblicos;Engenharia+de+Software+%40+Uninter;Full-stack+%E2%86%92+Node+%C2%B7+TypeScript+%C2%B7+React" alt="Adriano Anthony" />

  <br/>

  <a href="https://como-votei.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Como%20Votei-no%20ar-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="Como Votei" />
  </a>
  <a href="mailto:adrianoanthonymma16@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/E-mail-140F24?style=for-the-badge&logo=gmail&logoColor=7C3AED" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/adriano-anthony-202951358" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>

</div>

<br/>

---

## Sobre

Construo ferramentas que pegam **dados públicos do Congresso brasileiro** e respondem
uma pergunta que qualquer cidadão faz, mas quase ninguém consegue responder sozinho:
*como esse parlamentar realmente votou nos últimos anos?*

O [Como Votei](https://como-votei.vercel.app) faz isso com dados de 513 deputados e
81 senadores — votações nominais, discursos e proposições — sincronizados diariamente
das APIs da Câmara e do Senado. Nenhuma tentativa de acusar ninguém: os padrões são
mostrados com os dados à vista, para quem quiser conferir.

## Projeto em destaque

### 🏛️ [Como Votei](https://github.com/adrianoanthonymma16-boop/como-votei) — [ver no ar](https://como-votei.vercel.app)

Transparência legislativa: como deputados e senadores votam, falam e aprovam no Congresso.

**Next.js 14** (App Router) · **TypeScript** · **Prisma** · **PostgreSQL** (Neon) · **Tailwind** · **Zod**

- **11 endpoints de API** com ISR e cache de 1h; schema populado com 513 deputados e 81 senadores
- **Sincronização automática**: GitHub Actions diário (Câmara 03:00 UTC / Senado 04:00 UTC) + Vercel Cron incremental
- **Testes**: 6 suítes Jest (regras de negócio, heurísticas, queries) + Playwright E2E
- **Acessibilidade**: WCAG AA, navegação por teclado, ARIA labels, `axe-core` sem violações críticas
- **Alinhamento partidário** calculado a partir das votações nominais, agregado por parlamentar e por partido
- **Logs estruturados** (pino) e métrica de dado desatualizado por fonte
- Deploy na Vercel, 100% em free tier

## Antes do front-end

### 📄 [AutoDoc](https://github.com/adrianoanthonymma16-boop/autodoc)

Gerador automático de documentos ODT/DOCX com OCR. Python 3.10, CustomTkinter, Tesseract, `pytest`, MIT, 1★.

É daqui que vem meu interesse em automatizar trabalho manual: você desenha um retângulo no
documento, aponta o campo, e o sistema preenche o resto. **16 bugs corrigidos** até a v4.0,
com arquitetura separada em `services/` / `ui/` e duas interfaces (ttkbootstrap e CustomTkinter).
Roda 100% offline — os dados nunca saem da máquina.

> O [Seu Político](https://github.com/adrianoanthonymma16-boop/seu-politico) foi o começo
> dessa mesma ideia: análise de gastos públicos em JavaScript puro. Descontinuado por minha
> parte — o Como Votei é a versão atual e mais completa. O repositório continua lá, arquivado.

## Agora

- **Curso**: Engenharia de Software @ Uninter
- **Curso DIO**: foco em desenvolvimento web full-stack — Node.js, TypeScript, HTML, CSS e React
- **Metodologia**: [@opencode-agents](https://github.com/adrianoanthonymma16-boop/opencode-agents) — meu `AGENTS.md` e 23 skills de engenharia (Python, SQL, reaproveitamento) rodando comigo no dia a dia

## Stack

<div align="center">

**Frontend**  `React` `Next.js` `TypeScript` `Tailwind CSS` `HTML5`

**Backend**  `Node.js` `Python` `SQL` `REST` `Zod`

**Dados**  `PostgreSQL` `Prisma` `SQLite` `GitHub Actions` `Vercel`

**Testes e qualidade**  `Jest` `Playwright` `pytest` `Ruff`

**Ferramentas**  `Git` `GitHub` `Vercel` `Linux`

</div>

## Contato

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-in%2Fadriano--anthony--202951358-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adriano-anthony-202951358)
[![Gmail](https://img.shields.io/badge/adrianoanthonymma16@gmail.com-140F24?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adrianoanthonymma16@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-adrianoanthonymma16--boop-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adrianoanthonymma16-boop)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5593981275587)

</div>

---

<div align="center">

### ⚡ // Sobre.js

```javascript
/**
 * @file sobre.js
 * @author Adriano Anthony
 */

const eu = {
  identidade: {
    nome: "Adriano Anthony",
    local: "Santarém — PA",
    contexto: "Militar"
  },

  formação: {
    curso: "Engenharia de Software",
    instituição: "Uninter",
    certificações: "DIO — desenvolvimento web full-stack"
  },

  oQueEuFaço: {
    entrega: "transparência política com dados públicos",
    direção: "desenvolvimento web full-stack",
    stack: ["Node.js", "TypeScript", "React", "HTML", "CSS"]
  },

  valores: ["Disciplina", "Curiosidade", "Propósito"]
};
```

</div>
