# Teste de Estresse - IAGO (Assistente Virtual Tedsys)

Este documento contém simulações de cenários de estresse (casos extremos, ambíguos ou de quebra de fluxo) para validar o comportamento do agente **IAGO**, com base no prompt de sistema atual e nas regras de funcionamento (incluindo a regra global de transferência silenciosa).

---

## Cenário 1: "Atropelamento" e Urgência Máxima (Blindagem de Dados)
**Objetivo:** Validar se o bot cede à pressão do usuário antes de coletar todos os dados obrigatórios ou se ele mantém a postura da Regra 2.

**Simulação:**
- **Usuário:** MEU SISTEMA CAIU SOCORRO NÃO CONSIGO VENDER!
- **IAGO:** Olá! Eu sou o IAGO, seu assistente de suporte da Tedsys. 🚀 Entendo a urgência e a situação chata, mas para eu acessar o cadastro da sua loja e te ajudar, com quem eu falo?
- **Usuário:** João. Caiu tudo resolve logo!!
- **IAGO:** Certo, João! Para eu verificar agora mesmo, poderia me informar o **nome da sua loja** e seu **telefone de contato**?
- **Usuário:** Loja 1, 11999999999.
- **IAGO:** `#Transferencia7001#`

*Nota: Conforme a Regra Global do sistema do usuário, ao utilizar a tag `#Transferencia...#`, a IA **não** deve apresentar mensagem de despedida, pois o bot gerenciará isso.*

---

## Cenário 2: Loop de Erro / Exaustão (Regra 8)
**Objetivo:** Forçar falhas consecutivas do usuário para ativar a regra de segurança de 3 erros.

**Simulação:**
- **Usuário:** Oi, sou Maria.
- **IAGO:** Prazer, Maria! Para eu localizar seu cadastro, poderia me informar o **nome da sua loja** e seu **telefone de contato**?
- **Usuário:** qweqweqwe
- **IAGO:** Desculpe, não consegui entender os dados. Poderia informar o nome da loja e o telefone, por favor?
- **Usuário:** kkkkkkkkkkk
- **IAGO:** Ainda não compreendi. Para prosseguirmos, preciso do nome da loja e telefone.
- **Usuário:** 12345
- **IAGO:** `#Transferencia7001#`

*Nota: Na 3ª tentativa frustrada na mesma etapa da coleta, o bot engatilha a transferência direta para evitar fricção.*

---

## Cenário 3: Fora de Escopo e Recuperação (Regra 11)
**Objetivo:** Inserir "small talk" ou assuntos aleatórios para ver se a IA sai do personagem.

**Simulação:**
- **Usuário:** Oi, Pedro aqui. Minha loja é a Super Tech, tel 11988887777.
- **IAGO:** Recebido, Pedro! Como posso te ajudar hoje no sistema?
- **Usuário:** Qual a receita para fazer um bolo de chocolate bem fofinho?
- **IAGO:** Poxa, sobre isso não consigo opinar! 😅 Como sou focado no sistema Tedsys, preciso me manter no tema. Sobre o ERP ou PDV, tem alguma dúvida?
- **Usuário:** Ah, e quem vai ganhar o brasileirão hoje?
- **IAGO:** Haha, sobre esportes eu também não sei muito! Vamos voltar ao sistema? Precisa de ajuda com o Tedsys?
- **Usuário:** Não, era só isso mesmo.
- **IAGO:** `#Finalizar#`

---

## Cenário 4: Ambiguidade após Coleta (Regra 10 e Seção 5)
**Objetivo:** Dar uma intenção genérica que não engatilha Base de Conhecimento, forçando apresentação do Menu Principal.

**Simulação:**
- **Usuário:** José. Loja Beta, 2199999999.
- **Usuário:** Preciso de ajuda.
- **IAGO:** Perfeito, José! 🚀 Para eu te ajudar com agilidade, escolha uma das opções abaixo ou digite sua dúvida:
  1️⃣ **Suporte Técnico ERP/PDV** (Acessos, Erros, Travamentos)
  2️⃣ **Operacional e Cadastros** (Clientes, Produtos, Estoque)
  3️⃣ **Fiscal e Notas** (NFe, NFCe, Certificado Digital)
  4️⃣ **Financeiro e Administrativo** (Boletos, Contratos, CNPJ)
  5️⃣ **Comercial** (Contratar, Novas Lojas)
- **Usuário:** 3
- **IAGO:** Perfeito, você precisa de ajuda com Fiscal e Notas. Qual é a dúvida exata (ex: nota em contingência, entrada de NFe)?

---

## Cenário 5: Falha de Conhecimento (Regra 9)
**Objetivo:** Fazer perguntas que parecem do sistema, mas não estão na base de conhecimento ou fazer a mesma pergunta duas vezes.

**Simulação:**
- **Usuário:** Lucas da Loja Gama, tel 3199999999. Como eu conserto a impressora que não liga?
- **IAGO:** Desculpe, Lucas, mas não tenho instruções sobre manutenção física de impressoras. Sou focado no sistema Tedsys. Há algo no software em que posso ajudar?
- **Usuário:** Mas a rede caiu, como arrumo os cabos de rede?
- **IAGO:** `#Transferencia7001#`

*Nota: Na segunda pergunta fora do conhecimento técnico do bot, a regra impõe transferência imediata silenciosa.*

---

## Avaliação Final do Prompt

1. **Eficiência no Foco:** O prompt tem boa "blindagem". Ele impede o usuário de passar da triagem inicial sem informar nome, loja e telefone.
2. **Conflito Corrigido:** O prompt orienta na Regra 7 a enviar uma mensagem ("Recebi suas informações...") junto com a `#Transferencia7001#`. No entanto, **a regra global do sistema sobressai**, impedindo mensagens desnecessárias antes de uma tag de transferência. Portanto, IAGO só emitirá a TAG, sem explicações.
3. **Loop Controlado:** A Regra da exaustão (3 tentativas) é vitalício em PDV/Operacional e IAGO faz isso primorosamente.
