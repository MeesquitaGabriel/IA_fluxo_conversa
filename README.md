# IA_fluxo_conversa
Criação de um copiloto personalizado

O que foi aprendido
Criação do Copilot em Branco

Entramos no Microsoft Copilot Studio e selecionamos “Criar um Copilot em branco”.

Definimos nome, descrição, idioma e permissões básicas do novo Copilot.

Customização de um Tópico

Na área “Tópicos”, clicamos em “Customizar um tópico” (ou “+ Novo tópico”).

Escolhemos um título de tópico, descrevemos sua finalidade e criamos gatilhos (palavras-chave) para ativá-lo.

Redigimos instruções ao modelo (system prompt) orientando como responder quando aquele tópico fosse acionado.

Incluímos exemplos de entradas e saídas para treinar o modelo sobre o formato desejado.

Salvamos o tópico para que ele passe a participar do fluxo de conversação.

Personalização da Mensagem de Erro de Tópico

Navegamos até “Personalizar uma mensagem de erro de tópico”.

Substituímos o texto padrão de “Não entendi” por uma mensagem mais contextual, que orienta o usuário sobre as opções possíveis (por ex.: “Posso ajudar a consultar saldo, faturas ou planos. O que deseja fazer?”).

Definimos também mensagens específicas para erros de permissão (caso o usuário tente acessar algo proibido).

Salvamos as alterações, garantindo que o fallback do Copilot esteja amigável.

Ajuste de Qualidade de Resposta com GenAI

Acessamos a seção “Aumentar e diminuir a qualidade da resposta com GenAI”.

Configuramos parâmetros como Temperatura e Top-P para regular criatividade versus precisão.

Testamos dúvidas de exemplo para ver se o Copilot responde de forma concisa (temperatura baixa) ou mais fluida/conversacional (temperatura mais alta).

Salvamos as configurações finais, garantindo que o Copilot devolva respostas no nível de qualidade desejado.

Considerações Finais
Ao final desse processo, você terá um Copilot totalmente “do zero”, com pelo menos um tópico específico funcionando, uma mensagem de fallback personalizada e parâmetros de GenAI ajustados para controlar o estilo das respostas.

Se quiser criar mais tópicos (por ex.: “Agendar reunião”, “Criar tíquete de suporte”, “Enviar e-mail”), basta repetir o passo 2 para cada novo tema.

Sempre que alterar qualquer conjunto de parâmetros ou instruções, teste no próprio Chat do Copilot antes de colocar em produção.
