# Transcrição da sessão grill-me — Mapa de atores

**Exercício:** 2.1 — Mapa de Atores da Jornada de um Serviço Público (IDP-TD 2026)
**Aluna:** Flavia Rios
**Serviço:** Atendimento ao Seguro-Desemprego pela URA da Caixa Econômica Federal (canal telefônico; órgãos: CAIXA e Ministério do Trabalho e Emprego)
**Contexto da entrevista:** `B_relatorio_assistente_v3.md` (versão final da Parte B) e a metodologia de mapeamento de atores da Aula 03.

**Como a sessão foi conduzida:** a entrevista seguiu o método grill-me: uma pergunta por vez, em tom adversarial, para forçar decisões explícitas da aluna. O tutorial prevê o uso do Claude Code com a skill `/grill-me`. Como o computador da aluna roda macOS Catalina (10.15), que não é suportado pelo Claude Code (exige macOS 13 ou superior), a sessão foi feita no Claude (claude.ai) pelo navegador, com o Claude no papel de entrevistador grill-me.

**Fidelidade:** as perguntas do entrevistador e as respostas da aluna estão transcritas na íntegra, sem edição. Quando a resposta menciona uma figura ou um esquema ("Exemplo simplificado do mapa híbrido", "Relação contratual no mapa", "Organização conceitual do mapa", "Representação conceitual da coordenação do episódio"), apenas o título foi transmitido na conversa, e ele está mantido como foi escrito.

**Total:** 10 rodadas de pergunta e resposta.

---

## Índice das 10 rodadas (resumo elaborado a partir da transcrição integral abaixo)

| Rodada | Tema da pergunta | Decisão da aluna | Atores e nós citados na rodada |
|---|---|---|---|
| 1 | Fronteira do mapa | (b) episódio de resolução, com a URA da CAIXA no centro; TCU fora do mapa principal | Cidadão/trabalhador, URA da CAIXA, CAIXA, MTE, empregador, Dataprev, Receita Federal, banco recebedor, Central 158, Sine, TCU |
| 2 | Coerência do critério (controle e normas) | Três níveis: mapa principal, círculo externo e fora do mapa; TCU, CODEFAT, CGU e BCB/CMN no círculo externo; Ouvidoria do MTE e Judiciário/MP/Defensorias no principal | TCU, CODEFAT, CGU, Ouvidoria do MTE, BCB/CMN, Judiciário, Ministério Público, Defensorias |
| 3 | URA: ator ou canal? | (c) modelo híbrido: URA como nó sociotécnico central, CAIXA como responsável | URA, Central 158, Sistema do Seguro-Desemprego (Dataprev), gov.br, CAIXA Tem, CTPS Digital/Emprega Brasil, Empregador Web/eSocial, Portal de Demandas CAIXA–MTE |
| 4 | Critério dos sistemas × tabela | Nó só com duas condições (participa do episódio e é etapa autônoma); Central 158 separada em canal e operadores | URA, Central 158, Operadores do Contact Center 158, INSS, MTE, Sistema do Seguro-Desemprego, CTPS Digital/Emprega Brasil, gov.br, CAIXA Tem, Empregador Web/eSocial, Portal de Demandas |
| 5 | Granularidade da CAIXA e do MTE | CAIXA em 4 (gestão de pagamentos, atendimento CAIXA Cidadão, SAC e Ouvidoria, rede presencial); MTE em 4 (gestão do benefício, gestão e fiscalização contratual, SRTE, Ouvidoria); fornecedores condicionais; fiscalização contratual no círculo externo, com seta financeira "remuneração da URA — Contrato 11/2021" | CAIXA (gestão de pagamentos, CAIXA Cidadão, SAC e Ouvidoria, rede presencial), fornecedores terceirizados potenciais, MTE (gestão do benefício, gestão e fiscalização contratual, SRTE, Ouvidoria) |
| 6 | Segmentação do cidadão | (c) titular como ator central; dois subgrupos; familiares como ator auxiliar condicional (seta tracejada) | Trabalhador titular, usuários rurais e com baixo letramento digital, pessoas surdas ou com deficiência auditiva ou de fala, familiares e pessoas de apoio |
| 7 | Atores de origem da falha | Camada de fluxos de exceção; Dataprev organização separada do nó técnico | Empregador/RH, Receita Federal, banco recebedor, Dataprev (organização), Sine estadual/municipal |
| 8 | Reconciliação das camadas | Dataprev, Judiciário, MP, Defensorias e MGI na exceção; INSS (158) e operadores do 158 no principal; pescadores e INSS legado fora do mapa | Dataprev, Judiciário, Ministério Público, Defensorias Públicas, INSS, MGI, pescadores artesanais, INSS legado do seguro-defeso, operadores do Contact Center 158 |
| 9 | Formato e tipos de relação | Formato B (mermaid + tabela) com RACI complementar; 5 tipos de relação (atendimento, encaminhamento, dados, financeira, governança); tracejado = hipótese | MTE (gestão do benefício), CAIXA (gestão de pagamentos), banco recebedor, responsável pelo dado de origem |
| 10 | Coordenação do episódio | (b) ausência de coordenador documentado representada explicitamente no diagrama e na RACI | CAIXA, MTE, Central 158, cidadão |

---

## Rodada 1

### Pergunta do entrevistador (Claude — grill-me)

Li a v3. Vamos começar. Vou numerar as rodadas para facilitar a transcrição no final. Responda com a **sua decisão** e uma justificativa curta.

**Rodada 1 — A fronteira do mapa**

A v3 mostra que o cidadão que liga para a URA da CAIXA dizendo "minha parcela não caiu" pode ter um problema cuja causa está em muitos lugares: no empregador, no MTE, na Dataprev, na Receita Federal, no banco recebedor ou na própria CAIXA. A Aula 03 manda partir do cidadão e expandir em círculos, mas **alguém precisa decidir onde o mapa termina**. Sem esse limite, o mapa vira o organograma do governo federal inteiro.

Você tem três opções de fronteira:

- **(a) Só a ligação:** do momento em que o cidadão disca até desligar. O mapa fica enxuto, centrado na URA, nos atendentes e nos sistemas consultados durante a chamada. Mas atores como empregador, Receita Federal e TCU ficam de fora, mesmo causando boa parte das ligações.
- **(b) O episódio de resolução:** da dúvida que motivou a ligação até o problema ser resolvido ou abandonado, incluindo recontatos, encaminhamentos ao 158, ao Sine ou à agência, e a correção na origem. A demanda de falha cabe aqui, mas o mapa cresce.
- **(c) O ciclo inteiro do benefício:** da demissão até a última parcela. O mapa fica completo, mas a URA vira um detalhe e você perde o foco do serviço escolhido.

**Pergunta:** qual fronteira você escolhe para o seu mapa, e por quê? E qual ator você aceita deixar de fora como consequência dessa escolha?

### Resposta da aluna (Flavia Rios)

Escolho a opção (b) — O episódio de resolução, com a ligação à URA da CAIXA como ponto central do mapa.
Essa fronteira é a mais adequada porque permite analisar não apenas o atendimento telefônico, mas também os fatores que motivaram a ligação e os encaminhamentos necessários para solucionar a demanda do cidadão.
A escolha se justifica por três razões:

1. Mantém o foco no serviço público escolhido: a URA da CAIXA continua sendo o centro da análise, sem ampliar o estudo para todo o ciclo do Seguro-Desemprego.
2. Permite identificar a demanda de falha: uma ligação sobre uma parcela não recebida pode decorrer de problemas em diferentes instituições. Limitar a análise à chamada esconderia essas relações e suas consequências.
3. Evidencia a fragmentação da jornada: permite identificar os atores envolvidos nos encaminhamentos, os recontatos, as responsabilidades institucionais e os pontos em que o cidadão precisa transitar entre canais para obter uma solução.

Critério de inclusão: entram no mapa os atores que participam diretamente do atendimento ou que têm responsabilidade relevante pela causa, pelo encaminhamento ou pela resolução das demandas recebidas pela URA. Atores de influência indireta podem aparecer em um círculo externo, sem o mesmo nível de detalhamento.
Ator que aceito deixar de fora: o TCU.
Embora o Tribunal de Contas da União tenha papel importante na fiscalização e na avaliação do serviço, ele não participa diretamente da resolução individual da demanda do cidadão. Seus achados serão utilizados como evidências para contextualizar os problemas identificados, mas o TCU não precisa integrar o mapa principal de atores.
Síntese da decisão: o mapa acompanhará a jornada do cidadão desde o problema que motivou o contato com a URA da CAIXA até sua resolução, encaminhamento definitivo ou abandono, considerando os atores e as relações que influenciam esse percurso, sem representar todo o ciclo de concessão e pagamento do benefício.

---

## Rodada 2

### Pergunta do entrevistador (Claude — grill-me)

Decisão registrada: **fronteira (b), o episódio de resolução, com a URA da CAIXA no centro**. Você também definiu um critério de inclusão e excluiu o TCU. Agora vou testar se o seu critério se sustenta.

**Rodada 2 — Coerência do critério com os atores de controle e normatização**

Você excluiu o TCU porque ele "não participa diretamente da resolução individual da demanda". Mas, pelo mesmo raciocínio, outros atores da v3 também não resolvem nenhum caso individual:

- **CODEFAT:** delibera as regras do benefício. Nenhum cidadão tem a parcela liberada pelo CODEFAT, mas é a norma dele que define, por exemplo, que a contestação de saque vai para o MTE e não para a CAIXA.
- **CGU e Ouvidoria do MTE:** recebem reclamações individuais. A Ouvidoria, portanto, participa *sim* do episódio quando o cidadão reclama.
- **Banco Central e CMN:** regulam o SAC e a Ouvidoria da CAIXA, mas não tocam no caso concreto.
- **Judiciário, MP e Defensorias:** resolvem casos individuais, mas só quando o cidadão aciona a Justiça, o que é raro e lento.

Além disso, você mesma abriu a porta de um **"círculo externo"** para atores de influência indireta. Então o TCU está **fora do mapa** ou **no círculo externo**? São coisas diferentes, e o seu texto deixa as duas leituras possíveis.

**Pergunta:** aplique o seu critério de forma explícita a esses cinco atores (TCU, CODEFAT, CGU/Ouvidoria do MTE, BCB/CMN e Judiciário/MP/Defensorias). Para cada um, diga se ele fica **no mapa principal**, **no círculo externo** ou **fora do mapa**, com uma frase de justificativa.

### Resposta da aluna (Flavia Rios)

**Mantenho a opção (b) — episódio de resolução**, mas aperfeiçoo o critério de inclusão para distinguir os atores que participam da resolução individual daqueles que influenciam estruturalmente o serviço.

- **Mapa principal:** atores que participam efetivamente do atendimento, encaminhamento, reclamação ou resolução de uma demanda individual, inclusive em situações excepcionais.
- **Círculo externo:** atores que estabelecem regras, fiscalizam ou regulam o serviço, mas não participam diretamente da resolução individual.
- **Fora do mapa:** atores sem relação suficientemente relevante com o episódio de resolução ou com a governança específica do serviço.

### **Aplicação do critério**

| Ator | Classificação | Justificativa |
| --- | --- | --- |
| **TCU** | Círculo externo | Fiscaliza e avalia o desempenho do serviço, influenciando sua melhoria, mas não resolve demandas individuais. |
| **CODEFAT** | Círculo externo | Define regras que condicionam a concessão e os procedimentos do benefício, mas não atua nos atendimentos individuais. |
| **CGU / Ouvidoria do MTE** | Mista | A Ouvidoria do MTE fica no **mapa principal**, pois recebe e encaminha manifestações individuais. A CGU fica no **círculo externo**, por sua atuação em supervisão e controle, ressalvadas suas competências relacionadas à ouvidoria. |
| **BCB / CMN** | Círculo externo | Estabelecem e supervisionam regras aplicáveis aos canais bancários, sem atuar normalmente na solução operacional da parcela. |
| **Judiciário / MP / Defensorias** | Mapa principal, em fluxo excepcional | Podem participar da resolução de casos individuais quando a demanda administrativa não é solucionada e o cidadão recorre às vias jurídicas. Suas competências são distintas. |

### **Revisão da decisão anterior**

**O TCU permanece no mapa, mas exclusivamente no círculo externo.** Assim, corrijo a ambiguidade da primeira resposta.

Também reconheço que o mapa principal não deve representar apenas a jornada mais frequente. Deve contemplar os caminhos excepcionais de resolução, desde que identificados como tais.

**Decisão consolidada:** a fronteira será definida pela participação na resolução individual ou pela influência institucional direta sobre o funcionamento do serviço. A distinção entre mapa principal e círculo externo preservará o foco na experiência do cidadão, sem ignorar as relações de governança.

Nenhum dos cinco grupos analisados precisa ser completamente excluído. Entretanto, a presença de um ator no círculo externo não autoriza expandir o mapa para todas as suas atribuições institucionais.

---

## Rodada 3

### Pergunta do entrevistador (Claude — grill-me)

Critério consolidado em três níveis: **mapa principal**, **círculo externo** e **fora do mapa**. O TCU, o CODEFAT, a CGU e o BCB/CMN ficam no círculo externo. A Ouvidoria do MTE e o Judiciário, o MP e as Defensorias ficam no principal, estes três em fluxo excepcional. A ambiguidade da rodada anterior está resolvida.

**Rodada 3 — A URA é um ator ou um canal?**

O centro do seu mapa é "a ligação à URA da CAIXA". Mas a Aula 03 define atores como **pessoas, grupos e organizações** que influenciam o serviço ou são influenciados por ele. A URA é um **sistema**: ela não tem interesses, não ganha nem perde, não resiste a mudanças. Quem tem tudo isso é a CAIXA, que a opera, e o MTE, que a contratou no 11/2021.

Por outro lado, o próprio exemplo do tutorial coloca o "IVR / menu de voz" como um nó do mapa. Do ponto de vista do cidadão, é com a URA que ele "conversa".

O problema não se limita à URA. A v3 lista vários sistemas e canais: **URA, Central 158, CAIXA Tem, gov.br, CTPS Digital/Emprega Brasil, Empregador Web/eSocial, o sistema do Seguro-Desemprego (Dataprev) e o Portal de Demandas CAIXA–MTE**. Se todos virarem atores, metade do seu mapa será de máquinas, e fichas como "interesses" e "resistências" deixam de fazer sentido. Se nenhum virar ator, o cidadão "liga para a CAIXA", e você perde o ponto onde a demanda de falha acontece: o menu que não resolve e a falta de transferência para um humano.

Três caminhos possíveis:
- **(a)** Os sistemas são **nós próprios** (atores sociotécnicos), visualmente distintos das organizações.
- **(b)** Os sistemas **não são nós**: aparecem como **rótulo nas setas** entre organizações (ex.: Cidadão → CAIXA, "via URA").
- **(c)** **Híbrido:** só alguns sistemas viram nós, e os demais ficam nas setas.

**Pergunta:** qual caminho você escolhe? Se for o (c), diga **quais sistemas viram nós** e qual critério os separa dos que ficam só como rótulo.

### Resposta da aluna (Flavia Rios)

**Escolho a opção (c) — Modelo híbrido**, distinguindo os atores institucionais dos sistemas que representam pontos relevantes de interação, decisão ou encaminhamento na jornada do cidadão.

A URA não será classificada como ator institucional, mas como um **nó sociotécnico**, visualmente diferente das pessoas e organizações.

### **1. Critério de inclusão dos sistemas**

Um sistema será representado como nó próprio quando atender a pelo menos uma destas condições:

1. **Interação direta:** o cidadão interage com ele durante o episódio de resolução.
2. **Decisão ou encaminhamento:** o sistema automatiza uma etapa que pode determinar o resultado do atendimento.
3. **Ponto crítico de falha:** seu funcionamento pode gerar, prolongar ou dificultar a resolução da demanda.

Para evitar que o mapa fique excessivamente complexo, a inclusão também dependerá da relevância do sistema para a jornada analisada.

### **2. Classificação dos sistemas**

| Sistema ou canal | Representação | Justificativa |
| --- | --- | --- |
| **URA da CAIXA** | Nó próprio — central | É o objeto do estudo e o principal ponto de interação automatizada, podendo resolver, encaminhar ou não solucionar a demanda. |
| **Central 158** | Nó próprio | Representa um canal alternativo de atendimento, relevante para compreender encaminhamentos e recontatos. |
| **Sistema do Seguro-Desemprego (Dataprev)** | Nó próprio | Processa informações essenciais à situação do benefício, podendo influenciar o resultado das consultas e a resolução das inconsistências. |
| **gov.br** | Nó próprio, secundário | Problemas de autenticação podem impedir o acesso digital e motivar a procura pelo atendimento telefônico. |
| **CAIXA Tem** | Rótulo de canal | É uma alternativa de consulta e movimentação de valores, vinculada à CAIXA. Pode aparecer nas relações com o cidadão sem exigir nó próprio. |
| **CTPS Digital / Emprega Brasil** | Rótulo de canal | São interfaces digitais para solicitação e acompanhamento do benefício, representadas nas relações entre cidadão e MTE. |
| **Empregador Web / eSocial** | Rótulo de sistema | Representam mecanismos de envio e registro de informações, associados às relações entre empregadores e instituições responsáveis. |
| **Portal de Demandas CAIXA–MTE** | Rótulo de integração | É um instrumento de comunicação institucional entre CAIXA e MTE, sem interação direta do cidadão. |

A classificação poderá ser revista se a pesquisa demonstrar que algum sistema inicialmente representado apenas como rótulo constitui um ponto decisivo de falha ou encaminhamento.

### **3. Como representar visualmente**

Exemplo simplificado do mapa híbrido

Esquema conceitual, não um fluxo técnico comprovado de integração entre os sistemas.

Os nós institucionais terão fichas com interesses, poder, dependências, ganhos, perdas e possíveis resistências. Os nós sociotécnicos terão fichas diferentes, contendo função, organização responsável, dados utilizados, decisões automatizadas, limitações e possíveis falhas.

**Decisão consolidada:** a URA será um nó central do mapa, mas não um ator com interesses próprios. A CAIXA continuará sendo a organização responsável pelo canal. Essa distinção preserva a experiência concreta do cidadão sem atribuir características humanas aos sistemas.

---

## Rodada 4

### Pergunta do entrevistador (Claude — grill-me)

Decisão registrada: **modelo híbrido**. A URA vira um **nó sociotécnico central**, e não um ator com interesses. A CAIXA fica como a organização responsável por ela. Os nós de sistema terão uma ficha diferente da ficha das organizações.

Um detalhe: a sua resposta menciona um "Exemplo simplificado do mapa híbrido", mas a imagem ou o esquema não veio junto, só o título. Se for importante, descreva em palavras na próxima resposta. Para a transcrição, vale o texto.

**Rodada 4 — O seu critério contradiz a sua tabela**

Você definiu que um sistema vira nó se atender a **pelo menos uma** de três condições: (1) interação direta com o cidadão, (2) decisão ou encaminhamento automatizado, (3) ponto crítico de falha. Agora aplique essa regra à sua própria tabela:

- **CAIXA Tem:** o cidadão interage diretamente com ele para consultar a parcela. Atende à condição 1. Pela sua regra, seria **nó**, mas você o deixou como rótulo.
- **CTPS Digital / Emprega Brasil:** o cidadão interage diretamente com eles, e é neles que aparece a "mensagem genérica de indeferimento" que a v3 lista como causa de recontato. Atendem às condições 1 e 3. Seriam **nó**.
- **Empregador Web / eSocial:** a duplicidade entre os dois, documentada pelo TCU, gera divergências e indeferimentos. Atendem à condição 3. Seriam **nó**.
- **gov.br:** você o pôs como nó, mas o login do gov.br acontece *dentro* da CTPS Digital e do Emprega Brasil, que ficaram como rótulos. O mapa teria o porteiro, mas não a casa.

A sua cláusula de "relevância para a jornada" é que está fazendo o trabalho de verdade, mas ela não está definida. Tem ainda um problema de outra natureza: a **Central 158** não é só um sistema. Pela v3, é um Contact Center com **operadores humanos**, executado pelo INSS via TED. Classificá-la como nó sociotécnico apaga as pessoas que atendem.

**Pergunta:** reescreva o critério para que ele **produza exatamente a classificação que você quer**, sem depender de uma "relevância" indefinida. Por exemplo, você pode exigir duas condições em vez de uma, ou usar a fronteira da Rodada 1 como filtro. Em seguida, diga como fica a **Central 158**: nó sociotécnico, ator institucional (os operadores do Contact Center) ou os dois, separados?

### Resposta da aluna (Flavia Rios)

**Mantenho a opção (c) — modelo híbrido, mas reformulo o critério.** A crítica procede: interação direta ou possibilidade de falha, isoladamente, não justificam transformar qualquer sistema em nó.

### **1. Critério revisado**

Um sistema ou canal será representado como **nó próprio** somente quando atender simultaneamente a duas condições:

1. **Participar do episódio de resolução:** ser utilizado para consultar, esclarecer, encaminhar, corrigir ou contestar a demanda que motivou a ligação à URA.
2. **Representar uma etapa autônoma da jornada:** exigir uma interação, decisão ou encaminhamento distinto, cuja representação apenas como rótulo de uma seta esconderia uma responsabilidade, uma barreira ou uma possível interrupção do atendimento.

Caso não satisfaça as duas condições, será representado como rótulo de uma relação entre atores institucionais.

Assim, não basta um sistema poder apresentar falhas. É necessário que ele represente uma etapa identificável do episódio de resolução.

### **2. Aplicação aos sistemas**

| Sistema ou canal | Representação | Justificativa |
| --- | --- | --- |
| **URA da CAIXA** | Nó central | É a etapa automatizada que inicia o atendimento estudado e pode resolver, encaminhar ou interromper a jornada. |
| **Central 158** | Nó de canal + atores humanos | Constitui uma etapa alternativa de atendimento, com operadores e responsabilidades próprias. |
| **Sistema do Seguro-Desemprego (Dataprev)** | Nó técnico | Pode constituir etapa de consulta ou reprocessamento necessária à resolução de inconsistências. |
| **CTPS Digital / Emprega Brasil** | Nó secundário | Permitem acompanhar o benefício e identificar indeferimentos, podendo constituir etapa distinta de esclarecimento ou recurso. |
| **gov.br** | Rótulo de autenticação | É um mecanismo de acesso às interfaces digitais. Só se tornaria nó em um episódio específico de recuperação de identidade digital. |
| **CAIXA Tem** | Rótulo de canal | Será identificado na relação cidadão–CAIXA quando funcionar apenas como alternativa de consulta, sem etapa adicional de resolução. |
| **Empregador Web / eSocial** | Rótulo de sistemas | Representam a origem ou transmissão de informações do empregador, sem presumir que o cidadão interaja com eles durante a resolução. |
| **Portal de Demandas CAIXA–MTE** | Rótulo de integração | Representa a comunicação institucional de bastidor, sem etapa autônoma demonstrada na jornada do cidadão. |

A classificação é aplicada à **função desempenhada no episódio**, não à importância geral da tecnologia. Por exemplo, se um problema no CAIXA Tem exigir procedimentos próprios de recuperação de acesso, ele poderá ser representado como nó naquele fluxo específico.

### **3. Como fica a Central 158?**

**Escolho representá-la pelos dois elementos, separados:**

- **Central 158 — nó sociotécnico:** representa o canal pelo qual o cidadão busca atendimento, incluindo entrada, direcionamento e eventual recontato.
- **Operadores do Contact Center — ator humano coletivo:** representam as pessoas que prestam atendimento, interpretam demandas e realizam encaminhamentos, dentro das atribuições disponíveis.

O **INSS** permanece como ator institucional associado à execução do Contact Center por meio do TED com o MTE. O **MTE** permanece como responsável institucional pelo serviço.

Essa separação é importante porque o canal não tem interesses próprios, mas os operadores e as instituições possuem responsabilidades, condições de trabalho, limitações operacionais e diferentes graus de autonomia.

### **4. Decisão consolidada**

O mapa terá três representações visuais distintas: **atores humanos e institucionais, nós sociotécnicos e relações identificadas por seus canais ou sistemas**.

A URA permanece como nó central porque é o ponto de entrada do serviço estudado. Entretanto, o cidadão permanece no centro da análise da jornada.

Essa solução permite representar os pontos em que a demanda de falha surge ou persiste, sem transformar todos os sistemas governamentais em atores e sem atribuir interesses ou resistências a tecnologias.

---

## Rodada 5

### Pergunta do entrevistador (Claude — grill-me)

Critério revisado e coerente. Agora um sistema só vira nó se cumprir **duas condições juntas**: participar do episódio **e** ser uma etapa autônoma da jornada. Pela sua nova classificação:

- **Nós:** a URA (central), a Central 158, o Sistema do Seguro-Desemprego (Dataprev) e a CTPS Digital / Emprega Brasil.
- **Rótulos nas setas:** o gov.br, o CAIXA Tem, o Empregador Web / eSocial e o Portal de Demandas.
- **Central 158:** fica dividida entre o canal (nó sociotécnico) e os **operadores do Contact Center** (ator humano coletivo). O INSS e o MTE aparecem como atores institucionais.

**Rodada 5 — Granularidade: a CAIXA e o MTE são um ator cada, ou vários?**

A Aula 03 manda **"não parar na categoria"** e separar os subgrupos, porque cada um responde a incentivos diferentes. Na v3, a CAIXA e o MTE aparecem fatiados de várias formas:

**CAIXA:** (1) agente pagador, a organização que efetiva o crédito; (2) atendentes humanos do CAIXA Cidadão, para onde a URA eventualmente transfere; (3) SAC e Ouvidoria CAIXA; (4) agências, lotéricas e correspondentes; (5) fornecedores terceirizados *potenciais*, cuja subcontratação é permitida, mas não está comprovada.

**MTE:** (1) gestor do benefício, que habilita, analisa recursos e bloqueia ou desbloqueia parcelas; (2) gestor e fiscal de contrato, que mede, atesta e paga a CAIXA; (3) SRTE, as unidades federais presenciais; (4) Ouvidoria do MTE, que você já pôs no mapa principal.

Aqui o seu próprio critério cria uma tensão. O **fiscal de contrato do MTE** nunca resolve o caso de nenhum cidadão, então, pela Rodada 2, iria para o círculo externo. Só que a v3 mostra que o Contrato 11/2021 **pagava a CAIXA por ligação atendida na URA**. É justamente essa relação que conecta a demanda de falha a um incentivo financeiro. Jogar o fiscal no círculo externo enfraquece o argumento mais forte da sua pesquisa.

**Pergunta:**
1. Em quantos atores você divide a **CAIXA** e em quantos divide o **MTE**? Quais dos subgrupos listados viram atores separados, e quais você junta? Justifique com o incentivo diferente de cada um.
2. Onde fica o **fiscal de contrato do MTE**: mapa principal ou círculo externo? Se ficar no círculo externo, como a relação "pagamento por ligação" continua visível no mapa?

### Resposta da aluna (Flavia Rios)

**Divido a CAIXA em 4 atores funcionais e o MTE em 4 atores funcionais.** Mantenho as duas instituições como organizações de referência, mas separo os grupos cujas responsabilidades, incentivos e capacidades de atuação são diferentes.

O critério de granularidade será: **se dois grupos da mesma instituição possuem responsabilidades distintas, incentivos potencialmente conflitantes ou capacidades diferentes de influenciar a resolução da demanda, devem ser representados separadamente.**

### **1. CAIXA — 4 atores funcionais**

| Ator | Incentivo ou interesse predominante | Decisão |
| --- | --- | --- |
| **1. CAIXA — gestão de pagamentos** | Efetivar pagamentos corretamente, cumprir obrigações contratuais e controlar custos operacionais. | Separado |
| **2. CAIXA — atendimento CAIXA Cidadão** | Atender demandas, fornecer informações e cumprir indicadores de atendimento. | Separado |
| **3. CAIXA — SAC e Ouvidoria** | Tratar reclamações, corrigir falhas e cumprir exigências regulatórias. | Agrupados |
| **4. CAIXA — rede presencial** | Executar serviços presenciais dentro das atribuições de cada unidade. | Agências, lotéricas e correspondentes agrupados, com funções diferenciadas nas fichas. |
| Fornecedores terceirizados potenciais | Executar serviços contratados e cumprir metas comerciais e operacionais. | Não entram como atores confirmados. |

**Justificativa:** a área de pagamentos pode considerar uma operação corretamente processada enquanto o atendimento recebe reclamações de cidadãos que não receberam o crédito. Separar esses grupos permite representar esse conflito de perspectivas.

SAC e Ouvidoria ficam agrupados no mapa por integrarem a trajetória de reclamação, embora suas competências e níveis de escalonamento sejam diferentes.

Os fornecedores terceirizados permanecem como **atores condicionais**, em uma relação pontilhada com a CAIXA, identificada como subcontratação possível, não comprovada. Não serão contabilizados entre os quatro atores confirmados.

### **2. MTE — 4 atores funcionais**

| Ator | Incentivo ou interesse predominante | Decisão |
| --- | --- | --- |
| **1. MTE — gestão do benefício** | Garantir a concessão e o pagamento conforme os critérios legais, controlando irregularidades e recursos. | Separado |
| **2. MTE — gestão e fiscalização contratual** | Verificar a execução dos contratos, atestar serviços e controlar despesas e resultados. | Gestores e fiscais agrupados |
| **3. MTE — SRTE** | Prestar atendimento presencial e solucionar demandas dentro de suas competências. | Separado |
| **4. MTE — Ouvidoria** | Receber, encaminhar e acompanhar manifestações dos cidadãos. | Separado |

A separação é necessária porque **o interesse da gestão do benefício não é necessariamente idêntico ao da fiscalização contratual**. Uma área acompanha a regularidade da concessão; a outra verifica a prestação dos serviços contratados.

Esses interesses são hipóteses analíticas fundamentadas nas atribuições funcionais, não evidências de conflitos efetivos entre servidores.

### **3. Onde fica o fiscal de contrato?**

**Escolho manter a gestão e fiscalização contratual do MTE no círculo externo, mas conectada diretamente ao núcleo operacional do mapa.**

A justificativa é que esse grupo não participa normalmente da resolução individual da parcela, mas influencia a estrutura de incentivos do atendimento.

Relação contratual no mapa

Representação conceitual da relação de governança. A remuneração por atendimento está documentada no Contrato nº 11/2021; sua continuidade nos mesmos termos em 2026 não deve ser presumida.

A relação contratual aparecerá por uma **seta de natureza financeira e de prestação de contas**, identificada como “medição, ateste e remuneração do atendimento por URA — Contrato 11/2021”.

Isso permite observar uma hipótese importante: a remuneração por ligação pode criar incentivos diferentes daqueles associados à resolução definitiva do problema do cidadão. Entretanto, o contrato, isoladamente, não demonstra que a CAIXA estimule recontatos ou que a remuneração aumente efetivamente a demanda de falha.

### **4. Decisão consolidada**

O mapa terá **8 atores funcionais vinculados à CAIXA e ao MTE**, distribuídos entre o núcleo operacional e o círculo externo.

O fiscal de contrato permanecerá no círculo externo, mas sua relação com a CAIXA será explícita, com destaque para o fluxo financeiro e para os indicadores de execução contratual.

Assim, o mapa não confundirá participação direta na jornada com capacidade de influenciar seu funcionamento. A fiscalização contratual terá visibilidade proporcional à sua importância, sem ser apresentada como responsável pela resolução individual das demandas.

---

## Rodada 6

### Pergunta do entrevistador (Claude — grill-me)

Decisão registrada:
- **CAIXA em 4 atores funcionais:** gestão de pagamentos; atendimento CAIXA Cidadão; SAC e Ouvidoria; rede presencial.
- **MTE em 4 atores funcionais:** gestão do benefício; gestão e fiscalização contratual; SRTE; Ouvidoria.
- **Fornecedores terceirizados:** ficam como ator **condicional**, ligados por uma linha pontilhada.
- **Fiscal de contrato:** fica no **círculo externo**, mas com uma seta financeira explícita até a CAIXA, com o rótulo "medição, ateste e remuneração do atendimento por URA — Contrato 11/2021".

O argumento sobre a área de pagamentos e a área de atendimento da CAIXA está bem construído: uma considera o pagamento processado enquanto a outra recebe a reclamação de quem não recebeu.

**Rodada 6 — O cidadão: um ator ou vários?**

Até agora você fatiou com cuidado **as instituições**, mas o centro do seu mapa, o **cidadão**, continua sendo um só. A v3 traz quatro segmentos com barreiras diferentes na URA:

1. **Trabalhador requerente "típico":** tem celular, sabe usar menus, liga porque a parcela não caiu.
2. **Usuários rurais e com baixo letramento digital:** a v3 mostra que a cobertura de rede móvel é muito menor na zona rural, e menus de voz complexos excluem quem tem dificuldade de compreensão.
3. **Pessoas surdas ou com deficiência auditiva ou de fala:** para elas, uma URA **exclusivamente sonora é uma barreira total**. A CAIXA oferece atendimento em Libras, mas a v3 não comprova que ele exista para a URA.
4. **Familiares e pessoas de apoio:** ligam *pelo* trabalhador. Batem na autenticação e no sigilo de dados: a URA pede o CPF do titular, e o familiar não pode legalmente receber certas informações.

Pelo seu critério de granularidade da Rodada 5 (responsabilidades, incentivos ou capacidades diferentes viram atores separados), os quatro segmentos têm **capacidades de interação com a URA radicalmente diferentes**. Por coerência, deveriam ser separados.

O custo é que eles **não têm evidência estatística**: a v3 classifica a participação de cada segmento nas chamadas como "não quantificada", e a dos familiares como "hipótese".

**Pergunta:** como você representa o cidadão no mapa?
- **(a)** Um único ator "Cidadão", com os segmentos descritos só na ficha.
- **(b)** Os segmentos como **atores separados**.
- **(c)** Uma solução intermediária.

Em qualquer caso, diga especificamente **o que acontece com os familiares**. Eles são atores do mapa (e então, com qual relação com a URA, se ela pode barrá-los?) ou ficam fora por falta de evidência?

### Resposta da aluna (Flavia Rios)

**Escolho a opção (c) — solução intermediária:** manter o cidadão como ator central, mas representar separadamente os segmentos que apresentam barreiras de acesso significativamente diferentes.

Essa escolha preserva o foco na experiência do usuário sem criar a falsa impressão de que conhecemos a quantidade ou a frequência de chamadas realizadas por cada segmento.

### **1. Critério de segmentação**

Um segmento do cidadão será representado separadamente quando:

1. Apresentar uma **barreira específica de acesso, interação ou resolução** que não seja adequadamente representada pelo cidadão típico.
2. Essa barreira exigir uma **adaptação do atendimento, um canal alternativo ou uma relação diferente com os demais atores**.

A segmentação não depende de comprovação estatística da quantidade de usuários. Entretanto, é necessário distinguir barreiras documentadas de situações hipotéticas.

### **2. Aplicação aos quatro segmentos**

| Segmento | Representação | Justificativa |
| --- | --- | --- |
| **Trabalhador requerente típico** | Ator central | Representa a jornada de referência: o titular entra em contato para consultar uma parcela não recebida. |
| **Usuários rurais e com baixo letramento digital** | Subgrupo do cidadão | Enfrentam barreiras de conectividade e compreensão dos canais, que podem exigir atendimento alternativo. |
| **Pessoas surdas ou com deficiência auditiva ou de fala** | Subgrupo do cidadão | A interação exclusivamente sonora pode impedir o acesso, exigindo recursos de acessibilidade ou outro canal. |
| **Familiares e pessoas de apoio** | Ator auxiliar, condicional | Podem tentar intermediar o contato, mas sua participação efetiva na URA e os limites de autenticação ainda precisam ser verificados. |

Os segmentos não serão tratados como categorias mutuamente exclusivas: uma pessoa pode, por exemplo, residir na zona rural e também apresentar deficiência auditiva.

### **3. O que acontece com os familiares?**

**Incluo familiares e pessoas de apoio como ator auxiliar condicional**, visualmente distinto dos atores com participação documentada.

A justificativa é que sua possível participação cria uma relação diferente daquela existente entre o titular e a URA: a tentativa de intermediação em nome de outra pessoa.

A representação será:

Setas contínuas representam a jornada de referência; setas tracejadas indicam relações hipotéticas que precisam de validação.

O familiar poderá aparecer como alguém que tenta acessar o canal, mas **não será presumido que consegue consultar dados protegidos, superar a autenticação ou representar legalmente o titular**.

A possibilidade de a URA barrar o atendimento não elimina o familiar do mapa: uma tentativa frustrada de interação também pode ser relevante para compreender barreiras do serviço. Porém, sem evidência de sua ocorrência, essa relação será explicitamente identificada como hipótese.

### **4. Decisão consolidada**

O mapa terá **um ator central — o trabalhador titular —, dois subgrupos de usuários com barreiras específicas e um ator auxiliar condicional — familiares e pessoas de apoio**.

Essa estrutura permite investigar desigualdades de acesso e necessidades de acessibilidade sem atribuir frequências não demonstradas aos segmentos.

Na entrevista de construção do mapa, a participação dos familiares será uma hipótese a validar, e não um fato consolidado sobre o funcionamento da URA da CAIXA.

---

## Rodada 7

### Pergunta do entrevistador (Claude — grill-me)

Decisão registrada. O mapa terá:
- **Ator central:** o trabalhador titular.
- **Dois subgrupos com barreiras específicas:** rurais e com baixo letramento digital; pessoas surdas ou com deficiência auditiva ou de fala.
- **Ator auxiliar condicional:** familiares e pessoas de apoio, ligados por **setas tracejadas** (hipótese), sem presumir que conseguem passar pela autenticação.

O critério de que a segmentação não depende de estatística, mas de uma barreira que exige adaptação, é defensável. A observação de que os segmentos não são mutuamente exclusivos também é boa.

**Rodada 7 — Os atores "de origem": onde nasce a falha que vira ligação**

Na Rodada 1, o seu critério incluiu no mapa quem tem "responsabilidade relevante pela **causa**" da demanda. A v3 aponta cinco atores que **nunca atendem o cidadão na URA**, mas podem ser a origem do "minha parcela não caiu":

1. **Empregador / RH:** a duplicidade entre o Empregador Web e o eSocial gera divergências e indeferimentos.
2. **Receita Federal:** com o CPF divergente, o benefício trava até a correção na origem.
3. **Banco recebedor:** quando a parcela vai para uma conta fora da CAIXA, a falha pode estar no último trecho.
4. **Dataprev, como organização:** você já tem o nó técnico "Sistema do Seguro-Desemprego (Dataprev)". Mas a Dataprev **empresa** tem interesses, contratos e equipes que corrigem e reprocessam. Ela precisa ser um ator separado do sistema, ou o nó técnico basta?
5. **Sine estadual e municipal:** é para onde o cidadão é encaminhado presencialmente. Diferentemente dos outros quatro, ele **atende** o cidadão, mas é um ente federativo diferente do MTE.

Pelo seu critério, os cinco entrariam no **mapa principal**, e o mapa já está grande. Contando o que você decidiu até agora, já são cerca de 15 atores e 4 nós técnicos, fora o círculo externo. Um mapa com mais de 20 nós no núcleo deixa de ser legível, e a Aula 03 lembra que **o propósito do mapa define o nível de detalhamento**.

**Pergunta:** para cada um desses cinco (Empregador, Receita Federal, banco recebedor, Dataprev organização e Sine estadual/municipal), decida: **mapa principal**, **fluxo de exceção** (uma camada à parte, ligada ao núcleo) ou **círculo externo**. E responda diretamente: a **Dataprev organização** vira um ator separado do nó técnico, ou não?

### Resposta da aluna (Flavia Rios)

**Escolho manter os cinco atores no mapa, mas distribuídos entre o núcleo principal e uma camada de fluxos de exceção.** Nenhum deles ficará no círculo externo, pois todos podem participar da causa ou da resolução de uma demanda individual.

Para preservar a legibilidade, aperfeiçoo o critério da Rodada 1:

- **Mapa principal:** atores que participam diretamente da jornada recorrente de atendimento, consulta, encaminhamento ou resolução.
- **Fluxos de exceção:** atores acionados quando a demanda exige corrigir uma inconsistência específica, verificar um pagamento ou resolver um problema fora do fluxo habitual.
- **Círculo externo:** atores que exercem influência normativa, regulatória ou fiscalizatória, sem participação operacional no episódio.

### **Classificação dos cinco atores**

| Ator | Localização | Justificativa |
| --- | --- | --- |
| **1. Empregador / RH** | Fluxo de exceção | Pode precisar corrigir informações trabalhistas que originaram divergências, mas não participa normalmente do atendimento telefônico. |
| **2. Receita Federal** | Fluxo de exceção | Atua na origem dos dados cadastrais, quando divergências de CPF exigem regularização antes do prosseguimento da demanda. |
| **3. Banco recebedor** | Fluxo de exceção | Participa da investigação de parcelas destinadas a contas de outras instituições financeiras, quando há divergência entre pagamento informado e crédito recebido. |
| **4. Dataprev — organização** | Mapa principal | É responsável por serviços tecnológicos essenciais ao processamento do benefício. Sua atuação pode influenciar consultas, inconsistências e reprocessamentos, embora sua intervenção em cada ligação não esteja comprovada. |
| **5. Sine estadual/municipal** | Mapa principal | Realiza atendimento presencial e pode participar diretamente da resolução ou encaminhamento da demanda, com responsabilidades institucionais diferentes das SRTE do MTE. |

### **Dataprev: organização e sistema são dois nós distintos?**

**Sim. A Dataprev será um ator institucional separado do nó técnico “Sistema do Seguro-Desemprego”.**

Essa separação é necessária porque representam elementos de naturezas diferentes:

- **Dataprev — organização:** possui responsabilidades contratuais e institucionais, equipes técnicas, recursos e capacidade de manutenção e evolução dos sistemas.
- **Sistema do Seguro-Desemprego — nó sociotécnico:** representa o processamento automatizado das informações e sua influência sobre o resultado da consulta ou do benefício.

A Dataprev não será representada como atendente do cidadão. Sua conexão com o sistema será identificada como **operação e sustentação tecnológica**, conforme as responsabilidades que forem documentalmente comprovadas.

### **Como evitar um mapa excessivamente grande?**

O mapa terá uma estrutura em camadas, sem representar todas as relações com o mesmo destaque.

Organização conceitual do mapa

**Círculo externo — Governança**

TCU, CODEFAT, CGU, BCB/CMN e fiscalização contratual

**Fluxos de exceção — Correção na origem**

Empregador/RH, Receita Federal e banco recebedor

**Mapa principal — Episódio de resolução**

**Cidadão → URA da CAIXA**

CAIXA, MTE, Dataprev, Central 158 e Sine estadual/municipal, com seus subgrupos operacionais pertinentes

As camadas representam funções analíticas, não uma hierarquia de importância entre instituições.

**Decisão consolidada:** mantenho Dataprev e Sine estadual/municipal no mapa principal, enquanto empregador, Receita Federal e banco recebedor ficam nos fluxos de exceção.

Essa estrutura preserva a análise das causas da demanda de falha sem sobrecarregar o núcleo visual. Os fluxos de exceção poderão ser detalhados separadamente, mantendo conexões explícitas com a jornada central do cidadão.

---

## Rodada 8

### Pergunta do entrevistador (Claude — grill-me)

Decisão registrada. O mapa agora tem **três camadas**:
- **Mapa principal (episódio de resolução):** cidadão → URA, CAIXA, MTE, Dataprev, Central 158 e Sine estadual/municipal.
- **Fluxos de exceção (correção na origem):** Empregador/RH, Receita Federal e banco recebedor.
- **Círculo externo (governança):** TCU, CODEFAT, CGU, BCB/CMN e fiscalização contratual.

A Dataprev vira **ator institucional separado** do nó técnico "Sistema do Seguro-Desemprego", e a relação entre os dois é de "operação e sustentação".

**Rodada 8 — Reconciliação: as camadas novas desalinham decisões antigas**

Ao criar a camada "fluxos de exceção", você mudou as regras do jogo. Algumas decisões anteriores agora ficaram inconsistentes:

1. **Dataprev (organização) no mapa principal.** A sua definição nova de mapa principal é: "participam **diretamente** da jornada recorrente". Mas você mesma escreveu que a "intervenção [da Dataprev] em cada ligação não está comprovada". Na jornada recorrente, quem participa é o **nó técnico** (o sistema que responde à consulta). A Dataprev organização entra quando alguém precisa **corrigir ou reprocessar**, o que é exatamente a sua definição de fluxo de exceção. Pelas suas próprias regras, ela não deveria descer para a camada de exceção?

2. **Judiciário, MP e Defensorias.** Na Rodada 2, você os colocou no "mapa principal, em fluxo excepcional", porque ainda não existia a camada de exceção. Agora existe. Eles continuam no principal ou descem?

3. **Atores que ainda não foram posicionados:**
   - **INSS (institucional):** executa o Contact Center do 158 via TED. Você o citou na Rodada 4 como "ator institucional associado", mas sem camada.
   - **MGI (governança do gov.br):** você transformou o gov.br em rótulo de seta na Rodada 4. A organização que responde pelo login fica onde, ou fica fora?
   - **Pescadores artesanais e o INSS legado do seguro-defeso:** a v3 diz que o recorte é o trabalhador formal, mas o contrato de pagamento cobre outras modalidades. Eles entram ou ficam fora?
   - **Operadores do Contact Center 158:** você os criou na Rodada 4. Confirme a camada.

**Pergunta:** reposicione a Dataprev organização e o Judiciário/MP/Defensorias à luz das camadas novas, e posicione o INSS, o MGI, os pescadores/INSS legado e os operadores do 158. Para cada um: **principal**, **exceção**, **círculo externo** ou **fora do mapa**, com uma frase de justificativa.

### Resposta da aluna (Flavia Rios)

**Concordo com a necessidade de reconciliação.** As decisões das Rodadas 2 e 7 precisam ser ajustadas à estrutura de três camadas definida posteriormente.

Mantenho o recorte da Rodada 1: **o episódio de resolução da demanda do trabalhador formal que procura a URA da CAIXA**.

### **1. Reposicionamento dos atores**

| Ator | Classificação final | Justificativa |
| --- | --- | --- |
| **Dataprev — organização** | **Exceção** | A participação recorrente ocorre por meio do sistema; a intervenção de equipes da Dataprev em correções ou reprocessamentos específicos não está demonstrada para cada atendimento. |
| **Judiciário** | **Exceção** | Pode atuar na resolução individual quando o cidadão judicializa uma demanda não solucionada administrativamente. |
| **Ministério Público** | **Exceção** | Pode atuar em situações que demandem sua intervenção institucional, mas não constitui uma etapa habitual da resolução. |
| **Defensorias Públicas** | **Exceção** | Podem prestar assistência jurídica ao cidadão e promover medidas para solucionar sua demanda, quando cabível. |
| **INSS — execução do Contact Center 158** | **Principal** | Participa institucionalmente da prestação do canal alternativo de atendimento por meio do TED com o MTE. |
| **MGI — governança do gov.br** | **Exceção** | Sua atuação torna-se relevante quando problemas de autenticação ou recuperação de acesso exigem solução fora do fluxo habitual. |
| **Pescadores artesanais** | **Fora do mapa** | Pertencem a outra modalidade do Seguro-Desemprego, excluída do recorte principal definido para o trabalhador formal. |
| **INSS — legado do seguro-defeso** | **Fora do mapa** | Sua responsabilidade histórica nessa modalidade não integra o episódio de resolução do trabalhador formal estudado. |
| **Operadores do Contact Center 158** | **Principal** | Atendem diretamente os cidadãos encaminhados ao 158, podendo orientar e encaminhar suas demandas. |

### **2. Distinção importante: Dataprev e INSS**

A diferença de posicionamento entre as duas instituições não é contraditória.

**Dataprev:** o sistema participa do processamento das informações do benefício, mas isso não significa que suas equipes intervenham diretamente na jornada habitual de atendimento. Portanto, a organização fica na camada de exceção, enquanto o sistema permanece como nó técnico do mapa principal.

**INSS:** sua participação institucional na execução do Contact Center 158 está documentada. Por isso, permanece no mapa principal, associado aos operadores humanos e ao canal 158, sem presumir que servidores do INSS atendam pessoalmente todas as chamadas.

### **3. Ajuste no critério das camadas**

Para eliminar a ambiguidade, consolido as definições:

- **Mapa principal:** atores humanos ou institucionais e nós técnicos que integram a prestação habitual dos canais utilizados no episódio de resolução, mesmo quando sua participação ocorre nos bastidores.
- **Fluxos de exceção:** atores acionados em situações específicas de correção, contestação, recuperação de acesso ou resolução jurídica, que não integram necessariamente o percurso habitual.
- **Círculo externo:** atores de normatização, regulação, fiscalização e governança estrutural, sem participação operacional na resolução individual.
- **Fora do mapa:** atores vinculados a modalidades ou processos que ultrapassam a fronteira definida.

Uma ressalva: a classificação na camada de exceção indica uma **possibilidade de participação**, não comprova que o encaminhamento ocorra efetivamente. As relações ainda não documentadas serão representadas como hipóteses.

### **4. Decisão consolidada**

Com esses ajustes, o mapa mantém o **cidadão trabalhador formal como centro da análise**, a URA como nó sociotécnico central do atendimento e a CAIXA e o MTE como instituições subdivididas por funções.

A Dataprev institucional, o MGI e os atores jurídicos passam para os fluxos de exceção. O INSS, exclusivamente em seu papel no Contact Center 158, e os operadores desse canal permanecem no mapa principal.

**O critério determinante deixa de ser a importância institucional do ator e passa a ser sua função concreta dentro do episódio de resolução.** Isso permite controlar o tamanho do mapa sem eliminar as relações necessárias para compreender a origem, a continuidade e a solução das demandas de falha.

---

## Rodada 9

### Pergunta do entrevistador (Claude — grill-me)

Reconciliação feita. O critério final agora é a **função concreta no episódio**, e não a importância institucional. Ficou assim:

- **Mapa principal:**
  - Cidadão titular e os 2 subgrupos.
  - URA (nó central), Central 158, Sistema do Seguro-Desemprego e CTPS Digital / Emprega Brasil (nós técnicos).
  - CAIXA em 4 atores: pagamentos, CAIXA Cidadão, SAC/Ouvidoria e rede presencial.
  - MTE em 3 atores: gestão do benefício, SRTE e Ouvidoria.
  - INSS (execução do 158), operadores do 158 e Sine estadual/municipal.
- **Fluxos de exceção:** Empregador/RH, Receita Federal, banco recebedor, Dataprev (organização), MGI, Judiciário, MP e Defensorias.
- **Círculo externo:** TCU, CODEFAT, CGU, BCB/CMN e a fiscalização contratual do MTE.
- **Condicionais, com seta tracejada:** familiares e fornecedores terceirizados.
- **Fora do mapa:** pescadores e INSS legado do seguro-defeso.

**Rodada 9 — O formato do mapa e o significado das setas**

O tutorial dá duas opções para o arquivo `C_mapa_atores.md`:

- **(A) Tabela RACI:** para cada ator, quem é **R**esponsável (executa), quem é **A**provador (responde pelo resultado), quem é **C**onsultado e quem é **I**nformado. A RACI obriga a responder a pergunta mais dura do seu caso: **quem responde, no fim, pelo "minha parcela não caiu"?** O MTE, que gera a parcela? A CAIXA, que paga? Se ninguém é claramente o "A", isso é um achado. Mas a RACI não mostra bem camadas, nós técnicos e setas tracejadas, que você construiu com cuidado.
- **(B) Diagrama mermaid + tabela de atores:** mostra as três camadas, a diferença visual entre organizações e sistemas e as setas contínuas e tracejadas. Mas um diagrama com cerca de 25 nós e setas sem tipo vira um emaranhado.

Qualquer que seja o formato, as setas precisam ter **tipos**. A v3 sugeriu oito: **dinheiro, dados, autoridade/norma, atendimento, orientação, encaminhamento, controle e reclamação**. Oito estilos de seta é demais para ler, e poucos tipos misturam coisas diferentes. Por exemplo, "encaminhamento" (o 158 manda o cidadão ao Sine) não é a mesma coisa que "dados" (a CAIXA devolve ao MTE o arquivo de retorno do pagamento).

**Pergunta:**
1. Qual formato você escolhe, **A** ou **B**?
2. **Quais tipos de relação** você mantém (no máximo 5)? Quais dos oito você funde ou descarta?
3. Se escolher B, quer também uma pequena tabela RACI **só para a demanda "parcela não caiu"**? Se sim, diga quem é o **A** (quem responde pelo resultado).

### Resposta da aluna (Flavia Rios)

**Escolho a opção B — Diagrama Mermaid + tabela de atores**, complementada por uma pequena matriz RACI específica para a demanda “minha parcela não caiu”.

Essa combinação permite representar a complexidade institucional sem perder a perspectiva da responsabilização pelo resultado.

### **1. Formato do mapa**

O arquivo `C_mapa_atores.md` terá três componentes:

1. **Diagrama Mermaid:** representará o núcleo principal, os fluxos de exceção e o círculo externo, distinguindo visualmente atores humanos, organizações e nós sociotécnicos.
2. **Tabela de atores:** apresentará papel, interesses, poder, dependências e evidências de cada ator.
3. **Matriz RACI complementar:** esclarecerá responsabilidades nas diferentes causas possíveis de uma parcela não recebida.

Para preservar a legibilidade, o diagrama principal mostrará apenas as relações essenciais. Os vínculos secundários serão documentados na tabela.

### **2. Tipos de relação — cinco categorias**

| Tipo mantido | Tipos originais incorporados | Significado |
| --- | --- | --- |
| **1. Atendimento** | Atendimento + orientação | Interação para esclarecer dúvidas, prestar informações ou orientar o cidadão. |
| **2. Encaminhamento** | Encaminhamento + reclamação | Transferência da demanda para outro canal ou instância, incluindo escalonamento de reclamações. |
| **3. Dados** | Dados | Consulta, transmissão, atualização ou retorno de informações entre sistemas e instituições. |
| **4. Financeira** | Dinheiro | Pagamento do benefício e remuneração contratual, com identificação do objeto de cada fluxo. |
| **5. Governança** | Autoridade/norma + controle | Definição de regras, supervisão, fiscalização e prestação de contas. |

As cinco categorias serão diferenciadas por rótulos curtos nas setas, sem depender exclusivamente de cores.

**Convenção adicional:** setas contínuas indicarão relações documentadas; setas tracejadas, relações hipotéticas ou ainda não confirmadas. O tracejado indicará grau de evidência, não um sexto tipo de relação.

### **3. Matriz RACI — “Minha parcela não caiu”**

**Sim, incluirei uma RACI complementar.** Entretanto, não atribuirei um único responsável final a todas as situações, porque a frase do cidadão pode representar problemas diferentes.

A matriz será dividida por etapa e competência.

| Situação identificada | R — Executa | A — Responde pelo resultado da etapa |
| --- | --- | --- |
| Parcela não liberada por problema de habilitação ou bloqueio administrativo | Área competente do MTE | **MTE — gestão do benefício** |
| Parcela liberada, mas pagamento não processado corretamente pela CAIXA | CAIXA — gestão de pagamentos | **CAIXA — gestão de pagamentos** |
| Crédito enviado para outra instituição, mas não localizado na conta de destino | CAIXA e banco recebedor, conforme a etapa em que ocorreu a falha | **Responsável pela etapa comprovadamente falha**, a identificar após rastreamento |
| Informação cadastral inconsistente | Órgão ou entidade responsável pelo dado de origem | **Responsável pela correção cadastral**, conforme o tipo de inconsistência |

As colunas C e I serão preenchidas conforme a situação concreta, sem presumir acesso irrestrito de todos os atores aos dados do cidadão.

### **4. Quem é o “A” final?**

**Não existe evidência suficiente para atribuir um único “A” operacional a todas as causas de parcela não recebida.**

Minha decisão é distinguir:

- **MTE:** responsável pela gestão pública do benefício e pelas decisões administrativas de concessão.
- **CAIXA:** responsável pela execução das obrigações de pagamento que lhe competem contratualmente.
- **Outros participantes:** responsáveis por etapas específicas, quando identificadas.

A ausência de um responsável único pelo episódio completo será registrada como **hipótese de fragmentação da responsabilização**, e não como falha institucional já comprovada.

**Decisão consolidada:** o mapa será apresentado em Mermaid, com cinco tipos de relação e três camadas. A RACI será utilizada apenas para explicitar as responsabilidades nas situações relacionadas à parcela não recebida, preservando a distinção entre quem responde por uma etapa e quem coordena a solução percebida pelo cidadão.

---

## Rodada 10

### Pergunta do entrevistador (Claude — grill-me)

Decisão registrada:
- **Formato B:** diagrama mermaid, tabela de atores e uma RACI complementar.
- **5 tipos de relação:** atendimento, encaminhamento, dados, financeira e governança. O tracejado marca o grau de evidência, e não um sexto tipo.
- **RACI por situação:** o "A" muda conforme a causa. A ausência de um "A" único para o episódio inteiro fica registrada como **hipótese de fragmentação da responsabilização**.

**Rodada 10 — Quem é o "dono" do episódio? (última rodada)**

Na sua RACI, cada **etapa** tem um responsável, mas o **episódio** não tem. Só que o cidadão não vive etapas, ele vive o episódio. Ele liga para a URA da CAIXA e diz "minha parcela não caiu" sem saber se o problema é de habilitação, de pagamento, de banco recebedor ou de CPF. Alguém precisa **diagnosticar a causa e direcionar o caso**. Se ninguém faz isso, o cidadão faz sozinho, e é exatamente aí que nascem a peregrinação e a demanda de falha que a v3 documenta.

Pela v3, na prática:
- A **URA e o CAIXA Cidadão** só veem o domínio da CAIXA. No 11/2021, a URA era contratada para informar "situação de parcelas e pagamentos".
- O **158** vê o domínio do MTE, mas não o extrato bancário.
- **Ninguém está documentado** como responsável por coordenar a resolução **entre** instituições. O Portal de Demandas é institucional, e o cidadão não tem acesso a ele.

Você mencionou, no fim da sua resposta, "quem coordena a solução percebida pelo cidadão". A pergunta é justamente essa.

**Pergunta:** no seu mapa, como fica a **coordenação do episódio**?
- **(a)** Você atribui a coordenação a um ator existente (qual, e com que base na evidência?).
- **(b)** Você representa **explicitamente a ausência** de coordenação. Por exemplo, um nó vazio ou uma nota "sem coordenador do episódio", com o **cidadão** fazendo as setas de encaminhamento entre os canais.
- **(c)** Outra solução.

Diga também se essa decisão aparece **no diagrama** ou só no texto.

### Resposta da aluna (Flavia Rios)

**Escolho a opção (b) — representar explicitamente a ausência de um coordenador do episódio documentalmente identificado.**

Essa decisão é coerente com a fronteira escolhida na Rodada 1: acompanhar a demanda do cidadão desde o problema que motivou a ligação até sua resolução ou abandono.

### **1. Justificativa**

A pesquisa demonstra que existem responsabilidades institucionais distribuídas:

- **CAIXA:** presta informações sobre parcelas e pagamentos e executa suas obrigações como agente pagador.
- **MTE:** responde pela gestão do benefício, incluindo decisões administrativas de habilitação e bloqueio.
- **Central 158:** oferece atendimento no âmbito do MTE.
- **Outros atores:** podem ser necessários para corrigir inconsistências cadastrais, trabalhistas ou bancárias.

Entretanto, **não foi identificada evidência documental de um ator formalmente responsável por acompanhar o episódio completo, diagnosticar problemas entre instituições e assegurar uma resposta integrada ao cidadão**.

Isso não comprova que a coordenação inexista na prática. Significa que ela não foi demonstrada pelas fontes examinadas.

### **2. Como representar no mapa**

**A lacuna aparecerá diretamente no diagrama Mermaid**, e não apenas no texto.

Representação conceitual da coordenação do episódio

O quadro superior representa uma lacuna de responsabilidade identificada na pesquisa, não uma instituição ou um ator fictício.

As setas entre o cidadão e os diferentes canais indicarão os contatos e recontatos necessários ou possíveis. Quando não houver comprovação de encaminhamento institucional, não será desenhada uma seta que sugira transferência automática do caso.

### **3. Consequência para a RACI**

A matriz manterá os responsáveis pelas etapas, mas acrescentará uma linha específica:

| Atividade | R | A |
| --- | --- | --- |
| Diagnóstico e coordenação da resolução interinstitucional do episódio completo | Não identificado | **Não identificado** |

Essa ausência será registrada como **lacuna de responsabilização documental**, e não como prova definitiva de inexistência de coordenação.

### **4. Decisão final**

O cidadão não será classificado como responsável institucional pela coordenação. Entretanto, o mapa mostrará que, **na ausência de um mecanismo integrado comprovado, ele pode acabar assumindo o esforço prático de procurar diferentes canais e acompanhar sua própria demanda**.

Essa distinção é fundamental: o cidadão pode carregar o ônus da fragmentação sem ter autoridade para resolvê-la.

**Conclusão:** o mapa evidenciará tanto os atores responsáveis por cada etapa quanto a falta de identificação de um responsável pelo episódio completo. Essa será uma das principais questões analíticas do trabalho, a ser validada posteriormente, e estará visível no diagrama, na tabela de atores e na RACI.

---

## Encerramento

**Entrevistador:** a entrevista chegou a 10 rodadas. As decisões tomadas pela aluna (fronteira, critérios de camada, modelo híbrido de sistemas, granularidade da CAIXA e do MTE, segmentação do cidadão, posição dos atores de origem e de exceção, formato do mapa, tipos de relação e representação da lacuna de coordenação) são a base do arquivo `C_mapa_atores.md`.
