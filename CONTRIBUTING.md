# Contribuindo — Como Enviar Seu Projeto

## Requisitos

- O projeto deve ser **trabalho original seu**.
- Pode ser inspirado no material do curso, mas **não pode ser uma cópia de um exercício ou demonstração de aula**.
- Deve estar em um **repositório público no GitHub**.
- O repositório deve incluir um `README.md` descrevendo o que o projeto faz e como executá-lo.
- O projeto deve ser funcional (não precisa estar pronto para produção, mas deve rodar).

## Passos

1. Faça um **Fork** deste repositório.
2. Adicione seu projeto na categoria correta no `README.md`, seguindo o formato de entrada abaixo.
3. Abra um **Pull Request** com o título: `[Project] Your Project Name – Your GitHub Username`.
4. Aguarde a revisão — um mantenedor verificará a submissão e fará o merge assim que ela atender aos requisitos.

> [!TIP]
> Não sabe qual categoria se encaixa no seu projeto? Escolha a mais próxima ou use **Other**. Os mantenedores podem sugerir uma melhor opção durante a revisão.

---

## Formato de Entrada

Adicione seu projeto na seção relevante do `README.md` usando este formato:

```markdown
- [your-username/repo-name](https://github.com/your-username/repo-name) `LANG` `SCOPE` – One sentence describing what the project does. **by [@your-username](https://github.com/your-username)**
```

**Exemplo:**

```markdown
- [jsilva/weather-mcp](https://github.com/jsilva/weather-mcp) `📇` `☁️` – MCP server that fetches real-time weather data and answers natural language queries. **by [@jsilva](https://github.com/jsilva)**
```

**Badges de linguagem / runtime:**

| Badge | Significado |
|-------|-------------|
| `🐍` | Python |
| `📇` | TypeScript / JavaScript |
| `🏎️` | Go |
| `🦀` | Rust |
| `#️⃣` | C# |
| `☕` | Java |

**Badges de escopo:**

| Badge | Significado |
|-------|-------------|
| `☁️` | Consome APIs externas / na nuvem |
| `🏠` | Executa totalmente de forma local |
| `🔗` | Integra dois ou mais serviços |

---

## Template de Descrição do PR

Copie e preencha o seguinte ao abrir seu Pull Request:

```markdown
## Project Submission

**Project name:** Your Project Name
**GitHub repo:** https://github.com/your-username/your-repo
**Short description:** One sentence explaining what your project does.
**Category:** MCP Servers | AI Agents | Integrations & Automations | Web Apps & Games | Tools & Utilities | Other
**Stack:** e.g. TypeScript, TensorFlow.js, Next.js

## What makes it original?
<!-- Explain how this project goes beyond the course material. What's your own idea or twist? -->

## Checklist

- [ ] The project is my own original work
- [ ] It is NOT a copy of a class exercise or demo
- [ ] The repository is public and has a README with setup instructions
- [ ] I followed the entry format described in this guide
```
