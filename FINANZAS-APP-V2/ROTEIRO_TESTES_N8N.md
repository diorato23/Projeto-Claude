# 🧪 Roteiro de Testes — Workflows N8N (Fanny via WhatsApp)

> Envie estas mensagens para a Fanny na ordem indicada e anote os resultados.

---

## 1️⃣ Transações

| # | Mensagem | Resultado Esperado | ✅/❌ |
|---|---|---|---|
| 1 | `Gastei 25000 en pizza` | Pedir confirmação → registrar como **gasto** | ✅ |
| 2 | `Recebi 500000 de salário` | Registrar como **ingreso/cobro** | ✅ |
| 3 | `Mostrar mis últimas transacciones` | Listar transações recentes (pizza + salário) | ✅ |
| 4 | `Buscar pizza` | Encontrar a transação da pizza com ID | ✅ |
| 5 | `Cambiar el monto de pizza a 30000` | **Editar** valor da pizza para 30.000 | ✅ |
| 6 | `Mostrar mis últimas transacciones` | Pizza deve mostrar **30.000** | ✅ |
| 7 | `Eliminar pizza` | **Deletar** a transação da pizza | ✅ |
| 8 | `Mostrar mis últimas transacciones` | Pizza **não deve aparecer** | ✅ |

---

## 2️⃣ Categorías

| # | Mensagem | Resultado Esperado | ✅/❌ |
|---|---|---|---|
| 9 | `Ver mis categorías` | Listar todas as categorias existentes | ✅ |
| 10 | `Crear categoría Supermercado` | Criar com emoji automático (🛒) | ✅ |
| 11 | `Ver mis categorías` | **Supermercado** deve aparecer na lista | ✅ |
| 12 | `Eliminar categoría Supermercado` | Deletar a categoria | ✅ |
| 13 | `Ver mis categorías` | Supermercado **não deve aparecer** | ✅ |

---

## 3️⃣ Presupuestos

| # | Mensagem | Resultado Esperado | ✅/❌ |
|---|---|---|---|
| 14 | `Ver mis presupuestos` | Listar presupuestos atuais (ou vazio) | ✅ |
| 15 | `Definir presupuesto Alimentación 500000` | Criar presupuesto de 500.000 | ✅ |
| 16 | `Ver mis presupuestos` | **Alimentación — 500.000** na lista | ✅ |
| 17 | `Eliminar presupuesto Alimentación` | Deletar o presupuesto | ✅ |
| 18 | `Ver mis presupuestos` | Alimentación **não deve aparecer** | ✅ |

---

## ✅ Critérios de Sucesso

- [x] CRUD completo funciona (Crear, Listar, Editar, Eliminar)
- [x] Fanny responde em **español** com emojis
- [x] Dashboard web atualiza automaticamente após cada operação
- [x] Nenhum erro de `undefined` ou registro fantasma
- [x] Trial expirado bloqueia tanto N8N quanto App Web

---

## 📝 Notas dos Testes

| Data | Observações |
|------|-------------|
| 20/03/2026 | ✅ Todos os 18 testes passaram com sucesso. Isolamento de dados por familia_id confirmado. |
aporteenlinea