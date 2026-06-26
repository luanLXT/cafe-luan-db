# ☕ Café Luan — Banco de Dados (API)

Este repositório contém o arquivo `db.json` que alimenta a API REST mockada (via [JSON Server](https://github.com/typicode/json-server)) do projeto **Café Luan**.

## 🔗 Links relacionados

- **Front-end (produção):** https://luanlxt.github.io/cafe-luan/
- **Repositório do front-end:** https://github.com/luanLXT/cafe-luan
- **API hospedada (Render):** https://cafe-luan-db.onrender.com

## 📋 Recursos disponíveis

| Endpoint | Descrição |
|---|---|
| `/menu` | Lista de cafés do cardápio, separados em `especiais` e `cafes` |
| `/tipos_leite` | Opções de tipo de leite (integral, desnatado, vegetal, sem leite) |
| `/tamanhos` | Opções de tamanho (pequeno, médio, grande) |
| `/opcionais` | Acompanhamentos e adicionais disponíveis |
| `/pedidos` | Pedidos realizados (CRUD completo) |
| `/status_pedido` | Status possíveis de um pedido (recebido, em preparo, pronto, entregue) |

## ⚙️ Deploy

Este serviço está hospedado no [Render](https://render.com), configurado com:

- **Build Command:** `npm install json-server@0.17.4`
- **Start Command:** `npx json-server --watch db.json --host 0.0.0.0 --port $PORT`

> ⚠️ Por estar em um plano gratuito, o serviço entra em modo de espera após períodos de inatividade. A primeira requisição após esse período pode levar de 30 a 50 segundos para responder.

---

Desenvolvido por Luan como projeto acadêmico.

Atualiza README com links e descrição da API
