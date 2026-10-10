# Comparando frameworks: NIST CSF, ISO/IEC 27001 e CIS Controls

> **Fonte:** TIexames · Rafael (participa do comitê da ABNT/ISO de segurança da informação), com Carlos e Flávio · [vídeo no YouTube](https://youtu.be/lpaWoFS33Bg) · assistida em 10/2026
> **Tema:** Panorama · frameworks de segurança da informação

## Em uma frase
Framework é uma **caixa de ferramentas**: o bom profissional conhece os principais e sabe **qual usar para cada problema**. CIS para começar rápido, ISO 27001 quando precisa de certificado, NIST CSF quando quer segurança robusta e flexível sem selo.

## O que é um framework de segurança
Um conjunto estruturado de diretrizes, boas práticas, padrões e **controles** (medida de segurança = controle) já testados por milhares de profissionais. É um atalho: em vez de inventar o seu modelo, você investe o tempo em **implementar**.

**O que todo framework tem**, com mais ou menos ênfase:
1. **Diretrizes e políticas** (as regras do jogo)
2. **Controles de segurança** (o "mapa da mina": o que fazer na prática)
3. **Processo de gestão** (medir, conferir, melhorar)
4. **Auditoria** (de um colega de outra área até um organismo certificador)

**O que você ganha:** abordagem estruturada, redução de riscos, melhoria contínua e **confiança e credibilidade** diante de clientes, parceiros e reguladores.

**Por que o risco vem primeiro:** todo framework começa por identificar riscos, para proteger o que importa. Ninguém coloca a camisa no cofre do hotel; coloca o relógio e o passaporte.

**"Envidar os melhores esforços":** a LGPD e outras leis cobram que a empresa prove que fez o possível. O framework gera essa **evidência**. Analogia da aula: em um acidente de carro, quem estava com revisão em dia, sóbrio e dentro do limite se defende; quem estava com pneu careca e carteira apreendida, não.

## Os três principais

### ISO/IEC 27001 (família 27000)
- **Quem faz:** ISO + IEC, juntas. A ISO foi criada em 1947, depois de uma conferência em Londres em 1946, e tem sede em Genebra. A IEC é de 1906. No Brasil, a representante é a **ABNT**, que traduz as normas (ABNT NBR ISO/IEC 27001).
- **Família:** 27000 (vocabulário), **27001 (requisitos, é a que certifica)**, **27002 (explica cada controle)**, 27005 (riscos de segurança), 27017 (nuvem), 27018 (dados pessoais na nuvem), 27701 (privacidade), **27011 (telecomunicações)**, 27004 (métricas), 27006 (requisitos para quem certifica), entre outras.
- **Base:** tríade **CID** (confidencialidade, integridade, disponibilidade) e ciclo **PDCA**.
- **Versão 2022:** **93 controles em 4 temas** no Anexo A: organizacionais (37), pessoas (8), físicos (14) e tecnológicos (34). Em 2024 saiu uma emenda que incluiu a mudança climática na análise de contexto.
- **Vantagens:** **certificável** e aceita no mundo todo (se o certificador for acreditado conforme a ISO 27006); estrutura clara; dá para certificar só um **escopo** (uma unidade, um data center).
- **Desvantagens:** **cara** (a norma é paga e a auditoria também) e **demorada** (pode passar de um ano); exige evidência de tudo e uma equipe de segurança estruturada.

### CIS Controls
- **Quem faz:** **Center for Internet Security** desde 2015. Nasceu em 2008 no **SANS Institute** como "20 controles críticos" e passou pelo Council on CyberSecurity.
- **Versão:** v8 (2021), atualizada para **v8.1 (2024)**: **18 controles e 153 medidas** (*safeguards*).
- **Grupos de implementação (cumulativos):**
  - **IG1, "higiene básica":** 56 medidas, para empresas pequenas.
  - **IG2:** +74, total de **130 medidas**.
  - **IG3:** +23, total de **153 medidas**.
- **Vantagens:** direto ("leia e faça"); **gratuito**, com planilha de autoavaliação e modelos de política; rápido de implementar; mapeado para ISO e NIST. O IG1 já costuma ser o mínimo que uma seguradora pede para **seguro cibernético**.
- **Desvantagens:** quase não trata de políticas nem de segurança física; fica limitado em empresas grandes e complexas.

### NIST CSF (Cybersecurity Framework)
- **Quem faz:** **NIST**, agência do Departamento de Comércio dos EUA (antigo National Bureau of Standards). Criado para empresas que fazem negócio com o governo americano; ficou tão bom que virou padrão global.
- **Versão:** **CSF 2.0 (fevereiro de 2024)**. A versão 1.0 é de 2014.
- **Funções:**
  - **Governar** (nova na 2.0; a função de políticas e governança, que antes faltava)
  - **Identificar** (ativos, inventário, riscos)
  - **Proteger** (acesso, configuração, firewall, treinamento)
  - **Detectar** (monitoramento e análise de eventos)
  - **Responder** (análise, contenção, comunicação do incidente)
  - **Recuperar** (voltar ao normal)
- As funções se dividem em **categorias** e **subcategorias**.
- **Documentos de apoio gratuitos:** série **SP 800** (ex.: **SP 800-53**, catálogo de controles de segurança e privacidade, o "par" do CSF como a 27002 é da 27001), série **SP 1800** (guias práticos) e série SP 500.
- **Vantagens:** usado no mundo todo, fácil de entender, adaptável, muito bem documentado e **conversa bem com os outros frameworks** ("tem APIs", brincou o professor).
- **Desvantagens:** **não existe selo ou certificado NIST** (dá para fazer auditoria ou assessment, mas não há um certificado oficial); complexo para empresa pequena; foco cibernético, com pouco sobre papel e segurança física.

## Como responder a incidente sem ter incidente
Pergunta da turma: como implementar Detectar, Responder e Recuperar se nunca houve incidente? Resposta: **simulando**. Monte cenários, teste sem avisar as pessoas, meça o tempo e corrija. É como o estepe: não basta ter, precisa estar calibrado e você precisa saber trocar. Bombeiro treina com fogo de verdade. Exemplo da aula: a meta era recuperar o ambiente em 4 h, o primeiro teste levou 3,5 dias e cada teste mostrou o que documentar ou automatizar.

## Outros frameworks que vale conhecer de nome
| Framework | Para quê | Observação |
|---|---|---|
| **COBIT 2019** (ISACA) | Governança de TI, alinhando TI e negócio; segurança é só uma parte | Exige maturidade de governança. Não certifica empresa, só profissionais |
| **PCI DSS** (v4.0.1) | Dados de cartão de pagamento | Obrigatório para quem armazena, processa ou transmite dados de cartão, incluindo lojistas, com nível de exigência proporcional ao volume |
| **SOC 2** (AICPA) | Relatório de auditoria sobre controles para dados de clientes | Muito pedido a provedores de nuvem e SaaS. Tipos **I** (desenho dos controles num momento) e **II** (funcionamento ao longo de um período) |
| **HITRUST** | Setor de saúde | Combina HIPAA, ISO e NIST |
| **ITIL** | Gestão de serviços de TI | Não é framework de segurança, mas tem práticas de segurança |
| **COSO** | Controles internos e riscos corporativos | Muito usado por auditoria e finanças |

São mais de 27 frameworks documentados. Ninguém conhece todos; foque nos principais.

## Quando usar cada um
| Situação | Escolha |
|---|---|
| Empresa pequena ou média, pouca gente de TI, precisa de resultado rápido | **CIS Controls** (comece pelo IG1) |
| Precisa **provar** para clientes ou reguladores com certificado; atua em vários países | **ISO/IEC 27001** (padroniza a linguagem com todos) |
| Foco cibernético, quer combinar com outros frameworks e não precisa de selo | **NIST CSF** |
| Cartão, saúde, nuvem | PCI DSS, HITRUST, SOC 2 (em cima de ISO ou NIST) |

**ISO e NIST estão no mesmo nível** ("primos"). Ir de um para o outro não é "evoluir", é mudar o jeito de fazer, e dá retrabalho. Já sair do **CIS para ISO ou NIST** é, de fato, amadurecer. Segundo a aula, a maioria dos bancos segue a ISO sem ter o certificado, porque não precisa dele.

**O que todos têm em comum:** abordagem baseada em risco, proteção dos ativos mais críticos, conformidade (mostrar que leva segurança a sério) e melhoria contínua.

## Exemplo no ProvedorX (empresa fictícia)
- **Começo rápido:** o ProvedorX usa o **IG1 do CIS** (inventário de equipamentos e softwares, MFA para acesso administrativo, backup testado, atualização de firmware dos roteadores) e já consegue cotar seguro cibernético.
- **Organização:** usa as funções do **NIST CSF 2.0** para organizar o programa: Governar (política e papéis), Identificar (inventário de OLTs, roteadores de borda e sistemas contratados), Proteger, Detectar (monitoramento de rede), Responder (plano para queda massiva ou ataque DDoS) e Recuperar.
- **Certificação:** se um grande cliente corporativo exigir certificado, o ProvedorX certifica na **ISO 27001** só o escopo do data center e do NOC, olhando também a **ISO/IEC 27011**, específica para telecom.
- **Teste:** simula uma queda do sistema de gestão sem avisar a equipe e mede quanto tempo leva para voltar.

## Como se conecta com o resto
- **Aula 01:** "primeiro os riscos, depois os controles" é exatamente como os frameworks começam.
- **COBIT 2019:** APO13 (gestão de segurança) e DSS05 (serviços de segurança). O NIST pode ser o "motor" de segurança dentro de uma governança COBIT.
- **ITIL:** gestão de incidentes conversa com as funções Detectar, Responder e Recuperar.
- **LGPD:** "melhores esforços" e evidências; para privacidade, ISO/IEC 27701.
- **Próximos estudos:** ISO 27001 (fase 4), CIS Controls v8.1 (fase 5) e ISO 27005 / NIST RMF (fase 3).

## Pegadinhas de prova
- **ISO 27001 × 27002:** a 27001 traz os **requisitos** e é a que **certifica**; a 27002 **orienta** a implementação dos controles e não certifica.
- **NIST CSF não tem certificação oficial.** Quem diz "sou certificado NIST" está falando de um assessment feito por terceiros.
- **CSF 2.0 tem 6 funções**, com **Governar** como novidade. A 1.1 tinha 5.
- **Níveis de implementação do CSF** (*tiers*: Parcial, Informado por riscos, Repetível, Adaptativo) **não são certificação**. Os "níveis" exigidos para fornecer ao Departamento de Defesa dos EUA são do **CMMC**, baseado na NIST SP 800-171.
- **CIS: IGs são cumulativos** (56 → 130 → 153 medidas). O IG2 não tem 130 medidas "novas".
- **SOC 2 é relatório de atestação** (Tipo I e II), não "tier 1, 2, 3".
- **ISO/IEC 27701:2025** (publicada em outubro de 2025) virou **norma independente**; a versão de 2019 era extensão da 27001.
- **PCI DSS vale para lojistas também**, não só para processadoras e bandeiras.

## Perguntas de revisão
1. Quais são os 4 componentes que todo framework de segurança tem?
2. Qual a diferença entre a ISO/IEC 27001 e a ISO/IEC 27002?
3. Quais são as 6 funções do NIST CSF 2.0 e qual é a nova?
4. O que significa o IG1 do CIS Controls e quantas medidas ele tem?
5. Uma empresa pequena, sem área de segurança, precisa melhorar rápido. Qual framework e por quê?
6. Por que um provedor de nuvem costuma ter ISO 27001 e SOC 2, mas nenhum selo NIST?

<details><summary>Respostas</summary>

1. Diretrizes e políticas, controles de segurança, processo de gestão e auditoria.
2. A 27001 define os requisitos do sistema de gestão e é a que certifica; a 27002 explica em detalhe como implementar cada controle.
3. Governar (nova), Identificar, Proteger, Detectar, Responder e Recuperar.
4. É a "higiene básica", o grupo mínimo para empresas pequenas, com 56 medidas.
5. CIS Controls, começando pelo IG1: é gratuito, direto e rápido de implementar, com planilha de autoavaliação.
6. Porque ISO 27001 e SOC 2 geram certificado ou relatório formal que evita que cada cliente audite o provedor; o NIST não tem certificação oficial.
</details>
