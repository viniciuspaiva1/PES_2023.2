# Requisitos de um Gerenciador de Condomínio
## Sumário dos requisitos funcionais de um `condômino`
### Portaria:
* [Receber Encomendas](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-receber-encomendas)
* [Receber entregas (delivery)](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-receber-entregas)
* [Cadastrar visitantes](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-cadastrar-visitante)
* [Registro de ocorrências](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-registrar-ocorr%C3%AAncias)
### Agendamentos:
* [Reservar áreas comuns](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-reservar-%C3%A1reas-comuns)
* [Visualizar cronograma de lavanderia](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-visualizar-cronograma-lavanderia)
### Administrativo
* [Visualizar mural de avisos](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-visualizar-mural-de-avisos)
* [Pagar contas/multas](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-pagar-contasmultas)
* [Registrar chamados](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-registrar-chamados)
* [Prestar contas](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-prestar-contas)
* [Fazer reclamações/sugestões](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-fazer-reclama%C3%A7%C3%A3osugest%C3%B5es)
***
## Requisitos funcionais de um `condômino`

### Fluxo comum de Receber Encomendas
	a.  Receber notificações
	b.  Aceitar o recebimento de encomenda
#### Extensões de receber encomendas:
>1.b.  Reportar pelo app, caso a encomenda não seja do condômino
### Fluxo comum de Receber Entregas
	a.  Cadastrar a solicitação de um delivery
	b.  Receber de notificação a chegada
### Fluxo comum de Cadastrar Visitante
	a.  Cadastrar um visitante pelo nome e data de chegada
	b.  Gerar um código de acesso referente ao visitante
	c.  Receber notificação de que o visitante chegou
#### Extensões de cadastrar visitante:
>1.c.  Condômino pode compartilhar o código por whatsapp

>2.c.  O código deve ser informado na portaria para conferência
### Fluxo comum de Registrar Ocorrências
	a.  Registrar que houve algum tipo de transtorno envolvendo o condomínio
	b.  Verificar o status da ocorrência, se foi ou não atendida
#### Extensões de registrar ocorrências:
>1.a.  Transtornos seriam situações que envolvam uma semi-urgência (ex: carro alarmando) ou falha de outros condôminos (ex: estacionou na vaga errada)

>1.b.  Status: Atendida, não visualizada, em andamento.
### Fluxo comum de Reservar áreas comuns
	a.  Informar qual o espaço a ser reservado
	b.  Exibir um calendário do mês com as datas disponíveis e ocupadas
	c.  Informar a data e o horário de reserva
### Fluxo comum de Visualizar cronograma lavanderia
    a.  Exibir um calendário da semana com todos os horários
	b.  Trocar/Adicionar horário (em horários livres)
	c.  Notificar que não irá usar em determinado horário
### Fluxo comum de Visualizar Mural de Avisos
	a.  Visualizar os avisos mais recentes que foram postos pela administração
	b.  Receber a notificação
### Fluxo comum de Pagar contas/multas
	a.  Visualizar as contas de condomínio já pagas e as futuras
	b.  Realizar pagamento de conta via app
	c.  Visualizar se há alguma multa pendente a ser paga
	d.  Realizar pagamento da multa via app
	e.  Receber notificações para pagamentos pendentes
### Extensões de pagar contas/multas :
	1.c.  Recorrer à multa, caso necessário
### Fluxo comum de Registrar Chamados    
	a.  Realizar a abertura de um chamado para a administração
	c.  Visualização do histórico de chamados e status relativo a eles
#### Extensões de registrar chamados:
>1.a.  Chamados seriam coisas como manutenção do patrimônio condominial, problemas administrativos.
### Fluxo comum de Prestar Contas
    a.  Visualizar a prestação de conta da administração
    b.  Selecionar o período para visualizar
    c.  Visualizar gráficos e histórico
#### Extensões de prestar contas
>1.a.  Descritivo do recebimento e gastos mensais pela gestão
### Fluxo comum de Fazer reclamação/sugestões
    a.  Cadastrar reclamação e/ou sugestão para a equipe administrativa

***
***
## Sumário dos requisitos funcionais de um `administrador`
### Agendamentos
* [Gerenciar espaços comuns](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-gerenciar-espa%C3%A7os-comuns)
### Administrativo
* [Cadastrar novas notícias](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-cadastrar-novas-not%C3%ADcias)
* [Aplicar multa](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-aplicar-multas)
* [Atender chamados](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-atender-chamados)
* [Comentar sobre reclamações/sugestões](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-comentar-sobre-sugest%C3%B5esreclama%C3%A7%C3%B5es)
* [Cadastrar o condomínio como um todo](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-cadastrar-condom%C3%ADnio)
* [Cadastrar evento](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-cadastrar-calend%C3%A1rio)
* [Visualizar lista de insumos](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-visualizar-lista-de-insumos)
* [Gerenciar chamados](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-gerenciar-chamados)
### RH 
* [Adicionar/remover funcionários](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-adicionarremover-funcion%C3%A1rios)
* [Acessar/atender chamados dos funcionários](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-acessaratender-chamados-de-funcion%C3%A1rios)
### Finanças 
* [Cadastrar e visualizar as despesas](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-cadastrar-e-visualizar-as-despesas)
***
## Requisitos funcionais de um `administrador`

### Fluxo comum de Gerenciar espaços comuns
	a.  Visualizar todos os espaços comuns
	b.  Alterar reservas
	c.  Adicionar novos espaços    
#### Extensões de gerenciar espaços comuns:
> 1.b Poder mudar a disponibilidade na semana, o nome, etc.
### Fluxo comum de Cadastrar novas notícias
    a.  Visualizar o histórico de notícias
    b.  Cadastrar uma nova notícia
    c.  Notificar todos usuários que uma nova notícia foi cadastrada
#### Extensões de cadastrar novas notícias
> 1.b. Poder selecionar o período em que a notícia vai ficar fixada no mural e/ou agendar a postagem de uma notícia
### Fluxo comum de Aplicar multas
    a.  Selecionar um apartamento
    b.  Visualizar o histórico de multas do apartamento
    c.  Registrar uma multa
    d.  Notifica o condómino que recebeu a multa
#### Extensões de aplicar multas:
>1.b. Pode-se deferir ou indeferir o recurso

>1.c. Deve-se colocar a descrição, valor, tipo, data do ocorrido, data de vencimento (depende da política condominial)

### Fluxo comum de Atender chamados
    a.  Visualizar o histórico de chamados
    b.  Responder o chamado
#### Extensões de atender chamados
> 1.b. Alterar o status do chamado para: atendido, em andamento, rejeitado

### Fluxo comum de Comentar sobre sugestões/reclamações
    a.  Visualizar todas a sugestões/reclamações
    b.  Responder ao usuário que abriu a sugestão/reclamação
    c.  Notificar o usuário
### Fluxo comum de Cadastrar condomínio
	a.  Construir o esquemático de torres e apartamentos do condomínio
    b.  Definir áreas comuns
#### Extensões de cadastrar condomínio
> 1.a :
> - Divisão: torres, blocos, rua
> - Indicar exceções (torres com quantidades diferentes de apto)

> 2.b. Quantificar piscinas, churrasqueiras, etc.
### Fluxo comum de Cadastrar calendário
	a.  Visualizar os eventos já agendados
	b.  Alterar/excluir um evento
    c.  Cadastrar um evento
    d.  Notificar usuários antecipadamente sobre o evento
    
### Fluxo comum de Visualizar lista de insumos
    a.  Visualizar o histórico das listas mensais (pode virar gráfico)
    b.  Mudar status de uma solicitação
#### Extensões de visualizar lista de insumos
>1.b. Status: Comprado, rejeitado, solicitado

### Fluxo comum de Gerenciar chamados
    a.  Visualizar todos os chamados
    b.  Encaminhar o chamado para o setor/pessoa responsável
    c.  Mudar status de um chamado
    d.  Notificar usuário que abriu o chamado
#### Extensões de gerenciar chamados
> 1.c. Status: em andamento, concluído ou rejeitado

### Fluxo comum de Adicionar/remover funcionários
    a.  Visualizar o quadro de funcionários
    b.  Adicionar/alterar/remover funcionários
### Fluxo comum de Acessar/Atender chamados de funcionários
	a.  Visualizar todos os chamados
    b.  Encaminhar o chamado para o setor/pessoa responsável
    c.  Mudar status de um chamado
    d.  Notificar usuário que abriu o chamado
#### Extensões de acessar/atender chamados de funcionários
>1.c. Status: Em andamento, concluído ou rejeitado

### Fluxo comum de Cadastrar e visualizar as despesas
	a.  Selecionar o período para visualização histórica
    b.  Cadastrar uma despesas
    c.  Visualizar gráficos sobre um determinado setor
    d.  Visualizar fluxo de caixa
***
***
## Sumário dos requisitos funcionais de um `funcionário`
### Portaria
*  [Acessar os painéis de encomendas e entregas](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-acessar-os-pain%C3%A9is-de-encomendas-e-entregas)
*  [Acessar o painel de visitantes](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-acessar-o-painel-de-visitantes)
*  [Visualizar/Atender ocorrências](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-visualizaratender-ocorr%C3%AAncias)
###  Administrativo
*  [Abrir chamados](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-abrir-chamados)
*  [Visualizar calendário](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-visualizar-calend%C3%A1rio)
*  [Solicitar insumos/manutenção](https://github.com/viniciuspaiva1/PES_2023.2/tree/main/Gerenciador%20de%20condominio#fluxo-comum-de-solicita%C3%A7%C3%A3o-de-insumosmanuten%C3%A7%C3%A3o)
***
## Requisitos funcionais de um `funcionário`

### Fluxo comum de Acessar os painéis de encomendas e entregas
    a.  Visualizar as encomendas e entregas
    b.  Liberar uma entrega
    c.  Receber uma encomenda
    d.  Notificar o usuário
### Fluxo comum de Acessar o painel de visitantes
    a.  Visualizar os visitantes (por apartamento)
    b.  Liberar a entrada
    c.  Notificar o usuário
### Fluxo comum de Visualizar/Atender ocorrências
    a.  Visualizar as ocorrências
    b.  Mudar status de uma ocorrência
#### Extensões de visualizar/atender ocorrências
> 1.b. em andamento, concluído
### Fluxo comum de Abrir chamados
    a.  Realizar a abertura de um chamado para a administração
    b.  Visualizar o histórico de chamados e status relativo a eles
### Fluxo comum de Visualizar calendário
    a.  Visualizar o cronograma das atividades do condomínio
### Fluxo comum de Solicitação de insumos/manutenção
    a.  Visualizar o itens que já foram solicitados (mês atual)
    b.  Visualizar o status da solicitação
    c.  Cadastrar nova solicitação
