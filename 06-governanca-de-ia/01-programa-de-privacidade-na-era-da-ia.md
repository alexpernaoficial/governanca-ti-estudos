# Desenhando um programa de privacidade para a era da IA

> **Fonte:** TIexames e DataUX · Masterclass gratuita com o Prof. Matheus Passos · [vídeo](https://www.youtube.com/watch?v=R0s0hidUCjI) · assistida em 19/10/2026
> **Tema:** IA · LGPD · Privacidade

Crédito do conteúdo: Prof. Matheus Passos, TIexames e DataUX. Esta nota é um resumo com as minhas palavras, a partir da aula e dos slides disponibilizados no site da TIexames.

## Em uma frase
Quem já tem um programa de privacidade não precisa refazê-lo para a IA: precisa acrescentar uma camada de IA em cada etapa (governar, avaliar, proteger, responder e manter).

## O que é
Um programa de privacidade é o conjunto de políticas, papéis, registros e rotinas que mostra que a organização trata dados pessoais com responsabilidade. A aula propõe um mapa em cinco blocos, com 17 partes e 14 entregáveis, em que cada parte tem uma versão "de privacidade" e uma "camada de IA".

## Explicação simples

### Por que mudar agora
- O objeto do programa mudou. Antes o dado ficava parado (formulário, banco, CRM). Hoje ele circula e age: treino, busca aumentada (RAG), prompts, saídas, logs e agentes.
- Duas agendas se cruzaram: proteção de dados (RGPD, LGPD) e regulação de IA (ISO 42001, AI Act, PL 2338). Pedem respostas integradas: um inventário que fale de dados e de modelos.
- O profissional híbrido já existe: na pesquisa da IAPP citada, cerca de um terço já responde por privacidade e por governança de IA.
- Casos recentes citados: ANPD x Meta (suspensão do treino com dados de brasileiros, liberado depois com opt-out e transparência), Garante italiana x OpenAI (multa de 15 milhões de euros, depois contestada na Justiça) e autoridade holandesa x Clearview AI (30,5 milhões de euros por base biométrica feita por raspagem de imagens).

### As oito janelas de entrada da IA
A IA raramente entra pela "porta da frente" (o projeto aprovado em comitê). Ela entra por janelas:
1. SaaS com assistente de IA embutido e ativado por padrão
2. Navegador e extensões
3. Cláusula do fornecedor ("para melhorar nossos serviços")
4. E-mail e mensagens com resumo e resposta automáticos
5. Celular e apps (teclado com IA)
6. Desenvolvedor e API de LLM em produção
7. Marketing (segmentação e perfilamento)
8. RH (triagem de currículos, decisão automatizada, art. 20 da LGPD)

Regra prática: quem assina, instala ou ativa a IA raramente é quem responde por ela. Por isso o inventário de IA começa pelas janelas.

### Contexto global e Brasil (resumo)
- Três modelos: EUA setorial e estadual, UE horizontal por risco, China por tecnologia. O Brasil caminha para o modelo europeu.
- EU AI Act: quatro camadas de risco (inaceitável, alto, transparência, mínimo) e calendário escalonado; a aula cita que o alto risco do Anexo III foi adiado pelo Omnibus.
- EDPB, Opinion 28/2024: treinar modelo pode caber em legítimo interesse, com teste de três etapas. É interpretação do RGPD; não vale transportar automaticamente para a LGPD.
- Brasil já tem base: LGPD (art. 6 princípios, art. 20 decisão automatizada, art. 46 segurança), Resolução 15/2024 (incidentes em 3 dias úteis, quando há risco relevante), Resolução 19/2024 (transferência internacional), Guia de legítimo interesse, ECA Digital e adequação UE-Brasil (Res. 32/2026).
- PL 2338/2023: aprovado no Senado em dez/2024 e em análise na Câmara (segundo o slide, verificado em 15/10/2026). Mesmo sem ele, o gestor já tem obrigações.

### O mapa do programa (5 blocos, 14 entregáveis)
- **Governar:** charter, estrutura de governança e RACI, declaração de escopo (as oito janelas entram aqui), política integrada e política de uso de IA, plano de treinamento e letramento em IA.
- **Avaliar:** RoPA com campos de IA, inventário de sistemas de IA, matriz de bases legais, questionário de fornecedores de IA, RIPD e avaliação de impacto de IA.
- **Proteger:** checklist de privacy by design e supervisão humana, matriz de controles (OWASP Top 10 para LLM, MITRE ATLAS), adendo contratual de IA, política de retenção (prompts, logs, bases vetoriais).
- **Responder:** procedimento de direitos ("exclusão não é unlearning"), playbooks de incidentes com IA (vazamento por prompt, exfiltração por agente).
- **Manter:** painel de KPI e KRI, auditoria, radar regulatório, monitoramento de modelos e desativação.

Quem opera: comitê de privacidade e IA decide; Encarregado e líder de governança de IA orientam; segurança, TI, jurídico, compras e donos de processo executam.

### A régua de maturidade
- Privacy Maturity Model (AICPA/CICA, 2011): cinco níveis (ad hoc, repetível, definido, gerenciado, otimizado). Boa para privacidade, rasa para IA.
- MITRE AI Maturity Model: seis pilares, 20 dimensões, cinco níveis, público e gratuito, com ferramenta de autoavaliação. A correspondência pilar-bloco do mapa é proposta pelo curso, não pelo MITRE.
- A aula fecha com uma autoavaliação de sim ou não (por exemplo: existe política aprovada sobre o que a IA pode fazer com dados pessoais? A IA aparece no escopo e no orçamento do programa?).

## Exemplo prático: rede de escolas (fictício)
A Rede Escolar Girassol já tem RoPA e encarregado. Ao aplicar a camada de IA:
- Descobre, pelas janelas, que a coordenação usa um chatbot gratuito para resumir relatórios de alunos (janela 8/5) e que o sistema de matrículas ligou um assistente por padrão (janela 1).
- Inclui "treino, RAG ou decisão automatizada?" nos campos do RoPA e abre um inventário de IA com dono por sistema.
- Faz RIPD e avaliação de impacto para o assistente que sugere bolsas (decisão automatizada, art. 20), com supervisão humana.
- Como atende menores, considera o ECA Digital (verificação de idade proporcional, sem perfilamento publicitário).
- Revisa o contrato do fornecedor: sem uso dos dados para treino, sem retenção de prompts, aviso prévio de mudança de termos.

## Como se conecta com o resto
- ISO 27001 e 27701:2025: base da política integrada; 42001 compartilha a estrutura de sistema de gestão.
- COBIT e ITIL: papéis, RACI, gestão de fornecedores e de incidentes.
- LGPD: arts. 6, 7, 11, 20 e 46 aparecem em quase todo bloco.
- Gestão de riscos: RIPD e avaliação de impacto de IA (ISO 42005) são avaliações de risco aos titulares.

## Pegadinhas de prova
- Excluir o dado do titular não é o mesmo que desaprender o modelo ("unlearning").
- Opt-out sozinho não sustenta o legítimo interesse; dado sensível não usa essa base.
- O art. 20 da LGPD vale para decisões unicamente automatizadas, com ou sem IA.
- Nem toda saída discriminatória é incidente notificável: classifique antes de comunicar.
- A opinião do EDPB é sobre o RGPD, não sobre a LGPD.
- A correspondência MITRE x mapa é do curso, não do MITRE.

## Perguntas de revisão
1. O que muda no objeto do programa de privacidade entre 2020 e 2026?
2. Cite quatro das oito janelas de entrada da IA e quem deveria percebê-las.
3. Por que o inventário de IA começa pelas janelas e não pela "porta da frente"?
4. Quais são os cinco blocos do mapa e um entregável de cada?
5. O que a Resolução 15/2024 exige em caso de incidente?
6. Por que a régua da AICPA é "rasa para IA" e o que o MITRE acrescenta?

<details><summary>Respostas</summary>

1. De dado em repouso (formulário, banco, CRM) para dado em órbita: treino, RAG, prompts, saídas, logs e agentes.
2. Por exemplo: SaaS com IA (compras e privacidade), navegador (TI e segurança), contrato (jurídico e privacidade), RH (privacidade e jurídico).
3. Porque a IA aprovada em comitê é a única que o programa costuma ver; o resto entra por contratos, botões e apps.
4. Governar (charter), Avaliar (inventário de IA), Proteger (matriz de controles), Responder (playbook de incidentes), Manter (painel de KPIs).
5. Em regra, comunicar a ANPD e os titulares em 3 dias úteis quando houver risco ou dano relevante.
6. Os princípios valem, mas não detalham dados de treino, modelos e agentes; o MITRE tem seis pilares e 20 dimensões voltados à IA.
</details>

---
Voltar à [pasta 06](README.md) · [mapa de estudos](../README.md).
