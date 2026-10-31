# Engenharia de Software com IA (TIexames)

Fonte: TIexames, curso online com o professor Jessé Rovira, 4 aulas ao vivo de 27 a 30/10/2026, 8 horas no total (certificado de participação emitido em 30/10/2026). Os slides das aulas foram usados como apoio e o resumo está com as minhas palavras. O crédito do conteúdo é da TIexames e do professor.

## Em uma frase
Com IA, o prompt inicia a conversa, mas quem sustenta o projeto é a documentação: decisões registradas, dono definido e uma pessoa aprovando o que importa.

## O fio das 4 aulas
Um projeto de exemplo, uma loja online fictícia chamada CommerceAI, foi levado da ideia até o plano de trabalho para agentes de IA.

- **Aula 1 - memória do projeto.** A conversa com a IA não é a memória do projeto: o agente considera só um volume limitado de informação, e o que foi combinado se perde. A solução é o **playbook**, um conjunto de documentos com visão, atores, módulos, arquitetura, decisões e pendências, que qualquer agente (ou pessoa) lê para continuar de onde parou. Segredos como senhas ficam fora dos documentos e do Git: o guia só indica o caminho.
- **Aula 2 - dois consultores, um projeto.** No Claude Code, cada especialidade vira uma Skill própria: um consultor de arquitetura (entrevista, compara opções, produz playbook e registros de decisão) e um consultor de modelagem. A conversa é temporária; os arquivos são a passagem de bastão (handoff). Teste-chave: o segundo agente consegue explicar as decisões sem ter ouvido a primeira conversa?
- **Aula 3 - do negócio à especificação.** Primeiro português estruturado, depois formato formal. Entidade (assunto sobre o qual se guarda informação), campos com tipo e regras (obrigatório, único, identificador), relacionamentos (um cliente tem vários pedidos) e estados com transições permitidas (rascunho, aprovado, pago, cancelado). O arquivo XSD valida a estrutura do XML, mas não prova que a regra de negócio está certa.
- **Aula 4 - interface e plano.** Wireframe é a planta baixa da tela e deve nascer da visão, do playbook e da modelagem, não de gosto. Depois vêm histórias de usuário com critérios de aceite, o Product Backlog, o Sprint Planning e o Sprint Backlog com tarefas pequenas e verificáveis para os agentes, cada uma com fonte, resultado esperado, dependências e teste.

## O método: Pattern 5D
Descobrir, desenhar, decidir, documentar e validar. Não são cinco reuniões, são responsabilidades contínuas, e o ciclo volta quando uma tela revela uma regra que faltava. A IA recomenda e documenta; a pessoa aprova as decisões relevantes.

Cada decisão tem um status para que uma sugestão não vire regra sem querer:
- **Confirmado:** informado ou verificado em fonte autorizada.
- **Proposto:** alternativa esperando aceite.
- **Pendente:** falta resposta ou validação.
- **Rejeitado:** descartado, com o motivo registrado.

Quando duas fontes se contradizem, o agente para, sinaliza e valida, em vez de escolher sozinho.

## Exemplo no ProvedorX (fictício)
O ProvedorX quer um portal de autoatendimento para segunda via de fatura e abertura de chamado. O consultor de arquitetura pergunta antes de propor ferramentas: haverá um sistema legado? Quem aprova textos gerados por IA? O que é indispensável na primeira versão? As respostas viram playbook e registros de decisão. A entidade Chamado ganha estados (aberto, em atendimento, resolvido, cancelado) com transições definidas. A resposta sugerida pela IA fica "em revisão" até um atendente aprovar. O resultado é um pacote que outro agente, ou outra pessoa, executa sem adivinhar.

## Como se conecta com o resto
- **ITIL 4:** práticas de gestão do conhecimento, de habilitação de mudanças e de desenvolvimento e gestão de software. O playbook é conhecimento mantido; a decisão registrada é a rastreabilidade de uma mudança.
- **COBIT 2019:** gestão do conhecimento (BAI08) e arquitetura corporativa (APO03) ajudam a ler o playbook como ativo de governança.
- **Governança de IA:** o humano aprova antes de publicar e o agente não decide sozinho o que é sensível. É a mesma lógica de dono, indicador e limite de autonomia.
- **Segurança e LGPD:** segredos fora do Git, privilégio mínimo e dados pessoais tratados no desenho, não depois.

## Pegadinhas para lembrar
- XML válido no XSD não significa regra de negócio correta (estrutura x semântica).
- Release e Sprint não são a mesma coisa: uma Sprint gera incremento, e a Release é a disponibilização aos usuários, que pode ocorrer durante ou após a Sprint.
- UI é o que a pessoa vê; UX é a experiência de alcançar o objetivo.
- A especificação não é o banco de dados: primeiro o que o negócio precisa registrar, depois a implementação.
- ADR significa Architecture Decision Record, o registro de uma decisão arquitetural.

## Para revisar
<details>
<summary>1. Por que uma conversa com a IA não serve como memória do projeto?</summary>
O agente considera um volume limitado de informação, e mensagens e respostas ocupam esse espaço. Decisões antigas se perdem, e uma nova conversa não as conhece. Por isso elas ficam em documentos (playbook e registros de decisão).
</details>

<details>
<summary>2. O que significam os status confirmado, proposto, pendente e rejeitado?</summary>
Confirmado: decidido ou fornecido, com fonte. Proposto: alternativa aguardando aceite. Pendente: falta resposta ou validação. Rejeitado: opção descartada, com o motivo.
</details>

<details>
<summary>3. Por que o item do pedido é uma entidade separada do produto?</summary>
O produto mostra o preço atual do catálogo. O item do pedido guarda o preço e a quantidade daquela compra, e a compra antiga não deve mudar se o preço mudar.
</details>

<details>
<summary>4. O que o XSD valida e o que ele não valida?</summary>
Valida a estrutura: nomes, atributos exigidos, tipos e valores permitidos. Não valida se as transições fazem sentido nem se as regras refletem a visão aprovada. Isso exige conferência humana.
</details>

<details>
<summary>5. Qual é a diferença entre Product Backlog e Sprint Backlog?</summary>
O Product Backlog é a lista ordenada de necessidades e melhorias do produto. O Sprint Backlog é o objetivo da Sprint com os itens selecionados e o plano de execução.
</details>

Nota feita a partir dos slides das aulas e do certificado. Anotações próprias do dia a dia podem ser acrescentadas depois.
