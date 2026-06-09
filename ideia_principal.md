Ideia do Projeto - Orbital Rescue
O projeto sera uma API backend chamada Orbital Rescue, voltada para o contexto aeroespacial.

A ideia e criar um sistema que ajuda a priorizar e agendar imagens de satelite em situacoes de desastres naturais, como enchentes, queimadas, deslizamentos, rompimentos de barragem e vazamentos ambientais.

O problema e que imagens de satelite sao recursos limitados: os satelites passam por uma regiao em horarios especificos, possuem sensores diferentes, podem ter conflitos de agenda e podem ser afetados por condicoes como nuvens. Em uma emergencia, o sistema precisa decidir qual pedido deve ser atendido primeiro e qual satelite pode realizar a captura.

A solucao permite que clientes como Defesa Civil, prefeituras, ONGs, institutos ambientais e empresas privadas criem solicitacoes de imagem. O sistema calcula a prioridade com base em risco humano, urgencia, tipo de desastre, tipo de cliente e prazo de entrega. Depois, verifica se existe um satelite ativo com sensor compativel e uma janela de captura disponivel.

O fluxo principal seria:

Um cliente cria uma solicitacao de imagem.
O sistema calcula a prioridade automaticamente.
O sistema procura um satelite compativel.
O sistema reserva uma janela de captura.
Uma ordem de captura e gerada.
A imagem e entregue e o sistema verifica se o prazo foi cumprido.
Essa ideia e boa para o trabalho porque nao e apenas CRUD. Ela possui regras de negocio reais, como prioridade de emergencia, compatibilidade de sensores, conflito de agenda, reserva de janela e controle de SLA.

Resumo rapido:

Orbital Rescue e uma plataforma de priorizacao de imagens orbitais para resposta rapida a desastres naturais.