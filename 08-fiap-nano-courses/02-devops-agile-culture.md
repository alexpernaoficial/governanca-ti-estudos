# DevOps & Agile Culture: cultura, métodos ágeis, métricas e modelagem

> **Fonte:** FIAP · Nano Course "DevOps & Agile Culture" (60 h, 5 capítulos) · [página do curso](https://on.fiap.com.br/nano-courses/course/?id=3915) (exige login na plataforma FIAP ON) · concluído em 16/10/2026
> **Tema:** Gestão de TI (cultura DevOps, métodos ágeis, métricas de entrega, UML e casos de uso)
> *Resumo de estudo com minhas palavras, feito com apoio de IA. Os conceitos têm autores próprios, citados na seção "Fonte e referências". O crédito do conteúdo é da FIAP e dos autores.*

## Em uma frase
DevOps e agilidade são uma **cultura** de aproximar desenvolvimento e operação, entregar em ciclos curtos com qualidade, medir o que importa (e não o que só parece bonito) e documentar os requisitos de forma que todo mundo entenda a mesma coisa.

## Capítulo 1: DevOps

### O problema que o DevOps resolve
- Em geral há muito mais gente em desenvolvimento (back-end, front-end, testes) do que em operação (administradores de sistemas, redes, infraestrutura).
- O curso conta o caso de uma empresa de software com cerca de 300 desenvolvedores e 15 administradores de sistemas. A diretoria cobra mais funcionalidades, mais tecnologia nova e mais disponibilidade ao mesmo tempo.
- Desenvolvimento quer mudar rápido. Operação quer estabilidade. Sem uma cultura comum, um lado vira gargalo do outro.

### O que é
- DevOps é uma **cultura** que usa práticas e ferramentas para aumentar a capacidade de desenvolver e entregar software e serviços com alta velocidade e qualidade.
- Não é um cargo nem uma ferramenta. É a forma de times de desenvolvimento e operação trabalharem juntos, com responsabilidade compartilhada.

### Benefícios
- Aumento da velocidade de entrega
- Escalabilidade
- Colaboração contínua
- Confiabilidade
- Segurança

### Práticas
- **Infraestrutura como código:** a infraestrutura é descrita e versionada como código, e não montada na mão.
- **Arquitetura de microsserviços:** sistemas divididos em partes pequenas e independentes.
- **Integração contínua:** o código dos desenvolvedores é integrado e testado com frequência.
- **Entrega contínua:** o software fica sempre pronto para ser liberado.
- **Monitoração, alarme, log e indexação:** enxergar o que acontece em produção.
- **Comunicação e colaboração:** a base de todo o resto.

### Estágios do ciclo DevOps
Planejamento (plan), codificação (code), construção (build), teste (test), lançamento (release), implantação (deploy), operação (operate) e monitoração (monitor). O ciclo é contínuo: o que se aprende na monitoração volta para o planejamento.

### DevSecOps
É a segurança distribuída por todo o ciclo, e não deixada só para o final. Os ganhos que o curso cita: vulnerabilidades encontradas e corrigidas antes da entrega, consciência de segurança disseminada nos times, software mais seguro e de maior qualidade, e menor custo para resolver um problema de segurança.

## Capítulo 2: metodologias e melhores práticas

### Manifesto Ágil
Valores e princípios que guiam o desenvolvimento ágil. Alguns princípios que o curso destaca: software funcionando é a medida primária de progresso, atenção contínua à excelência técnica aumenta a agilidade, simplicidade é a arte de maximizar o trabalho não realizado, e as melhores arquiteturas e requisitos emergem de times que se auto-organizam.

### Scrum
- **Pilares (controle empírico):** transparência, inspeção e adaptação.
- **Papéis:** Product Owner (PO, dono do valor e do backlog do produto), Scrum Master (SM, quem ajuda o time a seguir o método e remove impedimentos) e o Time Scrum (quem entrega).
- **Princípios do curso:** auto-organização, colaboração, priorização baseada em valor, time-boxing (tempo fixo para cada atividade) e desenvolvimento iterativo.
- **Cerimônias:** inclui a reunião diária, em que cada pessoa responde o que fez ontem para o objetivo do Sprint, o que fará hoje e se há algo impedindo o time.

### Kanban
- É um quadro com **fluxo de trabalho** visível. Começa com o que existe hoje, propõe mudanças pequenas e evolutivas, respeita papéis e títulos atuais e incentiva liderança em todos os níveis.
- Práticas: visualizar o fluxo, **limitar o trabalho em progresso (WIP)**, gerenciar e medir o fluxo, tornar as políticas explícitas, criar ciclos de feedback e melhorar de forma colaborativa.
- Elementos: colunas, raias, cartões, limite de WIP e políticas explícitas.
- O curso compara as vantagens do Kanban sobre o Scrum, sem tratar um como substituto do outro.

### Extreme Programming (XP)
Um conjunto de práticas técnicas: propriedade coletiva do código, padronização de código, versões pequenas, jogo de planejamento, testes de aceitação, programação em pares, desenvolvimento orientado a testes (TDD), integração contínua, design simples, refatoração, metáforas e ritmo sustentável (semana de 40 horas).

### Quem atua no time
Desenvolvedores back-end, front-end e full stack, analista de qualidade (QA), Scrum Master. Junto ao time: designer de UX/UI, analista de segurança, administrador de sistemas, analista e administrador de dados. Na gestão: gerente de projetos, especialistas e líderes.

## Capítulo 3: domínios de conhecimento da agilidade e métricas

### Eficácia versus eficiência
- **Eficiência:** fazer bem e rápido o que se faz (visão da organização).
- **Eficácia:** fazer o que realmente traz resultado (visão do negócio).
- Uma equipe pode ser muito eficiente entregando algo que ninguém queria.

### Métricas de eficiência (organizacional)
- **Lead time:** tempo total desde o pedido até a entrega.
- **Cycle time:** tempo desde que o trabalho começou de fato até ficar pronto.
- **Waiting time e touching time:** tempo parado esperando versus tempo de mão na massa.
- **Flow efficiency:** quanto do tempo total é trabalho de verdade.
- **WIP:** quanto trabalho está em andamento ao mesmo tempo.
- **Throughput:** quantos itens são entregues por período.
- **Cumulative flow diagram** e **control chart:** gráficos para enxergar gargalos e variação no fluxo.

### Métricas de eficácia (negócio)
ROI (retorno do investimento), NPS (satisfação e recomendação do cliente) e churn (taxa de clientes que saem).

### Métricas de atmosfera (cultura)
Turnover (rotatividade de pessoas) e happiness radar (termômetro da felicidade do time).

### Métricas de qualidade (técnica)
Notificação de problemas e cobertura de testes.

### Métricas tóxicas e de vaidade
Números que parecem bons, mas não ajudam a decidir nada, ou que incentivam comportamento ruim. Medir só para aparecer, ou medir pessoas em vez de fluxo, costuma fazer mal.

## Capítulo 4: desvendando a UML
- **UML** é uma linguagem de padrões visuais para modelar sistemas, em especial os orientados a objetos (conforme Guedes, 2011).
- Surgiu da união de técnicas de modelagem dos anos 1990 (como a OMT, de James Rumbaugh).
- Ela **não é** um método nem um processo de desenvolvimento. É uma notação para representar o sistema.
- Razões para modelar visualmente: comunicar o entendimento do sistema, reduzir mal-entendidos e documentar antes de construir.
- Os diagramas se dividem em estruturais (o que o sistema é) e comportamentais (o que o sistema faz).

## Capítulo 5: diagramas de caso de uso
- O **modelo de caso de uso** descreve os requisitos funcionais de um sistema **do ponto de vista do usuário**, para especificar, construir e documentar o comportamento do sistema (conforme Bezerra, 2015).
- **Elementos:** cenário, caso de uso, ator, fronteira e relacionamentos.
  - **Ator:** quem interage com o sistema (pessoa ou outro sistema).
  - **Caso de uso:** uma funcionalidade que traz resultado para o ator.
  - **Cenário:** um dos caminhos possíveis para executar o caso de uso. O curso usa a imagem de um labirinto, com vários caminhos até a saída.
  - **Fronteira:** o limite entre o que está dentro e fora do sistema.
- **Como construir:** listar atores, listar requisitos funcionais, desenhar o diagrama e descrever cada caso de uso. O curso traz um estudo de caso, um exercício e templates de especificação.

## Exemplo prático (empresa fictícia)
Uma **rede de clínicas** vai lançar um aplicativo de agendamento. O time de desenvolvimento quer lançar toda semana, e a equipe de operação teme que cada lançamento derrube o sistema no horário de pico de marcação de consultas.

- **Cultura DevOps:** os dois times planejam juntos, e a operação entra no desenho desde o início, com monitoração e alarmes definidos antes do lançamento.
- **Integração e entrega contínuas:** cada mudança passa por testes automáticos, e lançamentos pequenos reduzem o risco de cada um.
- **DevSecOps:** os dados de pacientes pedem verificação de segurança durante o desenvolvimento, e não só no fim.
- **Caso de uso:** o ator "paciente" tem o caso de uso "agendar consulta", e o ator "recepcionista" tem "remarcar consulta". Os cenários incluem horário indisponível e cancelamento.
- **Métricas:** acompanhar o lead time de uma melhoria pedida pela recepção, o cycle time do time e a cobertura de testes. Medir o número de linhas de código seria uma métrica de vaidade.
- **Kanban:** um quadro com limite de WIP evita abrir cinco funcionalidades e não fechar nenhuma.

## Como se conecta com o resto do repositório
- **ITIL** ([pasta 01](../01-itil-gestao-de-servicos/)): mudança, entrega e melhoria contínua dialogam com integração e entrega contínuas. DevOps é uma forma de fazer a mudança fluir com segurança.
- **COBIT** ([pasta 02](../02-governanca-cobit/)): métricas de fluxo e de qualidade alimentam o desempenho de objetivos de governança e gestão.
- **ISO 27001** ([pasta 04](../04-iso-27001/)): DevSecOps é a segurança aplicada ao ciclo de desenvolvimento.
- **Desafios do gestor de TI** ([00-panorama](../00-panorama/04-desafios-do-gestor-de-ti.md)): agilidade e incerteza fazem parte do dia a dia do gestor.
- **Soft skills** ([07](../07-carreira-e-soft-skills/)): a cultura DevOps depende de comunicação e colaboração, tema do [curso 01](01-leadership-communication.md).

## Pegadinhas de prova
- **DevOps não é uma ferramenta nem um cargo.** É uma cultura apoiada por práticas e ferramentas.
- **Scrum não é Kanban.** Scrum tem papéis, cerimônias e ciclos fixos. Kanban tem fluxo contínuo e limite de WIP.
- **Lead time não é cycle time.** Lead time conta desde o pedido. Cycle time conta desde o início do trabalho.
- **Eficiência não é eficácia.** Fazer rápido não garante fazer o que traz resultado.
- **UML não é um método.** É uma linguagem de modelagem.
- **Ator não é sempre uma pessoa.** Pode ser outro sistema.
- **Métrica de vaidade parece boa e não decide nada.**

## Perguntas de revisão

**1. Por que o DevOps surgiu e o que ele propõe?**
<details><summary>Resposta</summary>
Desenvolvimento quer entregar rápido e operação quer estabilidade, e isso gera conflito. O DevOps propõe uma cultura comum, com práticas e ferramentas que aproximam os dois lados e aceleram entregas com qualidade.
</details>

**2. Cite três práticas DevOps.**
<details><summary>Resposta</summary>
Infraestrutura como código, integração contínua, entrega contínua, microsserviços, monitoração e log, e comunicação e colaboração. Qualquer três.
</details>

**3. Quais são os três pilares do Scrum e os três papéis?**
<details><summary>Resposta</summary>
Pilares: transparência, inspeção e adaptação. Papéis: Product Owner, Scrum Master e Time Scrum.
</details>

**4. Para que serve o limite de WIP no Kanban?**
<details><summary>Resposta</summary>
Limitar o trabalho em progresso evita abrir muita coisa ao mesmo tempo, expõe gargalos e ajuda a terminar o que foi começado.
</details>

**5. Qual a diferença entre lead time e cycle time?**
<details><summary>Resposta</summary>
Lead time é o tempo total do pedido até a entrega. Cycle time é o tempo do início efetivo do trabalho até ficar pronto.
</details>

**6. O que diferencia métricas de eficiência de métricas de eficácia?**
<details><summary>Resposta</summary>
Eficiência mede o fluxo e o uso do tempo na organização (lead time, WIP, throughput). Eficácia mede o resultado para o negócio (ROI, NPS, churn).
</details>

**7. Quais são os elementos de um modelo de caso de uso?**
<details><summary>Resposta</summary>
Cenário, caso de uso, ator, fronteira e relacionamentos.
</details>

## Fonte e referências
- FIAP · Nano Course "DevOps & Agile Culture", plataforma FIAP ON (acesso com login). Capítulos: DevOps; Metodologia e Melhores Práticas de Desenvolvimento de Software; Domínios de Conhecimento da Agilidade e suas Métricas; Desvendando o UML; Diagramas de Caso de Uso.
- Autores citados no curso nos capítulos de modelagem: Guedes (2011), Bezerra (2007; 2015) e Pressman (2011).
- As definições dos capítulos 1 a 3 vêm do texto do curso. Termos como lead time, cycle time e Scrum têm definições amplamente usadas na área, aqui resumidas com minhas palavras.

---
Voltar às notas da [pasta 08](README.md) · [mapa de estudos](../README.md).
