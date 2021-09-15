# AtividadeCHAT

Na classe ClientSocket foi criado o atributo nome, para que cada usuário fosse nomeado e que pudesse ser enviado mensagens particulares, foram criadas também as funcios getNome e setNome.

Na classe BlockingChatClientApp só foi mudado o cabeçalho de opções para ser enviado a mensagem, se é para dar/mudar nome, enviar msg privada ou para todos.

Na classe BlockingChatServerApp foi alterado a função clientMessageLoop para que pudesse receber a msg e trata-la de acordo com seu tipo, iniciado com "!" para mudar ou setar o nome, "@" para mandar uma msg privada, foi criada a função sendMsgToOne que tem a finalidade de mandar a msg privada, recebendo o sender, msg e destinatário, fazendo praticamente a mesma coisa que a sendMsgToAll com a diferença de mais um filtro lincado com o nome do destinatário.
