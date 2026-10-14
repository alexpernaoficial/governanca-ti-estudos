# O novo profissional de GRC que o mercado procura

> **Fonte:** TIexames · Wellington Mônaco · [vídeo no YouTube](https://youtu.be/AaOTz0_X6Ro) · assistida em 10/2026
> **Tema:** Panorama de GRC · perfil profissional

## Em uma frase
O que mais falta nas empresas não é conhecimento técnico de norma, é alguém que **integre** governança, riscos e compliance, que hoje costumam viver separados, cada um na sua planilha.

## O que é GRC
| Letra | Pergunta que responde | Exemplo |
|---|---|---|
| **G**overnança | Quem decide, com base em quê, e como a direção acompanha? | Papéis, comitês, políticas, indicadores para a diretoria |
| **R**iscos | O que pode dar errado, qual o tamanho e o que vamos fazer? | Registro de riscos, plano de tratamento |
| **C**ompliance | O que somos obrigados a cumprir, e estamos cumprindo? | Leis, regulador, contratos **e regras internas** |

Os três se alimentam: o compliance diz quais obrigações existem, a governança organiza quem cuida de cada uma, e a gestão de riscos mostra onde a empresa está exposta se algo falhar.

## Explicação simples

### 1. Certificação é requisito, não diferencial
Certificações (ITIL, COBIT, ISO 27001) mostram que você **conhece** o framework. Elas abrem a porta do processo seletivo, mas não diferenciam. O diferencial é mostrar que você sabe **aplicar**: adaptar o framework à realidade da empresa, sem querer implantar o livro inteiro.

### 2. Compliance não é só lei
É comum pensar em compliance só como "cumprir a LGPD" ou "atender o regulador". Mas também entram:
- **obrigações externas:** leis, normas do regulador, contratos com clientes e fornecedores;
- **obrigações internas:** políticas, procedimentos e regras que a própria empresa criou.

Se a empresa escreveu uma política e ninguém segue, isso também é uma não conformidade.

### 3. Política sem indicador é só papel
Toda política precisa responder: **como vou saber se ela está funcionando?** Sem um indicador de efetividade e uma data de revisão, a política vira um documento que ninguém lê.
- Política de senhas → % de contas com MFA ativo.
- Política de mudanças → % de mudanças feitas sem aprovação.

### 4. Governança de dados vem antes da governança de IA
A IA aprende e decide a partir dos dados. Se os dados estão errados, duplicados, sem dono ou coletados sem base legal, a IA só **multiplica o erro** em escala. Antes de discutir política de IA, a empresa precisa saber quais dados tem, onde estão, quem é o dono e qual a qualidade.

### 5. Registrar risco não é apontar culpado
Se registrar um risco ou um erro vira motivo de punição, as pessoas param de registrar, e a empresa fica cega. O papel do GRC é trazer **evidência** para a decisão, não caçar responsáveis. A cultura certa é parecida com a do pós-incidente sem culpa ("blameless").

## O perfil que o mercado procura
- **Integrador:** enxerga o todo e conecta áreas (TI, jurídico, operação, diretoria).
- **Fala a língua do negócio:** traduz risco técnico em impacto (dinheiro, cliente, multa, reputação).
- **Orientado a dados:** decide e mostra resultado com indicadores.
- **Prático:** começa pequeno, entrega algo que funciona e melhora aos poucos.

## Uma forma de integrar: 3 camadas
1. **Mapear:** levantar o que existe (políticas, obrigações, riscos, responsáveis).
2. **Reunir e cruzar:** ligar uma coisa à outra (esta obrigação → esta política → este risco → este dono).
3. **Bússola:** um painel simples que mostra para a direção onde a empresa está e o que precisa de atenção.

Ordem prática sugerida para começar: **Compliance → Governança → Riscos**. Primeiro saber o que é obrigatório, depois organizar quem cuida, depois medir a exposição.

## Exemplo prático: uma rede de escolas (fictícia)
A rede tem uma política de matrícula, contratos com as famílias que prometem prazos (como a entrega do boletim) e obrigações com o MEC e com a LGPD (dados de alunos menores de idade). Cada área controla a sua parte.

- **Mapear:** uma planilha única com cada obrigação, a política ligada, o dono e a evidência de cumprimento.
- **Cruzar:** o contrato promete boletim em 10 dias após o bimestre; a política da secretaria não fala desse prazo → lacuna encontrada.
- **Bússola:** um painel mensal com 5 indicadores (prazo do boletim cumprido, % de mudanças nos sistemas aprovadas, chamados reabertos, pedidos LGPD respondidos no prazo, treinamentos feitos).

## Como se conecta com o resto
- **COBIT 2019:** APO01 (estrutura de gestão de TI), APO12 (riscos), MEA01 (desempenho e indicadores), MEA03 (conformidade com requisitos externos).
- **ISO 31000:** processo de gestão de riscos (identificar, analisar, avaliar, tratar, monitorar).
- **ISO/IEC 27001:** a cláusula 9.1 exige monitorar e medir a eficácia do sistema de segurança, a mesma ideia do item 3.
- **ISO 37301:** norma de sistema de gestão de compliance.
- **ITIL:** gestão de incidentes e de problemas usam a mesma cultura do item 5 (aprender com a falha).

## Pegadinhas de prova
- **Governança × gestão (COBIT):** governança **avalia, direciona e monitora** (domínio EDM); gestão **planeja, constrói, executa e monitora** (APO, BAI, DSS, MEA).
- **Certificação de pessoa × de empresa:** "ISO 27001 Foundation" certifica **você**. A **empresa** se certifica na ISO 27001 por auditoria do seu SGSI (sistema de gestão de segurança da informação).
- **Risco × incidente × problema:** risco é algo que **pode** acontecer; incidente é uma interrupção que **está** acontecendo; problema (ITIL) é a **causa** de um ou mais incidentes.
- **Compliance × auditoria:** compliance é cumprir as obrigações no dia a dia; auditoria é a verificação independente de que isso está sendo feito.

## Perguntas de revisão
1. Por que uma certificação sozinha não diferencia um profissional de GRC?
2. Cite um exemplo de obrigação interna e um de obrigação externa.
3. Qual indicador você usaria para saber se uma política de backup funciona?
4. Por que a governança de dados precisa vir antes da governança de IA?
5. O que acontece com a gestão de riscos quando registrar um erro gera punição?

<details><summary>Respostas</summary>

1. Ela prova conhecimento do framework, não a capacidade de aplicá-lo na realidade da empresa.
2. Interna: uma política de senhas da empresa. Externa: a LGPD, um contrato com cliente, uma norma do regulador.
3. Exemplos: % de backups concluídos com sucesso e % de testes de restauração bem-sucedidos no mês.
4. Porque a IA reproduz e amplia a qualidade dos dados; dado ruim vira decisão ruim em escala.
5. As pessoas param de registrar, os riscos ficam escondidos e a direção decide sem informação.
</details>
