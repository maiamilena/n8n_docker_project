🤖 Projeto n8n WAHA Pipa 
Desafio: Automatizar conversas de boas vindas, solicitar informações basicas dos clientes para otimizar o tempo de resposta do corretor de alugueis e dar dicas sobre a praia da pipa
---

## 💬 Sobre o projeto

Este projeto nasceu da minha curiosidade em unir duas áreas que amo: **Ciência de Dados** e **Automação** 

Mesmo sendo da área de dados, decidi me aventurar no mundo dos **workflows, webhooks, Redis, Docker e IA** e o resultado foi esse robô turístico simpático que conversa com clientes do **PipaAluguel**, ajudando com reservas e dando dicas sobre as belezas de Pipa 🌊.

O fluxo foi criado no **n8n** e usa:

- **WAHA (WhatsApp HTTP API)** → para enviar e receber mensagens do WhatsApp  
- **Google Gemini (via LangChain)** → para dar respostas com tom humano, informativo e acolhedor  
- **Redis Chat Memory** → pra o bot lembrar do contexto da conversa  
- **Webhook + Switch + Set Nodes** → pra tratar os dados e direcionar o fluxo  
- **Docker Compose** → pra deixar tudo rodando bonitinho localmente  
- **Wikipedia + Calculator Tools** → porque até o bot turístico precisa de cultura e cálculos rápidos 😄  

---

## ⚙️ Estrutura técnica
📁 n8n_waha_local/
├── docker-compose.yml # Configuração do Docker
├── n8n_waha_pipa.json # Workflow completo exportado do n8n
├── .gitignore
├── README.md
└── workflow.png # (opcional) print do fluxo visual
