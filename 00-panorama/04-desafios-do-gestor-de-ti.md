# Desafios do gestor de TI

> **Fonte:** TIexames · Gianni Ricciardi (MSc, PhD) · live "Como lidar com os desafios atuais do Gestor de TI" (fev/2024) · [vídeo no YouTube](https://youtu.be/KlgMY0JfNpM) · assistida em 10/2026
> **Tema:** Panorama · o papel do gestor de TI
> *Este vídeo não tem legenda automática. A nota foi feita a partir das minhas anotações e dos slides da aula, complementada com explicação geral.*

## Em uma frase
O gestor de TI vive entre **projetos e operações**, responde ao board pelo que a TI entrega e precisa equilibrar **pessoas, decisões de tecnologia (fazer ou comprar), GRC e dados**, usando padrões (ISO, frameworks) como apoio, não como burocracia.

## Os quatro desafios da aula
1. **Pessoas:** liderança, gerações diferentes trabalhando juntas (inclusive a geração Z) e a chamada sociedade 5.0 (tecnologia a serviço das pessoas).
2. **Tecnologia:** a decisão de **fazer ou comprar** (*make or buy*), SaaS e o risco de **Shadow IT**.
3. **GRC:** governança adaptativa, riscos cibernéticos, padrões e compliance.
4. **Governança de dados:** como usar uma norma ISO para estruturar esse tema.

## Explicação simples

### Projetos e operações, guiados pela governança
O slide central é o modelo da **ISO/IEC 38500**: a governança corporativa de TI **avalia, dirige e monitora**.
- Recebe **pressões e necessidades do negócio**.
- **Dirige** com planos e políticas.
- Recebe **propostas** de quem executa.
- **Monitora** desempenho e conformidade.

Embaixo, a missão da gestão de TI se divide em **projetos de TI** e **operações de TI**. Todo projeto vira operação quando entra em produção, e muitas operações geram novos projetos de melhoria.

**Princípios (atenção à versão):** a aula, de fevereiro de 2024, usa a ISO/IEC 38500:2015, com **6 princípios**: responsabilidade, estratégia, aquisição, desempenho, conformidade e comportamento humano. A **ISO/IEC 38500:2024** alinhou a norma à **ISO 37000** (governança de organizações): passou a ter **11 princípios** (propósito, geração de valor, estratégia, supervisão, prestação de contas, engajamento das partes interessadas, liderança, dados e decisões, governança de riscos, responsabilidade social, viabilidade e desempenho ao longo do tempo), incluiu o engajamento das partes interessadas e ampliou o escopo para uso de dados, questões ambientais e sociais e IA.

### O gestor de TI responde pela entrega
Gestor de TI gosta de novidade e inovação, mas **representa o board** e tem a responsabilidade de entregar. Montar uma estrutura de TI que seja **robusta e flexível ao mesmo tempo** é difícil.

### Fazer ou comprar (make or buy)
Matriz que cruza **desempenho atual** (fraco ou forte) com **diferenciação** (commodity ou diferencial para o negócio):

| | Commodity | Diferencial |
|---|---|---|
| **Desempenho forte** | Terceirizar para focar | Manter dentro de casa |
| **Desempenho fraco** | Terceirizar por custo | Parceria (aliança) |

Regra prática: o que é **diferencial** fica perto (em casa ou com parceiro); o que é **commodity** pode ir para fora.

### SaaS e Shadow IT
Software como serviço é fácil de contratar com um cartão de crédito. Quando uma área assina sem a TI saber, isso vira **Shadow IT**: dados da empresa em lugares sem controle, contratos sem análise e riscos de segurança e de LGPD.

### Agilidade e controle juntos
Um dos slides junta **IT4IT** (modelo do Open Group para gerir a TI como uma cadeia de valor), **Design Thinking**, **Scrum** e **DevSecOps** (desenvolvimento, segurança e operação juntos). Do lado, as obrigações: **ISO 27000, ISO 20000, LGPD e regulatório**. A ideia é que agilidade não dispensa conformidade: a segurança e as regras entram no ciclo, não no fim.

### Governança adaptativa (DPBoK)
O **DPBoK** (Digital Practitioner Body of Knowledge, do Open Group) mostra a TI amadurecendo em camadas:
- **Fundador:** fundamentos digitais, infraestrutura, entrega de aplicativos.
- **Time:** produtos (Scrum), trabalho (PMBOK) e operações (ITIL).
- **Time de times:** processos (SAFe), investimentos (OKR) e cultura (IT4IT).
- **Corporação:** GRC, informação e arquitetura.

Em cada camada aparece uma norma de apoio: ISO 20000 em operações, família ISO 27000 e ISO 38500 em governança, risco e compliance, e assim por diante. A governança "adapta" o peso dos controles ao tamanho e à maturidade da empresa.

### Governança de dados com a ISO/IEC 38505-1
A **ISO/IEC 38505-1** aplica a ISO 38500 aos **dados**. Ela traz:
- termos e definições;
- contribuições da boa governança de dados;
- responsabilidades do corpo diretivo;
- estrutura e mecanismos de supervisão;
- princípios e modelo;
- responsabilização pelos dados.

O modelo usa o mesmo avaliar-dirigir-monitorar, ligado a classificação dos dados, perfil de risco, tecnologia e prestação de contas.

**Ciclo de responsabilidade dos dados:** coletar → armazenar → relatar → decidir → distribuir → descartar. A norma sugere controles para cada etapa, e serve tanto para **estruturar** a governança de dados quanto para **auditar** a empresa ou seus fornecedores.

### O gestor e os produtos digitais
O gestor de TI cuida de boa parte do **ciclo de vida do produto digital**:
- **Ciclo do sistema:** avaliar → explorar → integrar → implantar → operar.
- **Ciclo do contrato:** liberar → consumir → comprar ou assinar → cobrar e dar suporte.

O IT4IT 3.0 detalha isso em **7 fluxos de valor**: avaliar, explorar, integrar, implantar, liberar, consumir e operar.

## Exemplo prático: uma transportadora (fictícia)
- **Fazer ou comprar:** o sistema de roteirização das entregas é **diferencial** e fica em casa. A folha de pagamento e o e-mail corporativo são **commodity** e podem ser SaaS.
- **Shadow IT:** os motoristas começam a usar um grupo de mensagens com fotos dos comprovantes de entrega e endereços de clientes. A TI precisa saber, avaliar o risco (LGPD) e oferecer uma alternativa aprovada.
- **Governança de dados:** para os dados de entrega, a empresa define quem pode **coletar** (cadastro do pedido), onde **armazena** (sistema de gestão), quem **relata** (indicadores), quem **decide** com eles, para quem **distribui** (parceiros de última milha) e quando **descarta** (prazo legal).
- **Projeto vira operação:** a implantação de rastreio em tempo real é um projeto; quando termina, vira rotina da operação, e os problemas da rotina viram novos projetos de melhoria.

## Como se conecta com o resto
- **Aula 03:** ISO 27001, NIST e CIS são as "ferramentas" de segurança que o gestor escolhe.
- **COBIT 2019:** o domínio **EDM** (avaliar, dirigir, monitorar) segue a mesma lógica da ISO 38500. APO10 trata de fornecedores (fazer ou comprar).
- **ITIL:** gestão de fornecedores, de catálogo e de mudanças.
- **Trilha:** aula 13 (ISO/IEC 38500:2025), aula 42 (ISO/IEC 38507, governança de IA) e as aulas de governança de dados.
- **LGPD:** o ciclo de vida dos dados conversa direto com o tratamento de dados pessoais.

## Pegadinhas de prova
- **Família 38500:** 38500 é governança de TI; **38505-1** é governança de **dados**; 38506 trata de investimentos em TI; **38507** é governança de **IA**.
- **Governança × gestão:** avaliar, dirigir e monitorar é **governança** (corpo diretivo). Planejar, construir, executar e monitorar é **gestão**.
- **Versão da ISO 38500:** a de **2015** tem **6 princípios**; a de **2024** tem **11**, os mesmos da ISO 37000. Na prova, confira qual versão o exame cobra.
- **Shadow IT** não é "TI pirata" só por ser grátis: é qualquer tecnologia usada sem conhecimento ou aprovação da área responsável.

## Perguntas de revisão
1. Quais são as três ações da governança de TI segundo a ISO/IEC 38500?
2. Quais eram os 6 princípios da ISO/IEC 38500:2015, e o que mudou na versão 2024?
3. Na matriz de fazer ou comprar, o que fazer com algo que é diferencial para o negócio, mas em que a empresa ainda tem desempenho fraco?
4. O que é Shadow IT e por que é um risco?
5. Qual norma aplica a ISO 38500 à governança de dados, e quais são as etapas do ciclo de responsabilidade dos dados?
6. Por que se diz que "todo projeto vira operação"?

<details><summary>Respostas</summary>

1. Avaliar, dirigir e monitorar.
2. Responsabilidade, estratégia, aquisição, desempenho, conformidade e comportamento humano. A versão 2024 passou a usar os 11 princípios da ISO 37000 (governança de organizações).
3. Buscar uma parceria (aliança), para ganhar desempenho sem abrir mão do que diferencia a empresa.
4. É tecnologia usada sem conhecimento ou aprovação da área responsável. Expõe dados, cria contratos sem análise e foge dos controles de segurança e da LGPD.
5. ISO/IEC 38505-1. Coletar, armazenar, relatar, decidir, distribuir e descartar.
6. Porque, ao ser entregue, o resultado do projeto passa a ser mantido no dia a dia pela operação.
</details>
