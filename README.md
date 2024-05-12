# Chatbot para atendimento "humanizado", e gestão de agenda (Imersão IA - Alura + Google)

### 1. Introdução
Este projeto visa desenvolver um chatbot inteligente integrado ao WhatsApp, utilizando a API do modelo Gemini da Google, para proporcionar agendamento automatizado e atendimento personalizado aos clientes através de linguagem natural.

### 2. Funcionalidades
* **Interação em Linguagem Natural:**
    * O chatbot permite aos clientes agendar compromissos utilizando comandos de voz ou texto, de forma intuitiva e eficiente.
    * A API do Gemini garante compreensão precisa da linguagem natural, interpretando as necessidades do cliente e respondendo de forma coerente e humanizada.
* **Agendamento Automatizado:**
    * O chatbot acessa um banco de dados para consultar a disponibilidade na agenda, considerando o tipo de serviço e a duração estimada.
    * O cliente escolhe o serviço desejado, e o chatbot sugere horários disponíveis, realizando o agendamento automaticamente após a confirmação do cliente.
* **Banco de Dados Integrado:**
    * Armazena informações importantes como:
        * Nome do cliente
        * Contato (número de telefone)
        * Motivo do agendamento
        * Data e horário
        * Endereço (se necessário)
        * Tipo de serviço
* **Limitações e Regras:**
    * **Edição de Agendamento:** Impossibilita a edição de agendamentos com menos de 24 horas de antecedência.
    * **Limite de Alterações:** Limita as alterações de horário a duas vezes dentro de uma hora.
    * **Casos Excepcionais:** Em situações que exigem exceções às regras, o cliente é direcionado a entrar em contato direto com a empresa.
* **Gestão de Horários Otimizada:**
    * O chatbot estima o tempo de atendimento com base no serviço escolhido, evitando conflitos na agenda e otimizando a gestão de tempo.
* **Agendamento Automatizado para Clientes Especiais:**
    * Permite o agendamento automático para clientes fixos ou com pacotes de serviços, simplificando o processo para clientes recorrentes.
* **Notificações Automatizadas:**
    * Envio de lembretes automáticos via WhatsApp, notificando o cliente sobre a proximidade do seu compromisso, evitando atrasos e faltas.

### 3. Benefícios
* **Experiência do Cliente Aprimorada:** Agendamento fácil, rápido e intuitivo via WhatsApp, utilizando linguagem natural.
* **Redução de Falhas Humanas:** Automatização do processo de agendamento minimiza erros e otimiza a gestão da agenda.
* **Aumento da Eficiência:** Economia de tempo e recursos, permitindo que a equipe se concentre em outras tarefas.
* **Melhoria na Comunicação:** Notificações automáticas garantem que os clientes sejam informados sobre seus compromissos.
* **Flexibilidade para o Cliente:** Possibilidade de agendar, cancelar ou reagendar compromissos a qualquer hora e lugar.

### 4. Conclusão
Este projeto representa uma solução inovadora e eficiente para empresas que buscam automatizar o agendamento de clientes e aprimorar a experiência do cliente, utilizando o poder da IA e a popularidade do WhatsApp.
