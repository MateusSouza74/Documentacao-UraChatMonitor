# Documentacao-UraChatMonitor
# 📡 UraChatMonitor API

Este repositório contém a documentação da API de monitoramento das interações em canais de **URA** e **Chat**, utilizados para rastrear o início, o fim e as chamadas de serviços internos de fluxos automatizados.

---

## 📋 Descrição

A `UraChatMonitor API` registra logs importantes para análise de desempenho e estabilidade de fluxos. Essa API é usada em três momentos distintos:

- **`/log_start`**: registra o início da interação.
- **`/log_end`**: registra o final da interação, incluindo o status e duração total.
- **`/log_service_call`**: registra chamadas de APIs internas feitas durante a conversa.
---

## 🧭 Como visualizar a documentação da API (via Swagger)
---
1. Acesse o site: [https://editor.swagger.io](https://editor.swagger.io)
2. Clique em **File > Import File** e selecione o arquivo `ura_chat_monitor.yaml`.
3. A documentação aparecerá do lado direito, já formatada.
