README.md


Simulação de Copiloto com Fluxo de Conversa Personalizado

Objetivo: Simular a criação de um Copiloto no Microsoft Copilot Studio, explorando fluxos de conversa, personalização de tópicos, mensagens de erro e controle de qualidade de respostas com GenAI.

Criação do Copiloto em branco

Foi criada uma instância de Copiloto em branco para simular o projeto.

Essa etapa permite começar o desenvolvimento do fluxo de conversa do zero, sem tópicos predefinidos.

Customização de Tópico

Criado um tópico principal chamado “Gerenciamento de Tarefas”.

O tópico tem sub-tópicos como:

Criar tarefa

Ver tarefas

Cada sub-tópico tem respostas específicas simuladas para interagir com o usuário.

Personalização de Mensagem de Erro

Mensagem de erro personalizada para inputs inválidos: “Desculpe, não entendi ‘[input do usuário]’. Por favor, escolha uma das opções disponíveis.”

Garante que o usuário saiba que digitou algo incorreto, mantendo a experiência do fluxo.

Controle de Qualidade da Resposta com GenAI

Simulado ajuste da qualidade da resposta para:

Alta qualidade: respostas detalhadas, completas e com sugestões adicionais.

Baixa qualidade: respostas curtas e diretas, apenas o essencial.

Mostra como o Copiloto poderia gerar respostas mais precisas ou mais rápidas, dependendo da necessidade do usuário.

Exemplo de Conversa

Arquivo: exemplos/conversa.txt

Usuário: criar tarefa
Copiloto: Perfeito! Vamos criar uma nova tarefa.


Usuário: ver tarefas
Copiloto: Aqui estão suas tarefas atuais.


Usuário: xyz123
Copiloto: Desculpe, não entendi "xyz123". Por favor, escolha uma das opções disponíveis.

Aprendizados

Estruturação de fluxo de conversa em tópicos e sub-tópicos.

Criação de mensagens de erro personalizadas.

Compreensão de como o GenAI pode influenciar a qualidade das respostas.

Planejamento de uma experiência de usuário consistente.