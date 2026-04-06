# Tema Do Projeto

Este projeto tem como foco a construção de um caderno temático utilizando IA para análise e organização de conhecimentos em:

- Cibersegurança
- Infraestrutura de TI
- DevSecOps

O conteúdo foi baseado em projetos reais desenvolvidos Para testes no meu laboratório pessoal (WillSecLab), utilizando ferramentas como Graylog, Docker e automações.

---

# Curadoria de Fontes

Abaixo Foram selecionadas fontes para o estudo e melhoria no meu laboratorio visando o estudo e aprendizado em ciberseguraça, analise de logs e boas praticas em infraestrutura:

- https://cheatsheetseries.owasp.org/cheatsheets/AI_Agent_Security_Cheat_Sheet.html
- https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html
       - OWASP Cheat Sheets → boas práticas de segurança e defesa
- https://go2docs.graylog.org/current/home.htm
- https://go2docs.graylog.org/illuminate-current/content_packs/windows_security_event_logs_content_pack.html
       - Graylog Docs → gerenciamento e análise de logs (SIEM)
- https://www.elastic.co/docs/reference/beats/winlogbeat/
       - Elastic Winlogbeat → coleta e envio de logs do Windows

alem destes foram usados os links de meus repositorios o WillSecLab para que a llm me ajude a estudar corrigir e melhorar os mesmos
estes repositorios tem meus projetos que desenvolvi atravez de pesquisas ou projetos e melhorei e reimaginei com o uso da IA 

- https://github.com/Willian-1080p/PDI-Gitlab 
- https://github.com/Willian-1080p/home-cyber-lab
- https://github.com/Willian-1080p/Security-testes
- https://github.com/Willian-1080p/GrayLogs

---

# Emgenharia de Pronpts e "Cicatrizes"

Durante o Uso do NotebooKLM, Foram feitos varios teste de Pronpts tendo como opjetivo Extrarir respostas mais precisas, Praticas e aplicaveis ao meu Laboratorio

Abaixo alguns exemplos de prompts e evolução dos mesmos

---

# Caso 1: Entendimento de Logs de Segurança
# *Prompt inicial:*
"Explique logs de segurança"

*Resultado:*
Resposta muito genérica, sem aplicação prática.

# *Prompt melhorado:*
"Explique como identificar tentativas de login falhas em logs do Windows utilizando Winlogbeat e Graylog"

*Resultado:*
Resposta mais detalhada, com foco em eventos específicos e aplicação prática.

# *Aprendizado:*
Prompts genéricos geram respostas superficiais. Quanto mais contexto e tecnologia envolvida, melhor o resultado.

---

# Caso 2: Implementação prática no laboratorio
# *Prompt inicial:*
"Como usar o grayLog?"

*Resultado:*
Resposta ampla e pouco direcionada 

# *Prompt melhorado:*
"Como configurar inputs e streams no Graylog para monitorar eventos de segurança do Windows enviados pelo Winlogbeat?"

*Resultado:*
Resposta prática com direcionamento técnico e aplicável ao ambiente real.

# *Aprendizado:*
Especificar o cenário (ferramentas + objetivo) melhora significativamente a qualidade da resposta.

---

# Caso 2: Detecção de ameaças 
*Prompt inicial:**
"Como detectar ataques?"

*Resultado:*
Muito generico, sem contexto técnico.

*Prompt melhorado:*
"Quais eventos do Windows (Event ID) indicam possíveis ataques de força bruta e como identificá-los no Graylog?"

*Resultado:*
Resposta técnica, incluindo eventos relevantes e formas de analise.

# *Aprendizado:*
Adicionando Termos técnicos (ex: Event ID, brute force) direciona a IA para respostas mais úteis e diretas.

---

# "Cicatrizes"
- Respostas Genéricas quando o prompt era muito amplo 
- necessidade de reformular perguntas várias vezes 
- Dificuldade inicial de conectar a teoria com o ambiente real

---

# Estratégias adotadas

- Uso de Prompts mais especificos e contextuais 
- inclusao de ferramentas reais como graylog e winlogbeat
- interação contínua *(EX: teste -> ajuste -> melhoria)*

---
