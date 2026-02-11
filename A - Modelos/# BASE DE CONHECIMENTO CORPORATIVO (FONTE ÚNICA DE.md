# BASE DE CONHECIMENTO CORPORATIVO (FONTE ÚNICA DE VERDADE)

## 1. PROTOCOLOS DE SEGURANÇA E ACESSO

### Como realizar o Login e Logoff Administrativo?
* **Login:** Utilizar e-mail e senha do administrador nos campos designados e clicar em "Entrar". É diferente dos operadores que usam credencial numérica.
* **Logoff:** Posicionar o cursor sobre o nome do administrador no canto superior e clicar na opção "Logout". O usuário será redirecionado para a tela de login.

### Como realizar o Login e Logoff de Operadores (Agentes)?
* **Requisito de Navegador:** Utilizar **Google Chrome** para compatibilidade.
* **Credenciais:** Utilizar matrícula numérica e senha inicial fornecida pelos gestores.
* **Requisito de Hardware:** É importante ter um dispositivo de gravação e reprodução de áudio (headset).
* **Primeiro Acesso:** É necessário permitir o uso do microfone no pop-up do navegador.
* **Logoff:** Clicar no botão "Sair do Sistema" e confirmar a intenção na janela de diálogo.

### Quais são as Regras para Criação e Alteração de Senhas?
* **Critérios de Segurança Obrigatórios:**
    * Mínimo de **8 caracteres**.
    * Incluir letras maiúsculas e minúsculas.
    * Incluir números.
    * Incluir pelo menos um caractere especial.
* **Sugestão de Formato:** Exemplo: NomeEmpresa@AnoAtual.
* **Procedimento para Administrador:**
    1.  Clicar no nome do usuário (canto superior direito) e selecionar "Alterar senha".
    2.  Preencher Senha Atual, Nova Senha e Confirmar Nova Senha.
    3.  Clicar no botão vermelho "Salvar".
* **Procedimento para Agente:**
    1.  Clicar no avatar (ícone de perfil) e selecionar "Meu Perfil".
    2.  Clicar no botão "Trocar Senha".
    3.  Preencher Senha Atual e Nova Senha (duas vezes) e clicar em "Atualizar".

### Como proceder em caso de Bloqueio ou Esquecimento de Senha?
* **Desbloqueio:** Se um agente errar a senha várias vezes, o administrador deve acessar o menu "Agentes" e clicar no botão "Desbloquear".
* **Esquecimento:** Se o agente não lembrar a senha, o administrador deve editar o perfil, trocar a senha, salvar e aplicar as modificações.
* **Login Remoto (Admin):** O administrador pode logar no perfil de qualquer agente sem saber a senha clicando no botão "Login" na lista de agentes. O perfil do admin é substituído pelo do agente.

---

## 2. FUNCIONALIDADES DO AGENTE (OPERAÇÃO)

### Como funciona o Dashboard e Status?
* **Início do Turno:** O operador inicia na plataforma **em pausa**. Para ficar disponível, deve clicar no ícone de play (verde).
* **Dashboard:** Exibe blocos com quantidade de mensagens por canal, gráficos de linha (frequência de login e volume), e gráfico de pizza (motivos de finalização).
* **Pausas:** O operador pode realizar a **troca rápida** entre pausas (seta circular) sem precisar ficar disponível antes.
* **Indicadores de Fila:** A lateral direita mostra indicadores numéricos de fila para chat e voz. Passar o cursor exibe o nome da fila e contagem.

### Quais as funcionalidades da Interface de Chat?
* **Identificação Visual:** Balões à esquerda representam mensagens do cliente; balões à direita representam respostas do operador ou bot.
* **Regra de Envio:** Uma vez que a mensagem aparece como enviada, não pode ser excluída ou cancelada.
* **Áudio:** Gravar clicando no ícone do microfone e selecionar enviar (ícone verde) ou cancelar (ícone vermelho).
* **Arquivos:**
    * **Download:** Clicar na seta para baixo (individual) ou usar a função de download em lote (ícone "Baixar Arquivos").
    * **Envio:** Arrastar arquivos para a área de conversa ou clicar no ícone de clips.
* **Scripts:** Textos pré-prontos acessíveis pelo ícone de ações ou pelo atalho hashtag (`#`).
* **Emojis:** Disponíveis clicando no ícone do emoji.

### O que é o Modo Multi Window (Múltiplos Atendimentos)?
* **Capacidade:** Permite administrar até **quatro** clientes simultaneamente em uma única tela.
* **Ativação:** Clicar no botão "Ativar modo Multi Window".
* **Retorno:** Clicar em "Ativar modo single Windows" para voltar ao foco centralizado.

### Como funcionam Substatus e Tags?
* **Substatus (Bandeirinha):** Etiquetas virtuais visuais para identificar o estado (ex: aguardando retorno). São vinculadas apenas enquanto o atendimento está ativo na tela do operador (removidas ao transferir/finalizar). O primeiro item da lista é "nenhum substatus".
* **Tags:** Etiquetas virtuais adicionais que permitem **filtragem** e agrupamento. Podem ser múltiplas por atendimento. Adiciona-se clicando no ícone indicado e digitando a tag.

### Como realizar Transferências e Finalizações?
* **Transferência:** Menu de ações > Selecionar transferência. Pode ser para um **Agente** específico ou para um **Setor/Equipe**.
    * *Regra:* Uma vez transferido, o atendimento não pode ser retomado pelo operador original a menos que seja retransferido.
* **Finalização:** Menu de ações > Clicar em "Finalizar". Deve-se escolher um motivo (tabulação) pré-definido. O atendimento é removido da fila ativa.

### Como utilizar a Telefonia (Softphone)?
* **Acesso:** Clicar na ação "Ligar" (ícone de telefone) no menu de ações.
* **Funcionalidade:** Abre um softphone (ramal virtual) para discagem manual ou automática.
* **Recursos:** Gravação de chamadas, mudo, transferência e histórico.
* **Interface:** O softphone pode ser movido para qualquer área da tela.

### Como realizar Contato Ativo e usar a API Oficial WhatsApp?
* **Busca:** Acessar menu "Contatos" e buscar por nome, telefone ou identificador.
* **Status de Disponibilidade (Balãozinho):**
    * **Cinza:** Já existe atendimento em andamento (não pode iniciar novo).
    * **Laranja:** Contato disponível para iniciar atendimento.
* **Janela de 24h (API Oficial):**
    * Se o usuário estiver inativo, o campo de digitação é substituído por aviso e botão "Enviar Template".
    * O envio do template notifica o cliente e aguarda resposta para ativar a janela de diálogo.
* **Indicador de Janela:** Ícone de calendário mostra status: Vermelho (inativo), Amarelo (quase expirando), Verde (ativo).

---

## 3. FUNCIONALIDADES DO ADMINISTRADOR (GESTÃO)

### Como gerenciar Agentes?
* **Caminho:** Menu "Contact Center" > Submenu "Agentes".
* **Edição:** Permite alterar Nome, Senha, Filas, Grupos de Tabulação, Grupos de Contatos, Rotas de Saída e Grupos de Scripts.
* **Restrição:** A matrícula é o único dado que **não** pode ser editado (é definitiva).
* **Chat Multitarefas:** Pode ser habilitado para permitir até quatro chats simultâneos.
* **Desativação/Reativação:** Ao desativar, o agente é removido das filas. Ao reativar, **não** é readicionado automaticamente às filas.
* **Aplicar:** Após alterações, deve-se clicar em "Aplicar modificações".

### Como configurar Calendários?
* **Caminho:** Menu "Contact Center" > "Calendário".
* **Padrões:** Existem dois calendários padrão (Horário Comercial e Feriados) configurados no bot.
* **Regra de Edição:** Deve-se excluir a faixa de horário antiga antes de adicionar uma nova.
* **Atenção:** Evitar excluir calendários, pois exige reconfiguração técnica do bot.

### Como gerenciar Pausas e Scripts?
* **Pausas:** Menu "Contact Center" > "Pausas".
    * Configurações avançadas incluem mensagem automática, tempo mínimo para envio e palavra-chave para encerrar (ex: "/sair").
    * Pausas desativadas só atualizam para o operador após Logoff/Login.
* **Scripts:** Menu "Contact Center" > "Scripts".
    * Para canais de chat, deve-se selecionar tipo "Chat" (exclui e-mail).
    * Permite uso de emojis.
    * Ao criar novos grupos, é necessário atualizar o perfil dos agentes para incluir o grupo.

### Como funciona o Monitoramento?
* **Caminho:** Menu "Contact Center" > "Monitoramento".
* **Aba Chat:** Visão quantitativa de agentes e detalhamento de atendimentos em aberto.
* **Aba Fila:** Visão geral das filas, SLA, chamadas abandonadas e status de agentes.
* **Ações em Lote:** Possibilidade de finalizar ou transferir múltiplos atendimentos simultaneamente.

### Como gerenciar Contatos?
* **Caminho:** Menu "Contact Center" > "Contatos".
* **Edição:** Permite ajustar Nome (substituindo telefone), CPF, Identificador e Agente Preferido.
* **Exclusão:** Não remove, apenas desabilita a visualização (reativável via filtro de inativos).
* **Identificador:** Campo 'coringa' pesquisável para dados únicos.

---

## 4. CATÁLOGO DE RELATÓRIOS (LISTA COMPLETA)

### Relatórios de Agentes (R1 - R14)
* **R1 Agentes – Logins/Pausas:** Data e horário de login, logoff e motivo da pausa.
* **R1B Agentes – Logins/Pausas:** Foco específico nas ações de Login e Logoff.
* **R2 Agentes – Estatísticas:** Tempo logado, qtd/tempo chamadas, qtd/tempo pausas, tempo livre.
* **R3 Agentes – Resumo DAC (médias):** Estatísticas de chamadas internas/externas (tempo total, qtd, média) e tempo login.
* **R4 Agentes – Lista de chamadas geradas:** Dados gerais (ramal, número, data, tempo chamando, status, tempo falando).
* **R5 Agentes – Chamadas geradas agrupadas por destino:** Ligações agrupadas pelo número discado.
* **R6 Agentes – Estatísticas chamadas externas:** Login, chamadas externas (qtd, total, médio) e pausas.
* **R7 Agentes – Resumo DAC (quantitativo):** Chamadas recebidas por fila, externas, internas e originadas.
* **R8 Agentes – Distribuição Tempo Logado:** Relação de atendimentos com tempo ocioso/pausa por dia.
* **R9 Agentes – Não atendimento no ramal:** Ligações atendidas, tempo tocando, tempo fila, status.
* **R10 Agentes – Estatísticas de ocupação:** Ocupação por intervalo de tempo (qtd agentes, tempo falando, % ocupação).
* **R11 Agentes – Estatísticas login, chamadas, pausas:** Agrupado por filas. Login, chamadas rec/geradas, pausas.
* **R12 Agentes – Lista de chamadas recebidas:** Agrupado por agentes. Ramal, origem, duração, status.
* **R13 Agentes – Pesquisa de satisfação:** Resultado da pesquisa telefônica por agente.
* **R14 Agentes – Disponibilidade:** Tempo disponível por canal (voz vs chat).

### Relatórios de Chamadas e Telefonia (R17 - R47)
* **R17 Chamadas - Tempo de Tabulação:** Info da ligação, tabulação usada, tempo para tabular.
* **R17A Chamadas - Não Tabuladas:** Ligações não tabuladas.
* **R18 Chamadas - TMA e TME por Tabulação:** Total chamadas, TMA e TME em função da tabulação.
* **R19 Chamadas – Tempo de chamadas em Ring:** Tempo tocando antes de atender (maior e médio).
* **R20 / R20A Chamadas – Lista de chamadas:** Informações de todas as chamadas (entr/saída, duração, status, espera, tabulação). R20A tem estrutura melhor para fonte de dados.
* **R21 Chamadas – Tempo de Espera:** Estatísticas separadas por dia (atendidas, abandonos, segundos de espera).
* **R22 Chamadas – Gráfico de Tempo de Atendimento:** Gráficos de qtd ligações por tempo, por fila.
* **R23 Chamadas – Nível de Serviço:** Atendidas (NS, TME, TMA), Abandonadas (% > tempo config), Transferidas.
* **R23A:** Nível de Serviço sem Agentes (transferidas sem agente).
* **R23B:** Nível de Serviço com filtro de tempo específico (ex: 7h às 9h de cada dia selecionado, não período corrido).
* **R23C:** Nível de Serviço para acompanhar várias filas (Gerencial para múltiplas DACs).
* **R24 Chamadas – Estatísticas por intervalo:** Separado por hora (fila, transbordo, abandono, TMA, NS).
* **R25 / R26 Chamadas – Estatísticas por DDD:** Por DDD (geral) ou Por DDD/Dia. (Transbordadas, abandonos, atendidas, TMA).
* **R27 Chamadas – Estatísticas por Período:** Agrupado por filas (Recebidas DAC, Internas, Atendidas NS, TMA, Abandonos, Espera).
* **R28 Chamadas – Tempo de abandono:** Total abandonos por tempo.
* **R29 Chamadas – Abandonadas:** Atendidas e abandonadas com/sem fila de espera.
* **R30 Chamadas – Status:** Qtd e tempo por status da chamada.
* **R31 Chamadas – Análise Completa Receptivo:** Por dia (Agente, Qtd atendidas, Tempos méd/max, Desligadas ao atender).
* **R32 Chamadas – Análise Completa Ativo:** Por dia (Agente, Qtd atendimentos, ocupados, não atendido, congestionamento).
* **R33 Chamadas – Números Externos:** Ligações externas para ramais.
* **R34 / R35 Chamadas – Rechamadas:** Estatísticas de números que ligaram repetidamente.
* **R37 Chamadas – Estatísticas Ativo:** Ligações ativas feitas por agentes + gráfico.
* **R38 / R39 Chamadas – Classificação (Tabulação):** Sintético (Total e %) e Analítico (Detalhado por ligação).
* **R40 DAC – Quantitativo por Serviço:** Por tipo de serviço (qtd, tempo, média).
* **R41 DAC – Perfil de Espera:** Gráficos (atendidas na fila/hora, atendidas/tempo fila, abandonadas/tempo fila).
* **R42 DAC – TME:** Tempo Médio de Espera (atendidas vs abandonadas).
* **R43 DAC – TMA:** Tempo Médio de Atendimento receptivo.
* **R45 DAC – Estatísticas de transferências:** Origem, qtd transferidas, transbordadas, abandonadas, atendidas.
* **R46 DAC – Estatísticas por intervalo:** Intervalos de 1h (atendidas <10s, TME, TMA, Pausa).
* **R47 DAC – Atendimento Totalizado:** Tempos min, med, max e total por agentes/DACs.

### Relatórios de Chat (R70 - R98)
* **R68 / R69 Chat - Autoatendimento:** R68 Consolidado (finalizações por bots por rota). R69 Analítico (detalhe por contato, bot, tabulação).
* **R70 Chat – Atendimentos (Geral):** Estatísticas completas. Qtd por entrada, tabulação, fila, transferências. Listagem com origem, contato, agente, tempos, msgs, status.
* **R71 / R71A Chat – Estatísticas Agentes:** Total conversas, mensagens e tempo médio. R71 (por dia), R71A (período total).
* **R72 Chat – Pontos de Acesso:** Rastreamento do cliente pelos pontos do Bot.
* **R73 Chat – SLA de Atendimento:** Por hora. Atendidas, dentro do NS, não atendidas, % NS.
* **R74 Chat – Pesquisa de Satisfação:** Data, agente, questão e nota.
* **R75 Chat – Pessoas atendidas por dia:** Fila, qtd usuários, TME. Identifica altas e baixas de fluxo.
* **R76 Chat – Atendimento incluindo ativos:** Similar ao R70, mas inclui atendimentos ativos (idos falar com cliente).
* **R77 Chat – Volumetria de mensagens:** Total mensagens/conversas por tipo de entrada, por mês e dia.
* **R78 Chat - Nível de Serviço V2:** Não recomendado (metodologia específica).
* **R78A / R78B Chat - TMA e TME:** R78A Consolidado (Rota, Total chats, TME, TMA). R78B Analítico (Por protocolo, tempo fila, tempo atend).
* **R79 / R79A / R79B Chat - Substatus:** Consolidados e históricos de uso de substatus.
* **R94 Chat - Volumetria de abertura de protocolos - Canais:** Iniciado pelo operador vs Iniciado pelo cliente.
* **R95 Chat - Volumetria de abertura de protocolos - Agentes:** Protocolos criados pelos agentes.
* **R96 Chat - Simulação de janelas do Whatsapp:** Simulação de consumo Gupshup/Meta.
* **R97 Chat - Protocolos - consolidado (BI):** O mais completo consolidado. Toda a jornada (tempos bot, fila, resposta 1º agente, humano, contagem msgs cliente/agente/bot).
* **R98 Chat - Protocolos - analítico (BI):** O mais completo analítico. Detalhe por atendimento dentro do protocolo.

### Outros Relatórios e Avisos
* **R80 Callback – Abandono na fila:** Data, telefone, fila, status.
* **R81 Callback – Retorno IVR:** Data, telefone, fila, status.
* **R90 Lista de Agentes por Grupo:** Nome, matrícula, criação, status.
* **R91 Lista de Grupos:** Filas, autopause, música de espera.
* **R92 Lista de Serviços:** URAs e URLs de dados.
* **R93 Agentes Vips:** Lista de contatos com agente VIP associado.
* **R100 Contatos:** Melhor maneira de exportar contatos da ORPEN.
* **Relatórios com Problemas:**
    * **URA:** R60 a R65 precisam ser revistos (geram em branco ou dados sem sentido).
    * **R67 Chat:** Recontato Após Auto Atendimento (Gera em branco).