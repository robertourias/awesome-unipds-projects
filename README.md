# Awesome UNIPDS Projects 🎓

Uma lista curada de projetos originais criados por alunos do curso de pós-graduação **[UNIPDS Engenharia de Software com IA Aplicada](https://unipds.com.br/org-erick-wendel/?utm_source=awesomeunipdsprojects&utm_medium=github&utm_term=&utm_content=awesomeunipdsprojects)**.

> [!IMPORTANT]
> Esta é uma vitrine de **trabalhos originais dos alunos**. Projetos inspirados nos conceitos do curso são bem-vindos, mas devem ser criações totalmente novas — não cópias de exercícios demonstrados em aula.

Quer adicionar o seu? Veja [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Índice

- [Legenda](#legenda)
- [Projetos](#projetos)
  - [🔌 Servidores MCP](#-servidores-mcp)
  - [🤖 Agentes de IA](#-agentes-de-ia)
  - [🌐 Web Apps & Games](#-web-apps--games)
  - [⚡ Integrações & Automações](#-integrações--automações)
  - [🛠️ Ferramentas & Utilitários](#-ferramentas--utilitários)
  - [📦 Outros](#-outros)

---

## Legenda

**Linguagem / runtime**
- `🐍` – Python
- `📇` – TypeScript / JavaScript
- `🏎️` – Go
- `🦀` – Rust
- `#️⃣` – C#
- `☕` – Java

**Escopo**
- `☁️` – Consome APIs externas / na nuvem
- `🏠` – Executa totalmente de forma local
- `🔗` – Integra dois ou mais serviços

---

## Projetos

> [!NOTE]
> Os projetos estão listados em ordem alfabética dentro de cada categoria.

### 🔌 Servidores MCP

Servidores MCP que expandem assistentes de IA com novas ferramentas e capacidades.

<!-- Add your project here. See CONTRIBUTING.md for the entry format. -->
- [alvesribeirof/architecture-analysis-mcp](https://github.com/alvesribeirof/architecture-analysis-mcp) `#️⃣` `🔗` – Servidor MCP para análise arquitetural de código com foco em princípios SOLID, Padrões de Projeto e feedback imediato ao desenvolvedor. **by [@alvesribeirof](https://github.com/alvesribeirof)**

- [s3b4hjr/philosophy-mcp](https://github.com/s3b4hjr/philosophy-mcp) `🐍` `☁️` - Servidor MCP para um corpus filosófico multilíngue — glossário, sínteses, perfis de pensadores e artigos em português, inglês e espanhol. **by [@s3b4hjr](https://github.com/s3b4hjr)**

---

### 🤖 Agentes de IA

Agentes autônomos que executam tarefas em múltiplas etapas usando LLMs.

- [SyanCS/pokemon-training-center](https://github.com/SyanCS/pokemon-training-center) `📇` `🔗` – Assistente de agendamento com IA que classifica intenções em linguagem natural via LangGraph + OpenRouter para gerenciar matrículas, reservas e recomendações de aulas Pokémon. **by [@SyanCS](https://github.com/SyanCS)**
- [SyanCS/alvorada_real_estate](https://github.com/SyanCS/alvorada_real_estate) `📇` `🔗` – Plataforma de pesquisa imobiliária com três pipelines LangGraph para extração de características a partir de anotações, ranqueamento de imóveis em linguagem natural e busca por similaridade com Neo4j GraphRAG. **by [@SyanCS](https://github.com/SyanCS)**

---

### 🌐 Web Apps & Games

Aplicações web e experiências no navegador com aprendizado de máquina ou IA.

- [Biaginibe/ML-nextjs-board-game](https://github.com/Biaginibe/ML-nextjs-board-game) `📇` `🏠` – Sistema de recomendação de jogos de tabuleiro usando TensorFlow.js para aprendizado de máquina no lado do servidor com Next.js. **by [@Biaginibe](https://github.com/Biaginibe)**
- [DiogoOrdine/game-eclipse-ai-agent](https://github.com/DiogoOrdine/game-eclipse-ai-agent) `📇` `🏠` – Adaptação do jogo Eclipse integrando uma rede neural YOLOv5n executando com TensorFlow.js dentro de um Web Worker. **by [@DiogoOrdine](https://github.com/DiogoOrdine)**
- [Douglas-sm/game-flapbird](https://github.com/Douglas-sm/game-flapbird) `📇` `🏠` – Jogo Flappy Bird em pixel art com uma IA que se treina no próprio navegador usando Canvas 2D e TensorFlow.js. **by [@Douglas-sm](https://github.com/Douglas-sm)**
- [me-wsantos/classificacao-tensorflowjs](https://github.com/me-wsantos/AI-Engineer-UNIPDS/tree/75e2183198175ac8610399b1df2752fdef710f42/001-classificacao-tensorflowjs) `📇` `🏠` – Rede neural classificadora de classe social treinada e executada inteiramente no navegador com TensorFlow.js, prevendo faixas socioeconômicas (A–E) com base em atributos fornecidos pelo usuário. [🌐 Demo ao vivo](https://ai-engineer-unipds.onrender.com/) **by [@me-wsantos](https://github.com/me-wsantos)**
- [rdiegoss/scout](https://github.com/rdiegoss/scout) `📇` `🏠` – PWA com IA para descoberta de serviços locais que utiliza embeddings TensorFlow.js no dispositivo para ranquear prestadores próximos (eletricistas, encanadores, mecânicos) por similaridade semântica, proximidade geográfica e compatibilidade comportamental. **by [@rdiegoss](https://github.com/rdiegoss)**
- [SyanCS/the-speakeasy-chatbot](https://github.com/SyanCS/the-speakeasy-chatbot) `📇` `🏠` – Chatbot de barman dos anos 1920 que roda completamente no navegador via Gemini Nano on-device do Chrome (Prompt API) — sugestões multimodais de coquetéis, substituições, escalonamento e correções de drinques, sem backend ou chaves de API. **by [@SyanCS](https://github.com/SyanCS)**
- [SyanCS/dr_nala_breed_recommendation](https://github.com/SyanCS/dr_nala_breed_recommendation) `📇` `🏠` – App de recomendação de raças de cães orientado por IA que treina um classificador de compatibilidade com TensorFlow, persiste artefatos do modelo no PostgreSQL e serve recomendações ranqueadas a partir de um web worker do navegador com fallback baseado em regras. **by [@SyanCS](https://github.com/SyanCS)**
- [thabata-marchi/portuguese-alphabet-game](https://github.com/thabata-marchi/portuguese-alphabet-game) `📇` `🏠` – Jogo educacional de pré-alfabetização para crianças que ensina o alfabeto português usando reconhecimento de voz e IA adaptativa. **by [@thabata-marchi](https://github.com/thabata-marchi)**

---

### ⚡ Integrações & Automações

Projetos que conectam serviços, automatizam fluxos de trabalho ou reagem a eventos.

- [mjunior/whatsapp-ai-pix-agent](https://github.com/mjunior/whatsapp-ai-pix-agent) `📇` `🔗` – Um agente de IA que cobra minha esposa via PIX quando ela pede favores pelo WhatsApp. **by [@mjunior](https://github.com/mjunior)**

- [iran-gregorio/project-aegis](https://github.com/iran-gregorio/project-aegis) `📇` `🔗` - Um chatbot inteligente projetado para analisar sentimento e lidar com agressividade no WhatsApp. **by [@iran-gregorio](https://github.com/iran-gregorio)**

---

### 🛠️ Ferramentas & Utilitários

CLIs, bibliotecas, auxiliares e ferramentas para desenvolvedores com IA.

<!-- Add your project here. See CONTRIBUTING.md for the entry format. -->
- [ElizioMartins/projeto-00-ibge-tensores](https://github.com/ElizioMartins/projeto-00-ibge-tensores) `📇` `🏠` – Preditor populacional usando dados demográficos do IBGE e Aprendizado de Máquina. **by [@ElizioMartins](https://github.com/ElizioMartins)**
---

### 📦 Outros

Tudo aquilo que não se encaixa nas categorias acima.

<!-- Add your project here. See CONTRIBUTING.md for the entry format. -->
*Nenhum projeto ainda — seja o primeiro a enviar um!*

---

## Contribuindo

Veja [CONTRIBUTING.md](CONTRIBUTING.md) para as diretrizes de submissão.  
Dúvidas? Abra uma issue ou entre em contato pelo canal da comunidade do curso.

## Agradecimentos

Um agradecimento especial a todos os nossos incríveis colaboradores 💚🇧🇷

<a href="https://github.com/unipds-engenharia-de-ia-aplicada/awesome-unipds-projects/graphs/contributors"><img src="https://readme-contribs.as93.net/contributors/unipds-engenharia-de-ia-aplicada/awesome-unipds-projects" /></a>
