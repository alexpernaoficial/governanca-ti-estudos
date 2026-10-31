# ISO/IEC 20000-1 na prática: o que a norma exige e como o ITIL ajuda

> **Fonte:** TIexames · Wellington Mônaco · live (fev/2026) "Gestão de Serviços de TI na Prática com ISO/IEC 20000-1 e ITIL 4 e 5" · [vídeo no YouTube](https://youtu.be/wK7-C7PZ0bM) · assistida em 31/10/2026
> **Tema:** ISO/IEC 20000-1 · sistema de gestão de serviços · relação com o ITIL

## Em uma frase
A ISO/IEC 20000-1 diz **o que** um sistema de gestão de serviços precisa ter para ser auditado e certificado, e o ITIL mostra **como** fazer. As duas juntas funcionam como um "Lego": o escopo, o compromisso da alta direção e as ferramentas precisam ser definidos **no começo**, porque o resto da norma só executa e mede o que foi combinado ali.

## O que é
- **ISO/IEC 20000-1:2018:** norma internacional de **requisitos** para um **sistema de gestão de serviços** (SGS). É a **única norma certificável** de gestão de serviços. Vale para qualquer organização, de qualquer porte ou setor, e para qualquer tipo de serviço, não só de TI.
- **ISO/IEC 20000-2:** orientação (código de prática) para aplicar a parte 1. Não é certificável. A relação é parecida com a da 27001 (requisitos) com a 27002 (orientação sobre os controles).
- **ITIL:** biblioteca de boas práticas, com **34 práticas** de gestão. Não é certificável como sistema de gestão da empresa: certifica-se a **pessoa**.
- **Requisito × prática × processo:** são coisas diferentes. A ISO fixa o requisito (o que provar), o ITIL oferece a prática (como organizar) e o processo é a atividade que a empresa desenha no dia a dia.
- **ABNT:** representa a ISO no Brasil e traduz as normas para o português.

## Explicação simples

### 1. A estrutura comum a todas as ISO de sistema de gestão
Todas as normas ISO de sistema de gestão seguem a mesma **estrutura de alto nível** (*High Level Structure*, do Anexo SL). Por isso o índice se repete na ISO 9001, 27001, 22301, 31000 e outras, o que facilita integrá-las.

- **1 a 3:** escopo, referências normativas, termos e definições (informativas, não são auditadas).
- **4 · Contexto:** entender a organização, as partes interessadas e as suas necessidades, e **definir o escopo** do sistema.
- **5 · Liderança:** compromisso da alta direção, política e papéis (quem responde pelo sistema).
- **6 · Planejamento:** riscos e oportunidades, objetivos mensuráveis e o plano de gestão de serviços.
- **7 · Apoio:** recursos, competências, conscientização, comunicação, documentação e conhecimento.
- **8 · Operação:** onde estão os requisitos próprios de gestão de serviços (veja abaixo).
- **9 · Avaliação de desempenho:** monitoramento, auditoria interna, análise crítica pela direção e relatórios.
- **10 · Melhoria:** não conformidades, ação corretiva e melhoria contínua.

O **PDCA** aparece na própria estrutura: planejar (4 a 6), executar (7 e 8), verificar (9) e agir (10).

### 2. A cláusula 8 em sete grupos
- **8.1 Planejamento e controle operacional.**
- **8.2 Portfólio de serviços:** entrega e planejamento, partes envolvidas, **catálogo de serviços**, gestão de ativos e de configuração.
- **8.3 Relacionamento e acordo:** relacionamento com o negócio, **níveis de serviço**, fornecedores externos e internos.
- **8.4 Oferta e demanda:** orçamento e contabilização, demanda e capacidade.
- **8.5 Desenho, construção e transição:** **mudanças**, desenho do serviço, liberação e implantação.
- **8.6 Resolução e atendimento:** **incidentes**, requisições e **problemas**.
- **8.7 Garantia do serviço:** **disponibilidade**, **continuidade** e **segurança da informação**.

Detalhe que o professor reforçou: a ISO fala em **requisitos** (ex.: registrar, classificar, priorizar e escalar incidentes) e o ITIL traz a **prática** correspondente. O fluxo é integrado: incidente, problema, mudança, configuração e ativos conversam entre si.

### 3. O que mudou no ITIL (Version 5), segundo a aula
- O ITIL (Version 5) saiu em **fev/2026**. O foco passa de "serviço" para **produtos e serviços digitais**.
- O professor afirmou que as **34 práticas continuam** e mudou a abordagem: agora cada prática considera o uso de **IA**. (Fontes de mercado indicam que o grupo de práticas técnicas foi reposicionado e que a cadeia de valor virou um modelo de ciclo de vida de produtos e serviços; confira no material oficial antes de prova.)
- Ganha peso a **experiência** de quem usa, além do valor percebido. Entra o **XLA** (acordo de nível de experiência) ao lado do SLA.
- **Modelo 6C de capacidade de IA**, na leitura do professor:
  - **Criação:** construir e adotar soluções de IA;
  - **Curadoria:** dar contexto e qualidade aos dados;
  - **Clarificação:** validar e ajustar as respostas;
  - **Cognição:** entender e verificar o resultado;
  - **Comunicação:** agentes de IA entre si e com pessoas;
  - **Coordenação:** governar, com regras de ética e responsabilidade.
- A ISO 20000-1 continua na versão de 2018. Ela não precisa esperar uma nova edição: a empresa pode se movimentar na governança antes.

### 4. A tese da aula: decida tudo no começo
- **Cláusula 4:** levante dores, reclamações, multas, perdas de contrato, sistemas legados, o que existe e o que **falta** (ferramentas, pessoas, orçamento). Use análise **SWOT** e **PESTEL**. Escreva o escopo.
- **Cláusula 5:** obtenha a decisão da alta direção **por escrito**, com recursos e política. Se a direção não quer pagar uma solução, ela **aceita o risco** formalmente. Ao mudar o CEO, o compromisso continua registrado.
- **Cláusula 6:** defina objetivos, indicadores de risco e os **KPIs que a direção vai receber**. Se isso não for definido no início, não haverá orçamento nem ferramenta para as cláusulas 9 e 10.
- **Escopo e risco:** o que fica fora do escopo é risco assumido pela empresa e vira proposta de ampliação no orçamento seguinte.
- **Todo risco é registrado e tratado**, inclusive o risco **aceito** (que precisa de rastreabilidade).
- O professor afirmou que a maioria das falhas de implantação (ele citou 95%, sem fonte) vem de esquecer requisitos e ferramentas na fase inicial. Trate como opinião de consultor, não como estatística.
- A direção quer ver **dinheiro e risco**: disponibilidade dos produtos e serviços digitais e quanto se deixou de faturar quando caíram. Quantidade de chamados dentro do SLA é informação operacional.

### 5. Como usar ISO 20000 e ITIL juntos (6 passos)
1. **Defina o escopo** do sistema (cláusula 4) e o patrocinador, com a matriz RACI.
2. **Mapeie** as práticas ITIL necessárias, entre as 34.
3. **Monte a cadeia de valor** e conecte as práticas, incluindo o uso de IA.
4. **Implemente o PDCA** (cláusulas 4 a 10), em ondas, como programa.
5. **Meça, audite e melhore.** O ITIL orienta e a ISO garante a **auditabilidade**.
6. **Integre com outras normas:** 27001 (segurança), 9001 (qualidade), 22301 (continuidade), 27701 (privacidade).

**Armadilhas citadas:**
- confundir prática com processo;
- documentar só para a auditoria e não usar no dia a dia ("papelândia");
- focar só no planejamento ou só na operação, sem o compromisso da alta direção (o sistema cai em desuso);
- práticas isoladas, sem integração;
- falta de medição: sem indicadores de incidentes, problemas e mudanças não existe melhoria contínua;
- usar **template** pronto sem entender: cada empresa tem um cenário.

**Dica de engajamento ("gestão pela inveja"):** gere indicadores positivos sobre as áreas que mais ajudam e divulgue, para aproximar as áreas do sistema.

## Exemplo prático: provedor fictício ProvedorX
O **ProvedorX** quer certificar o serviço de suporte ao cliente na ISO 20000-1.

- **Cláusula 4 (contexto):** o levantamento mostra reclamações de queda no fim de semana, multa por prazo de reparo e dependência de um sistema legado de cadastro. Escopo definido: suporte ao cliente residencial e a central de atendimento. O suporte corporativo fica fora e é registrado como risco aceito para a próxima fase.
- **Cláusula 5 (liderança):** o diretor assina a política e o termo de compromisso. Ele aprova o orçamento para uma ferramenta de monitoramento que abre chamado sozinha, ou registra por escrito que não aprova e aceita o risco.
- **Cláusula 6 (planejamento):** o objetivo é "reduzir a indisponibilidade percebida pelo cliente". O indicador que a direção recebe mensalmente é a **disponibilidade do acesso** e o **faturamento estimado perdido** nas quedas. Esse relatório já é combinado agora para que a cláusula 9 não dependa de planilha manual.
- **Cláusula 8.5 e 8.6:** mudanças na rede passam por registro; um KPI mede quantas mudanças geraram **incidente em até 72 horas**. Incidentes recorrentes viram **problema** com causa raiz.
- **Cláusula 8.7:** o plano de continuidade tem teste anual, e a segurança da informação segue a 27001.
- **Cláusulas 9 e 10:** auditoria interna trimestral e reunião de análise crítica com a direção. Cada não conformidade vira ação corretiva com prazo.

## Como se conecta com o resto
- **Aula 03 (frameworks):** a 20000-1 é a norma certificável de gestão de serviços; o ITIL é a caixa de boas práticas.
- **Aula 05 (ITIL 4):** o princípio "comece de onde você está" aparece aqui na forma de tratar o **legado** (não jogar fora o que existe).
- **Aulas 08 e 09 (gestão de incidentes):** a subcláusula 8.6 é o requisito, a prática de incidentes do ITIL é o como.
- **COBIT 2019:** a aula usou o COBIT para separar **governar** (avaliar, dirigir, monitorar) de **gerir**. O COBIT trabalha com objetivos de governança e gestão; o ITIL com práticas.
- **ISO 27001, 22301, 27701:** mesma estrutura de alto nível, então o sistema de gestão pode ser integrado.
- **Aula 07 e aula 54:** ITIL 5, IA e governança de IA aprofundam o que a aula só apresentou.

## Pegadinhas de prova
- **HLS** é *High Level Structure* (estrutura de alto nível, Anexo SL). Não é "statement".
- **Parte 1 certifica; parte 2 orienta.** Quem certifica é a ISO/IEC 20000-1.
- A ISO exige **requisitos** (o que), o ITIL dá **práticas** (como). Prática não é processo.
- **Cláusulas:** 4 contexto, 5 liderança, 6 planejamento, 7 apoio, 8 operação, 9 avaliação de desempenho, 10 melhoria. Na ordem PDCA: 4 a 6 planejar, 7 e 8 executar, 9 verificar, 10 agir.
- **Risco:** na ISO 31000, risco é o **efeito da incerteza nos objetivos**. A aula usou "probabilidade de não atingir os objetivos", que é uma forma simplificada.
- **Declaração de aplicabilidade** é um conceito da **ISO 27001**. Na 20000-1, o que delimita o sistema é o **escopo** da cláusula 4.
- Tratar o risco inclui **aceitar**, mas o risco aceito continua registrado.
- Certificação vale mais quando a certificadora é **acreditada** por critérios internacionais. Se não for, pode não ser aceita por concorrência ou cliente internacional.
- O ITIL (Version 5) não trocou a ISO: a 20000-1 continua na edição de **2018**.
- A estatística "95% das implantações falham" não tem fonte. Não use como dado em prova ou apresentação.

## Perguntas de revisão
1. Qual é a diferença entre a ISO/IEC 20000-1 e a 20000-2?
2. O que é a estrutura de alto nível e qual a vantagem de todas as ISO de sistema de gestão a usarem?
3. Cite as cláusulas 4 a 10 e diga a que fase do PDCA pertencem.
4. Quais são os sete grupos da cláusula 8?
5. Por que o professor diz que escopo, compromisso da direção e ferramentas devem ser definidos logo no começo?
6. Quais são os 6 passos para usar ISO 20000 e ITIL juntos?

<details><summary>Respostas</summary>

1. A parte 1 traz os requisitos e é certificável. A parte 2 é um código de prática com orientações para implementar, e não certifica.
2. É um índice padrão (cláusulas 1 a 10) que as normas ISO de sistema de gestão compartilham. Facilita integrar o sistema de serviços com segurança, qualidade e continuidade.
3. Contexto, liderança e planejamento (4 a 6): planejar. Apoio e operação (7 e 8): executar. Avaliação de desempenho (9): verificar. Melhoria (10): agir.
4. Planejamento e controle operacional; portfólio de serviços; relacionamento e acordo; oferta e demanda; desenho, construção e transição; resolução e atendimento; garantia do serviço.
5. Porque as cláusulas 9 e 10 só medem e melhoram o que foi combinado antes. Sem escopo, orçamento e indicadores acordados com a direção, depois não há recurso para ferramentas nem relatórios, e o risco fica sem dono.
6. Definir o escopo; mapear as práticas ITIL; montar as cadeias de valor; implementar o PDCA; medir, auditar e melhorar; integrar com outras normas.
</details>

## Fontes de conferência
- [Glocert: ISO 20000-1 requirements explained](https://www.glocertinternational.com/resources/guides/iso-20000-1-requirements-explained/) (cláusulas 4 a 10 e subcláusulas 8.1 a 8.7).
- [InvGate: ITIL 5 vs ITIL 4](https://blog.invgate.com/itil-5-what-changes) (34 práticas, modelo 6C, foco em produtos e serviços digitais).
