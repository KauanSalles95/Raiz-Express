# 🌱 Raiz Express


**Raiz Express** é um aplicativo de delivery voltado para **produtos da agricultura familiar e de pequenos produtores locais**: hortifrúti, ovos, queijos, mel e pães artesanais.

O objetivo é encurtar o caminho entre quem planta e quem come. O consumidor sabe exatamente de onde vem cada alimento, e o produtor vende direto, sem atravessador e com um painel simples para controlar pedidos e estoque.


---

## 🚀 Principais Funcionalidades

### 🛒 Para o Consumidor

- **Busca por proximidade:** encontra produtores e produtos num raio de poucos quilômetros.
- **Origem transparente:** cada item mostra a propriedade, o produtor e o horário da colheita.
- **Pagamento rápido:** Pix com confirmação instantânea (via Webhooks) ou cartão de crédito.
- **Acompanhamento em tempo real:** mapa com a rota do entregador e status de cada etapa do pedido.

### 🧑‍🌾 Para o Produtor

- **Painel web:** cadastro de produtos, controle de estoque e agenda de colheita.
- **Gestão de pedidos:** aceitar, preparar e marcar como pronto em poucos cliques.
- **Relatórios de vendas:** produtos mais vendidos e faturamento por período.

### 🚚 Para o Entregador

- **Rotas agrupadas:** pedidos próximos entram na mesma rota, reduzindo o custo de frete.
- **Confirmação com foto:** comprovante de entrega registrado no app.

### 💡 Diferenciais

- 🧺 **Cestas por assinatura:** semanal ou quinzenal, com itens da safra.
- 🍅 **Selo "Colhido hoje":** destaque para produtos colhidos no mesmo dia.
- ⭐ **Avaliações:** consumidores avaliam produtos e produtores.

---

## 🛠️ Tecnologias Utilizadas

- **Mobile:** ![React Native](https://img.shields.io/badge/React_Native-black?logo=react&logoColor=61DAFB)
- **Front-end Web:** ![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white)
- **Back-end:** ![Static Badge](https://img.shields.io/badge/Python-white?logo=Python&logoColor=White&labelColor=black&color=steelblue)
- **Banco de Dados:** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
- **Cloud e Infraestrutura:** ![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
- **Integrações:** ![Mercado Pago](https://img.shields.io/badge/Mercado_Pago_API-00B1EA?logo=mercadopago&logoColor=white) 



## 🔄 Metodologias

### Por que Espiral e não Cascata?

| Critério | Cascata | Espiral | Nossa situação |
|---|---|---|---|
| Requisitos mudam no caminho? | Difícil de lidar | Aceita bem | **Mudam muito**: vamos descobrir o que o produtor realmente precisa |
| Há riscos técnicos altos? | Aparecem só no final | Análise de risco a cada ciclo | **Sim**: pagamento, geolocalização e tempo real |
| Dá para entregar por partes? | Só no fim | Protótipo a cada volta | **Sim**: queremos validar cedo com produtores reais |

O Cascata supõe que sabemos tudo antes de começar, o que não é verdade num marketplace de dois lados. No **Espiral**, cada volta passa por **planejamento → análise de riscos → desenvolvimento e testes → avaliação**.

### Ciclos planejados

| Ciclo | Objetivo | Risco analisado | Entregável |
|---|---|---|---|
| 1 | Validar a ideia | Produtores não adotarem o app | Protótipo no Figma |
| 2 | Catálogo funcional | Busca por proximidade lenta | Cadastro, busca e carrinho |
| 3 | Fluxo de compra | Falhas no pagamento | Pedido pago de ponta a ponta |
| 4 | Logística | Rastreamento instável | Entrega em tempo real |
| 5 | Retenção | Complexidade das assinaturas | Cestas recorrentes |

---

## 🏁 Diagramas e Telas

- [Caso de Uso](Diagramas/Caso%20de%20Uso.md)
- [Raiz Express no Figma](https://www.figma.com/design/kMyWXu8UDGKctp73x8O0U8)

---

## 🎯 Próximos Passos do Desenvolvimento

- [x] Definir o escopo e as funcionalidades principais.
- [x] Desenhar o protótipo das telas no Figma.
- [ ] Validar o protótipo com produtores e consumidores reais.
- [ ] Criar o MVP focado no fluxo: busca → carrinho → pagamento Pix.
- [ ] Desenvolver o painel do produtor.
- [ ] Integrar entrega e rastreamento em tempo real.
- [ ] Implementar as cestas por assinatura.

---

Desenvolvido com ☕ por ***Kauan Salles Alves***
