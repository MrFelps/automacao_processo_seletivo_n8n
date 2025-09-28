# 📌 Automação de Processo Seletivo com n8n

Este projeto é um **fluxo de automação desenvolvido no n8n** para otimizar as etapas de um processo seletivo. O objetivo é reduzir tarefas manuais, padronizar a comunicação com candidatos e dar mais agilidade ao time de recrutamento.

---

## ⚙️ Funcionalidades do Fluxo

- **Recebimento de candidaturas** O fluxo é disparado automaticamente quando um candidato envia sua inscrição.

- **Validação de informações (salário pretendido)** Um nó de verificação analisa a faixa salarial informada e direciona o candidato para o fluxo adequado.

- **Cadastro automático** O candidato é registrado em uma base (planilha ou banco de dados).

- **Comunicação automatizada por e-mail** São enviados e-mails personalizados para diferentes áreas (Dev, Mídias Sociais, Gestor da Vaga, etc.).

- **Agendamento de entrevista** Para candidatos aprovados, o fluxo cria automaticamente um evento no **Google Calendar**, gera o link de entrevista e envia os detalhes por e-mail.

---

## 🛠️ Tecnologias Utilizadas
- [n8n](https://n8n.io) – Plataforma de automação de workflows  
- Gmail API – Envio de e-mails automáticos  
- Google Calendar API – Agendamento de entrevistas  

---

## 📂 Estrutura do Repositório
- `rh_processo_seletivo.json` → Arquivo exportado do n8n contendo toda a lógica do processo seletivo.  
- `README.md` → Descrição e documentação do projeto.  

---

## 🚀 Benefícios da Automação
- Redução de tempo gasto em tarefas repetitivas.  
- Comunicação mais rápida e organizada.  
- Processo seletivo mais ágil e profissional.
