# Sessão 1 — Ficha de laboratório

**Instruções gerais**

- Trabalha com o teu grupo (2–3 pessoas). Cada grupo entrega uma única resolução.
- Os exercícios 1–3 fazem-se no laboratório 1 (antes da pausa); os exercícios 4–8 no laboratório 2, aplicados ao projeto do grupo.
- Os níveis indicam a dificuldade: **base** (aplicar diretamente o que foi explicado), **consolidação** (aplicar ao projeto) e **desafio** (decidir e justificar).
- Guarda as respostas num documento partilhado do grupo. As histórias de utilizador e o plano de etapas vão ser usados nas próximas sessões.

### Exercício 1 — Fases do ciclo de vida (base)

Indica a fase do ciclo de vida do software a que pertence cada atividade.

| Atividade | Fase |
|---|---|
| a) Entrevistar o dono da loja sobre o que corre mal com o caderno | Levantamento de requisitos |
| b) Desenhar o esboço do ecrã «Lista de pedidos» | Desenho |
| c) Escrever o código que guarda um pedido novo | Desenvolvimento |
| d) Abrir 20 pedidos de teste e confirmar que todos aparecem na lista | Testes |
| e) Instalar a aplicação no computador do balcão e explicar aos empregados como usá-la | Implantação |
| f) Corrigir um erro reportado três meses depois de a aplicação estar a funcionar | Manutenção |
| g) Perceber, a partir das notas da entrevista, que «saber o estado» exige uma lista fechada de estados | Análise |

### Exercício 2 — Funcional ou não funcional? (base)

Classifica cada requisito como **funcional (F)** ou **não funcional (NF)**.

1. O sistema deve permitir registar um cliente com nome, email e telefone. **(F)**
2. A lista de pedidos deve abrir em menos de 2 segundos com 1000 pedidos. **(NF)**
3. O sistema deve permitir filtrar os pedidos por estado. **(F)**
4. A aplicação deve funcionar nas versões atuais do Chrome e do Firefox. **(F)**
5. O sistema deve permitir atribuir um técnico a um pedido. **(F)**
6. Os dados pessoais dos clientes só podem ser consultados por funcionários da loja. **(F)**
7. O sistema deve registar a data de entrega quando o equipamento é levantado. **(F)**
8. Um empregado novo deve conseguir abrir um pedido em menos de 3 minutos, sem formação. **(NF)**
9. O sistema deve impedir que um pedido passe de «aberto» para «entregue». **(F)**
10. O sistema deve listar os equipamentos de um cliente. **(F)**

### Exercício 3 — Que metodologia? (base)

Para cada equipa, indica a metodologia descrita (cascata, iterativa/incremental, Scrum ou Kanban) e a frase que te deu a pista decisiva.

- **Equipa A:** trabalha em ciclos de duas semanas. No início de cada ciclo escolhe as histórias a fazer; todos os dias tem uma reunião de 15 minutos; no fim mostra o resultado ao *Product Owner*. **(SCRUM)**
- **Equipa B:** dá suporte técnico a uma empresa. Os pedidos chegam todos os dias e são postos num quadro com as colunas «Novo», «Em análise», «Em resolução» e «Resolvido». A coluna «Em resolução» nunca pode ter mais de 3 pedidos. **(KANBAN)**
- **Equipa C:** desenvolve o software de uma máquina de raio-X. Os requisitos foram aprovados por uma entidade reguladora e não podem mudar. Cada fase só começa depois de a anterior estar documentada e aprovada. **(CASCATA)**
- **Equipa D:** entregou ao cliente, no primeiro mês, uma versão que só registava encomendas. No segundo mês acrescentou a faturação e no terceiro os relatórios. Em cada entrega o cliente deu sugestões que foram usadas na seguinte. Não há papéis nem reuniões definidos. **(ITERATIVA/INCREMENTAL)**

### Exercício 4 — Histórias de utilizador (consolidação)

Escreve 6 histórias de utilizador para as funcionalidades mínimas do projeto (uma por funcionalidade), no formato «Como … quero … para …». Para cada história, escreve 2 critérios de aceitação verificáveis.

Funcionalidades mínimas: registar cliente e equipamento; abrir pedido; listar e filtrar pedidos por estado; atribuir técnico; mudar estado; fechar pedido.
**(Como técnico, quero poder registar os meus clientes e respetivos equipamentos, que entregam em loja, para organizar a linha de trabalho)**
**(Como técnico, quero conseguir abrir pedidos com a info necessária ao processo individual, para dar entrada ao equipamento no sistema e poder seguir o seu processo)**
**(Como técnico, quero ser capaz de listar e filtrar os pedidos existentes por estado, para conseguir organizar e planear o trabalho)**
**(Como técnico, quero poder atribuir técnicos a cada processo, para delegar trabalho)**
**(Como técnico, quero conseguir mudar o estado do processo, para poder o poder validar e agir conforme a informação disponível)**
**(Como técnico, quero ser capaz de fechar pedidos, para concluir processos, seja através de opções de "concluído" ou "cancelado")**

### Exercício 5 — Priorizar o *backlog* (consolidação)

O dono da loja deu-vos esta lista de desejos. Classifiquem cada item com MoSCoW para a **primeira versão** da aplicação e justifiquem em uma frase.

1. Abrir um pedido de assistência. **(Should)**
2. Enviar um SMS ao cliente quando o equipamento está pronto. **(Should/Could)**
3. Mudar o estado de um pedido. **(Must)**
4. Ver um gráfico com o número de reparações por mês. **(Could)**
5. Registar clientes e equipamentos. **(Must)**
6. Filtrar pedidos por estado. **(Must)**
7. Atribuir um técnico a um pedido. **(Must)**
8. Imprimir uma etiqueta com código de barras para colar no equipamento. **(Won't)**
9. Aplicação para telemóvel para os clientes consultarem o estado. **(Won't)**
10. Registar a data de entrega ao fechar o pedido. **(Must)**

### Exercício 6 — Ler um README (consolidação)

Lê o ficheiro `README.md` do repositório-modelo do projeto (o formador projeta-o ou partilha-o) e responde:

1. Que três ações tens de fazer na página do repositório para criar o ambiente de trabalho?
2. Quanto tempo pode demorar a preparação na primeira vez?
3. Que comando arranca a aplicação, e onde se escreve?
4. Que mensagem confirma que a aplicação arrancou, e em que porta fica?
5. O que fazes se a aplicação não abrir sozinha no browser? E como paras o servidor?

### Exercício 7 — Plano de etapas (desafio)

Construam o plano de etapas do vosso grupo para toda a UC, numa tabela com as colunas: **Etapa**, **Quando** (sessão ou período de trabalho autónomo), **Entregável**, **Responsável principal** e **Estimativa (horas)**.

O plano deve cobrir as sessões 2 a 7 e os seis marcos de trabalho autónomo, e a soma das estimativas do trabalho autónomo deve ser 15 horas. Indiquem também um risco do projeto e o que farão se ele acontecer.

### Exercício 8 — Quadro Kanban com limites (desafio)

Proponham o quadro Kanban do vosso grupo:

1. Que colunas vão usar? (mínimo 3) - **(A fazer / Em processo / Concluído / Entregue)**
2. Que limite de trabalho em curso (WIP) põem em cada coluna, e porquê? **(Em curso não pode ter mais do que 3 tarefas, pois isso leva a que os trabalhos sejam iniciados, mas nunca sejam concluídos)**
3. O que fazem quando a coluna «Em curso» está cheia e alguém acaba de ficar livre? **(Vai verificar o que é que está a interferir na conclusão da entrega das tarefas em curso)**
4. Criem o quadro (no GitHub Projects ou em papel) com pelo menos 6 cartões, um por história do exercício 4. - **(Feito no trello)**

