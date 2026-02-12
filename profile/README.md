# Brasil Transparente

O **Brasil Transparente** é um projeto open-source que consolida e organiza os gastos **efetivamente pagos** pela União em um único lugar.

O objetivo é oferecer uma visão clara, estruturada e auditável de como o dinheiro público foi utilizado, reunindo dados que hoje estão distribuídos entre diferentes poderes e portais oficiais.

Mais do que visualização, o projeto propõe um modelo consolidado de leitura dos gastos federais.

---

## 🎯 Propósito

O Brasil Transparente busca:

- Consolidar dados de todos os poderes da União em uma base unificada
- Exibir apenas valores efetivamente pagos
- Reduzir ruídos como refinanciamento da dívida e transferências intergovernamentais
- Reclassificar despesas para permitir melhor compreensão do destino real dos recursos
- Tornar os dados públicos mais acessíveis sem perder rigor técnico

O foco é equilibrar clareza para o público geral e consistência metodológica para usuários técnicos.

---

## 🏛 Escopo Atual

O projeto atualmente contempla:

- Dados consolidados do último exercício disponível
- Poder Executivo
- Poder Legislativo
- Poder Judiciário
- Órgãos autônomos

Os dados são estruturados de forma hierárquica:

União → Poder → Órgão → Subórgão → Categoria de Despesa

---

## 📊 Metodologia (Resumo)

O projeto considera apenas valores efetivamente pagos.

São excluídos:

- Refinanciamento da dívida
- Transferências que não configuram gasto direto da União
- Valores apenas empenhados ou liquidados

Também há reclassificações específicas, como:

- Consolidação de aposentadorias e pensões
- Tratamento de precatórios e RPVs
- Ajustes para evitar dupla contagem institucional

A metodologia completa está documentada no site.

---

## 🗂 Origem dos Dados

Os dados são obtidos exclusivamente de fontes oficiais, incluindo:

- Portal da Transparência
- Câmara dos Deputados
- Senado Federal
- Supremo Tribunal Federal
- Conselho Nacional de Justiça
- Tribunal de Contas da União
- Ministério Público da União
- Defensoria Pública da União

Todos os datasets utilizados são públicos e verificáveis.

---

## 🔌 API Pública

O projeto disponibiliza uma API pública com documentação Swagger para consulta programática dos dados consolidados.

A API permite:

- Consulta por poder
- Consulta por ministério
- Consulta por órgão
- Consulta por despesa

---

## 🛠 Tecnologias

### Backend
- Java
- Spring
- MySQL

### Frontend
- Angular

### Infraestrutura
- Google Cloud
- Docker

---

## 🚀 Roadmap

Próximos passos planejados:

- Expansão da série histórica
- Documentação técnica detalhada do pipeline
- Melhorias na exportação de dados
- Aprimoramento da experiência para usuários

---

## 🤝 Como Contribuir

O projeto é aberto a contribuições técnicas e não técnicas.

Você pode ajudar com:

- Backend
- Frontend
- Infraestrutura
- Documentação
- Testes
- Revisão metodológica
- Design
- Feedback

Servidor no Discord para coordenação da comunidade:

👉 https://discord.gg/sQbf3bSzt4

---

## 📌 Princípios do Projeto

- Transparência metodológica
- Neutralidade política
- Rigor técnico
- Código aberto
- Dados verificáveis

---

## 📬 Contato

Para dúvidas técnicas, sugestões ou parcerias, utilize o servidor do Discord ou abra uma issue neste repositório.
