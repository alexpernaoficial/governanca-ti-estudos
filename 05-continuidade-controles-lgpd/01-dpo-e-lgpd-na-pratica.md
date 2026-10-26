# DPO e LGPD na prática

> **Fonte:** Ka Solution · Aulão "DPO & LGPD na prática" · aula ao vivo em 24/10/2026 (208 min) · certificado de conclusão recebido em 26/10/2026
> **Tema:** LGPD · Privacidade · DPO

Crédito do conteúdo: Ka Solution. Esta nota é uma **visão geral do tema**, escrita com as minhas palavras a partir do título e da proposta da aula e de fontes públicas (texto da LGPD e regulamento da ANPD). Não é um resumo detalhado do que foi dito ao vivo.

## Em uma frase
O DPO (encarregado de dados) é a ponte entre a organização, as pessoas cujos dados são tratados e a ANPD, e a LGPD só funciona na prática quando existe rotina: saber quais dados a organização tem, por que os trata e como responde quando alguém pergunta.

## O que é
- **LGPD** (Lei 13.709/2018): regra brasileira de proteção de dados pessoais. Define princípios, bases legais, direitos dos titulares e deveres de quem trata dados.
- **ANPD**: a autoridade que fiscaliza e regulamenta a LGPD.
- **Encarregado (DPO)**: pessoa indicada pelo controlador para atuar como canal de comunicação com os titulares e com a ANPD (art. 41 da LGPD). A ANPD detalhou o papel na Resolução CD/ANPD nº 18/2024.
- **Controlador e operador**: o controlador decide sobre o tratamento; o operador trata em nome dele.

## Explicação simples
Pense no DPO como o "ponto de contato de privacidade" da organização:
1. **Recebe** pedidos e reclamações dos titulares (acesso, correção, exclusão).
2. **Conversa** com a ANPD quando ela pede informações.
3. **Orienta** as pessoas da organização sobre as boas práticas.
4. **Enxerga o conjunto:** quais dados existem, onde estão e com quem são compartilhados.

Na prática, isso se apoia em poucas rotinas: inventário dos dados, registro das operações de tratamento, escolha da base legal de cada uso, resposta a pedidos dos titulares, avaliação de risco e plano para incidentes de segurança.

## Exemplo prático: clínica odontológica (fictício)
A clínica Sorriso Claro guarda ficha, exames e contato dos pacientes.
- **Inventário:** lista onde estão os dados (sistema, planilha, WhatsApp da recepção).
- **Base legal:** prontuário vem da obrigação legal e da tutela da saúde; o lembrete de promoção precisa de outro fundamento e de uma forma simples de o paciente sair da lista.
- **Pedido de titular:** um paciente pede cópia da ficha. O DPO sabe a quem pedir, confere a identidade e responde no prazo.
- **Incidente:** o computador da recepção é perdido. O DPO coordena a avaliação do risco e decide, com a direção, se é preciso avisar os pacientes e a ANPD.

## Como se conecta com o resto
- **Governança de TI:** privacidade é um tipo de risco e de controle, e entra no mesmo desenho de governança.
- **ISO 27001 e controles:** segurança da informação protege os dados, e a LGPD exige medidas de segurança.
- **Governança de IA:** as ferramentas de IA tratam dados pessoais, então o inventário e a avaliação de risco precisam incluir elas (ver a nota do programa de privacidade na era da IA).

## Pegadinhas de prova
- Encarregado (DPO) **não é** quem responde juridicamente por tudo: a responsabilidade é do controlador.
- Consentimento **não é** a única base legal: a LGPD tem várias.
- Controlador e operador são papéis diferentes: quem decide x quem executa em nome de outro.
- A ANPD **regulamenta e fiscaliza**; o DPO **faz a ponte**.

## Perguntas de revisão
1. Quem indica o encarregado e qual é o papel dele?
2. Qual a diferença entre controlador e operador?
3. Cite três bases legais da LGPD além do consentimento.
4. O que o DPO deve fazer ao saber de um incidente de segurança com dados pessoais?

<details><summary>Respostas</summary>

1. O controlador indica. O encarregado é o canal de comunicação com os titulares e com a ANPD, além de orientar a organização (art. 41).
2. O controlador decide sobre o tratamento; o operador trata os dados em nome do controlador.
3. Por exemplo: cumprimento de obrigação legal, execução de contrato, legítimo interesse, tutela da saúde.
4. Acionar o plano de incidentes: avaliar o risco para os titulares, registrar o fato e, quando o risco for relevante, comunicar a ANPD e os titulares, conforme a regulamentação.
</details>

## Fontes
- Lei 13.709/2018 (LGPD), art. 41 e art. 5
- Resolução CD/ANPD nº 18, de 16/07/2024 (regulamento do encarregado)
