# 📅 Organizador de Rotina com Inteligência Artificial

## 📝 Descrição do Projeto
Este projeto consiste em um ecossistema integrado para a organização de rotinas pessoais e aumento da produtividade, utilizando Inteligência Artificial para transformar a gestão do tempo em uma experiência dinâmica e personalizada. O objetivo principal é solucionar problemas comuns como a sobrecarga de tarefas, a má gestão do tempo e a falta de consistência em hábitos, oferecendo uma solução que se adapta ao comportamento do usuário em tempo real.

Desenvolvido para a disciplina de **Engenharia de Prompt**, o sistema utiliza um web chat onde o usuário interage em linguagem natural. Através de automações, o organizador processa dados de compromissos e prioridades para gerar cronogramas otimizados, equilibrando atividades obrigatórias com períodos de lazer e descanso.

## 🚀 Tecnologias Utilizadas
* **Automação (Cérebro Operacional):** [n8n](https://n8n.io/) (Open-source, self-hosted).
* **Inteligência Artificial:** [ChatGPT (OpenAI)](https://openai.com/chatgpt) para interpretação de dados e geração de rotinas.
* **Banco de Dados:** [Firebase Cloud Firestore](https://firebase.google.com/) (NoSQL) para armazenamento de histórico e preferências.
* **Frontend:** HTML, CSS e JavaScript (Interface de Web Chat Simulado).

## 📊 Diferenciais e Resultados
O projeto se destaca por sua arquitetura modular e baixo custo de manutenção.
* **Personalização Real:** Diferente de agendas estáticas, a IA ajusta a rotina automaticamente diante de imprevistos.
* **Métodos de Produtividade:** Implementação de blocos de foco (60-90 min), pausas estratégicas e priorização de tarefas (baixa a urgente).
* **Escalabilidade e Custo:** Estimativa de custo mensal entre R$ 50 e R$ 150 para milhares de execuções em ambiente self-hosted.
* **Eficiência:** Tempo médio de resposta entre 3 a 8 segundos por interação.

## 🔧 Como Executar
1.  **Configurar n8n:** Importe o workflow de automação e configure os webhooks.
2.  **Configurar Firebase:** Crie um projeto no console do Firebase e configure as coleções `usuarios`, `tarefas` e `preferencias`.
3.  **Configurar IA:** Insira sua chave de API da OpenAI (ou outro LLM compatível) nos nodes do n8n.
4.  **Interface:** Hospede os arquivos da pasta `/web-chat` em um servidor de sua preferência.

## 👥 Grupo: Vibes & Codes
* Lucas Henrique Roque Cruz
* Matheus de Oliveira Santos
* Renan Correia Ferreira de Souza
* Vinicius Xavier
* Vinicius Scherer Di Giorno
* Matheus Chagas Mauriz Coque
* Mariana Calderari
* Gabriel da Silva Cesario

---
[Voltar ao início](https://github.com/matheus-coder987/projeto-organizador-ia)
