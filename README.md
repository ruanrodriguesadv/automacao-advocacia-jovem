# automacao-advogado-hacker

Lista de ferramentas open source para advocacia, consulta de processos, automação e IA. Apresentada no evento da Jovem Advocacia de Juazeiro/BA.

# 🛠️ Ferramentas Open Source para Advogados

Lista de ferramentas gratuitas e de código aberto, separadas para quem assistiu à palestra **"Automação para quem quer prospectar e faturar"** no evento da Jovem Advocacia — Juazeiro/BA.

Nenhuma delas é produto comercial — são projetos de código aberto mantidos pela comunidade. Teste, adapte e, se fizer sentido, contribua com quem construiu.

---

## 🔰 Como Usar Este Guia (Para Não Programadores)

Se você não é da área de tecnologia, não se assuste com os comandos de terminal. A maioria dessas ferramentas segue um destes 3 caminhos simples:

1. **Ferramentas em Python (ex: `pip install ...`):**
   * Baixe e instale o [Python](https://www.python.org/).
   * Abra o **Prompt de Comando** (Windows) ou **Terminal** (Mac).
   * Copie o comando indicado abaixo de cada ferramenta, cole no terminal e aperte **Enter**.

2. **Ferramentas com Docker (ex: `docker-compose up`):**
   * Baixe e abra o [Docker Desktop](https://www.docker.com/).
   * Ele cria um "servidor local" no seu computador para rodar sistemas complexos com um único clique.

3. **Prompts e Scripts em Texto:**
   * Não exigem instalação nenhuma! Basta copiar o texto e colar direto no ChatGPT, Claude ou Gemini.

---

## 🏛️ Jurisprudência e Consulta de Processos

### juscraper
Biblioteca em Python para consultar processos e jurisprudência em 18 tribunais estaduais (TJSP, TJBA, TJPE e outros), além do DataJud, do Jusbr (novo portal unificado do CNJ) e do PDPJ.

<pre><code>pip install juscraper</code></pre>

⭐ **38 estrelas** · Atualizado em 2026

---

## 📝 Peças Processuais com IA (Gratuito)

### Biblioteca de Prompts Jurídicos
41 prompts jurídicos prontos em português para usar com ChatGPT, Claude ou similar — peças, contestações, pareceres, contratos e rotina de escritório. Traz aviso claro de que o resultado exige revisão técnica antes de qualquer uso profissional.

---

## ⏱️ Monitoramento de Prazos e Processos

### mcp-juridico-brasil
Servidor MCP que roda direto no Claude Desktop: acompanha movimentações processuais e calcula prazos em dias úteis conforme o CPC, cobrindo 91 tribunais via DataJud.

<pre><code>uvx mcp-juridico-brasil</code></pre>

### busca-processos-judiciais
Biblioteca em TypeScript/JavaScript para consultar processos via API pública do CNJ em todas as Justiças — Estadual, Federal, Trabalhista, Eleitoral, Militar e Tribunais Superiores.

<pre><code>npm i busca-processos-judiciais</code></pre>

⭐ **80 estrelas** · 44 forks

---

## 💼 CRM para Escritório de Advocacia

### LexManager
CRM simples em Flask, com gestão de clientes, processos e integração com o DataJud. Projeto pequeno e ainda inicial — bom ponto de partida para quem quer customizar, não uma solução pronta.

### EMAJ
Sistema em Laravel + Vue.js para gestão de escritório (clientes, processos, financeiro, agenda), criado originalmente para o escritório-modelo da UNIPLAC. Código mais robusto, documentação mais enxuta.

---

## 🤖 Outras Ferramentas de IA (Uso Geral)
*Não são específicas de advocacia, mas valem pelo potencial de uso no dia a dia — conteúdo, atendimento e produtividade.*

### LibreChat
Interface de chat com IA self-hosted, tipo um ChatGPT próprio: unifica OpenAI, Claude, Gemini e outros modelos numa única plataforma, com agentes, busca na web e Code Interpreter.  
⭐ **42,6 mil estrelas**

<pre><code>docker-compose up</code></pre>

### Claude Ads
Skill para Claude Code que audita contas de anúncios pagos (Google, Meta, TikTok) com mais de 160 verificações e um score de saúde de 0 a 100.  
⭐ **55 estrelas**

<pre><code>curl -fsSL https://raw.githubusercontent.com/Hainrixz/claude-ads/main/install.sh | bash</code></pre>

### Agentic Inbox
Cliente de e-mail self-hosted (roda em Cloudflare Workers) com um agente de IA que lê, busca e sugere respostas — sempre com confirmação antes de enviar.  
⭐ **6,4 mil estrelas**

### Open-LLM-VTuber
Assistente de IA com avatar animado (Live2D), 100% offline, com conversa por voz e percepção visual — dá pra usar como personagem para conteúdo em vídeo.  
⭐ **13,5 mil estrelas**

### Open Higgsfield AI
Alternativa open source e gratuita ao Higgsfield AI: mais de 200 modelos de geração de imagem e vídeo (Image Studio, Video Studio, Lip Sync, Cinema Studio), sem assinatura.  
⭐ **135 estrelas**

<pre><code>git clone https://github.com/Anil-matcha/Open-Higgsfield-AI.git</code></pre>

---

## ⚠️ Aviso Legal
Ferramentas de terceiros, mantidas pela comunidade — use por sua conta e risco, revise antes de aplicar a qualquer caso real, e respeite sempre o dever de sigilo e as normas de ética da OAB.

---

**Ruan Victor Freire Rodrigues** · Advogado · OAB/BA 63.187  
🌐 [ruanrodrigues.adv.br](https://ruanrodrigues.adv.br) · 📸 [@ruanrodrigues.adv](https://instagram.com/ruanrodrigues.adv)
