# 🧪 Perguntas Simuladas — Teste da IA Financeira

> Envie estas mensagens via WhatsApp para testar o assistente IA do Finanzas-App.
> Cada seção testa um aspecto diferente do sistema.

---

## 📥 1. Registro de Transações (Input)

| # | Mensagem | O que testa |
|---|---|---|
| 1 | `"Gastei 45.000 no mercado hoje"` | Registro básico de gasto |
| 2 | `"Recebi meu salário de 3.500.000"` | Registro de ingresso alto |
| 3 | `"Paguei 12.500 de transporte"` | Categoria automática (transporte) |
| 4 | `"Almorcei por 18.000 no centro"` | Categoria automática (alimentação) |
| 5 | `"Paguei Netflix 49.900 pesos"` | Serviço de assinatura recorrente |
| 6 | `"Comprei medicamentos 35.000"` | Categoria saúde |
| 7 | `"Gas del apartamento 85.000"` | Serviço doméstico |
| 8 | `"Me devolvieron 20.000 que le presté a Juan"` | Ingresso inusual |

---

## 💰 2. Consultas de Saldo e Resumos

| # | Mensagem | O que testa |
|---|---|---|
| 9 | `"Cuánto gasté esta semana?"` | Consulta por período curto |
| 10 | `"Cuál es mi saldo de este mes?"` | Resumo mensal |
| 11 | `"Cuánto gasté en comida este mes?"` | Filtro por categoria |
| 12 | `"Muéstrame mis gastos de hoy"` | Filtro por data (hoje) |
| 13 | `"Cuánto llevo gastado en transporte en marzo?"` | Mês específico + categoria |
| 14 | `"Resumen del mes pasado"` | Mês anterior |

---

## 📊 3. Comparativos e Tendências

| # | Mensagem | O que testa |
|---|---|---|
| 15 | `"Estoy gastando más o menos que el mes pasado?"` | Comparação entre meses |
| 16 | `"En qué categoría gasto más?"` | Análise de padrão |
| 17 | `"Cómo va mi presupuesto de entretenimiento?"` | Status de orçamento |
| 18 | `"Cuánto me falta para llegar al límite del presupuesto?"` | Alerta de limite |

---

## 🎯 4. Orçamentos e Metas

| # | Mensagem | O que testa |
|---|---|---|
| 19 | `"Cuanto he usando de mi presupuesto mensual?"` | Progresso do orçamento |
| 20 | `"Voy a recibir 500.000 esta semana, guárdalos"` | Ingresso futuro |
| 21 | `"Quiero ahorrar 200.000 este mes, es posible?"` | Projeção de poupança |

---

## 🔴 5. Casos Extremos e Ambíguos

| # | Mensagem | O que testa |
|---|---|---|
| 22 | `"gasté"` | Mensagem incompleta |
| 23 | `"Compré algo por ahí de unos 30 lucas"` | Valor informal (jerga colombiana) |
| 24 | `"Paguei R$150 no supermercado"` | Moeda errada (BRL em vez de COP) |
| 25 | `"Fui de compras"` | Sem valor especificado |
| 26 | `"123456789"` | Número sem contexto |
| 27 | `"Gasté 0 pesos ayer"` | Valor zero |
| 28 | `"Gasté MUCHO esta semana jaja"` | Valor qualitativo, não numérico |

---

## 🤖 6. Fora do Escopo Financeiro

| # | Mensagem | O que testa |
|---|---|---|
| 29 | `"Qual é a capital da França?"` | Pergunta não financeira |
| 30 | `"Me ayudas a escribir un email?"` | Pedido fora do domínio |

---

## ✅ Critérios de Avaliação

| Critério | O que observar |
|---|---|
| **Precisão** | Registra o valor e categoria corretos? |
| **Inferência** | Detecta a categoria sem ela ser mencionada? |
| **Jargão local** | Entende termos colombianos (`lucas`, `pesos`)? |
| **Tolerância a erros** | Lida elegantemente com inputs incompletos? |
| **Delimitação** | Rejeita perguntas fora do escopo financeiro? |
| **Multilíngue** | Responde em espanhol independente do idioma de entrada? |
