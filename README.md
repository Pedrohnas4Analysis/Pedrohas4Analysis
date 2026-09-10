# Pedrohnas4Analysis
Me chamo Pedro Henrique. Natural do Rio de Janeiro. Estarei postando aqui os meus melhores projetos como Cientista de Dados. Tenho como formação de origem Bacharel em Educação Física, então embora esteja trabalhando na área Tech, a maioria dos projetos são voltados para Esportes.

# 📊 Portfólio de Dashboards de Dados

A seguir você pode encontrar dashboards interativos que desenvolvi para praticar análise exploratória de dados, storytelling visual e construção de indicadores de negócio. Dois deles foram construídos a partir de datasets públicos do Kaggle, e o terceiro a partir de uma base de dados que eu mesmo criei.

> 🛠️ Ferramenta principal: **Tableau**

---

## 🏅 1. Medalhas Olímpicas do Brasil

<p align="Left">
  <img src="assets/Captura de tela 2026-09-05 125727.jpg" alt="Exemplo" width="400">
</p>
<p align="Left">
  <img src="assets/Captura de tela 2026-09-10 141215.png" alt="Exemplo" width="400">
</p>

Dashboard que consolida o histórico de medalhas do Brasil nos Jogos Olímpicos, permitindo filtrar por gênero (masculino/feminino) e visualizar a distribuição geográfica das edições dos Jogos.

**Principais elementos:**
- Contadores de medalhas de ouro, prata e bronze
- Filtro interativo por categoria (ex: medalhas femininas)
- Mapa-múndi com o volume de medalhas por edição/sede dos Jogos
- Ranking dos maiores medalhistas brasileiros da história

**Fonte dos dados:** Kaggle

**Insights em destaque:**
- Do total de 530 medalhas, as mulheres respondem por **29,6%** (157 medalhas) contra 373 dos homens.
- A disparidade de gênero é maior justamente no **ouro**: os homens conquistaram quase **3x mais ouros** que as mulheres (103 vs 35), enquanto na prata a diferença é menor (122 vs 70) e no bronze intermediária (148 vs 52).
- Isso indica que, historicamente, o desempenho feminino brasileiro tem sido mais consistente em pódios de prata/bronze do que em conquistar o ouro — um ponto interessante para aprofundar cruzando com modalidade e época.

🔗 [Link para o dashboard no Tableau Public](#)
🔗 [Dataset original no Kaggle](#)

---

## 📉 2. Análise de Churn de Clientes (Telecom)

<p align="Left">
  <img src="assets/Captura de tela 2026-09-10 171819.png" alt="Exemplo" width="400">
</p>

Dashboard analítico sobre cancelamento de clientes (*churn*) em uma empresa de telecomunicações, com foco em identificar padrões de risco por tempo de permanência, tipo de contrato, serviço de internet e forma de pagamento.

**Principais elementos:**
- Taxa geral de churn (26,54%) e receita em risco (16,13%)
- Distribuição de tempo de permanência (*tenure*) por churn
- Análise cruzada entre tenure e tipo de contrato
- Segmentação de churn por serviço de internet e método de pagamento
- Filtro por serviço adicional (ex: Streaming Movies)

**Fonte dos dados:** Kaggle (Telco Customer Churn)

**Insights em destaque:**
- Clientes com contrato mensal ("Month-to-month") e menor tempo de casa concentram a maior parte do churn, enquanto contratos de dois anos apresentam retenção muito mais alta.
- Serviços de **suporte e proteção** (Tech Support, Online Security, Online Backup, Device Protection) têm forte relação com o churn: quem **não** contrata esses serviços cancela 1,5–1,7x mais do que quem contrata — sugerindo que a ausência de suporte técnico/segurança é um forte indicador de risco.
- Já os serviços de **entretenimento** (Streaming TV e Streaming Movies) mostram distribuição quase equilibrada entre quem tem e não tem (~39% vs ~39%), ou seja, praticamente não influenciam a decisão de cancelar.
- Isso sugere que investir em suporte técnico proativo tende a ter mais impacto na retenção de clientes do que pacotes de streaming.

🔗 [Link para o dashboard no Tableau Public](#)
🔗 [Dataset original no Kaggle](#)

---

## 🏋️ 3. Perfil Físico de Alunos de Academia (dataset próprio)

<p align="Left">
  <img src="assets/Captura de tela 2026-09-04 162923.png" alt="Exemplo" width="400">
</p>

Dashboard criado a partir de uma base de dados própria, com métricas de 100 alunos de academia: peso, IMC, percentual de gordura e VO2 máximo, segmentados por faixa etária, sexo e nível de flexibilidade.

**Principais elementos:**
- Cartões-resumo com médias gerais (peso, IMC, % de gordura, VO2 máx.)
- Distribuição de alunos por faixa etária
- Comparativo de VO2 médio e % de gordura por sexo (via filtro)
- Ranking Top 10 de flexibilidade

**Fonte dos dados:** dataset próprio, estruturado por mim

**Insights em destaque:**
- A base é composta por 56 alunas e 44 alunos, e é concentrada em adultos jovens: 94% dos alunos têm até 45 anos (31 entre 18-25, 34 entre 26-35, 29 entre 36-45, apenas 5 com 46+).
- A diferença de % de gordura entre sexos é de **7,5 p.p.** (26,1% feminino vs 18,6% masculino), e o VO2 máximo médio masculino é cerca de **18% maior** que o feminino (39,1 vs 33,2 ml/kg/min) — padrão fisiologicamente esperado, o que reforça a consistência da base.
- Combinando os dois indicadores, alunos com maior capacidade cardiorrespiratória (VO2 mais alto) tendem a apresentar menor % de gordura — uma correlação que pode ser explorada visualmente com um gráfico de dispersão VO2 x % Gordura.
- A faixa 46+ tem apenas 5 alunos, então métricas isoladas para esse grupo devem ser lidas com cautela pelo tamanho reduzido da amostra.

🔗 [Link para o dashboard no Tableau Public](#)

---

## 🛠️ Tecnologias e habilidades utilizadas

- **Tableau** — construção dos dashboards interativos
- **Excel / Google Sheets** — limpeza e organização inicial dos dados
- Análise exploratória de dados (EDA)
- Storytelling com dados e design de dashboards
- Criação de KPIs e filtros interativos

---
# Você pode me encontrar pelos links a seguir: ⤵️
</p>

<p align="left">
  <a href="#" title="Gmail">
  <img src="https://img.shields.io/badge/-Gmail-FF0000?style=flat-square&labelColor=FF0000&logo=gmail&logoColor=white&link=mailto:pedrohnas1999@gmail.com?cc=pedrohnas1999%40gmail.com&bcc=pedrohnas1999%40gmail.com&subject=Te%20encontrei%20no%20GitHub&body=Oi!" alt="Gmail"/></a>
  <a href="#" title="LinkedIn">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=www.linkedin.com/in/pedrohnas4analysis" alt="LinkedIn"/></a>
  <a href="#" title="WhatsApp">
  <img src="https://img.shields.io/badge/-WhatsApp-25d366?style=flat-square&labelColor=25d366&logo=whatsapp&logoColor=white&link=[API-DO-SEU-WHATSAPP](https://wa.me[21][994217718]?text=Oi!%20Encontrei%20seu%20perfil%20no%20GitHub." alt="WhatsApp"/></a>

</p>


> 💡 Sinta-se à vontade para explorar os dashboards e enviar feedback!


