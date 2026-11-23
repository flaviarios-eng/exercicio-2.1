# Auditoria da v1 — Mapa de atores do Atendimento ao Seguro-Desemprego pela URA da Caixa

**Assistente auditor:** Claude (Anthropic). **Pesquisa auditada:** `B_relatorio_assistente_v1.md`, produzida pelo ChatGPT (OpenAI).

**Critério:** só entram falhas de conteúdo: erros factuais, lacunas de evidência, inferências mal-suportadas, fontes fracas ou mal atribuídas, atribuições incorretas e atores omitidos. Questões de formatação e estilo foram desconsideradas.

## Avaliação geral

A v1 tem méritos reais. Ela separa fato documentado de hipótese, admite lacunas e corrige a premissa do objeto ao distinguir o 0800 da CAIXA do 158 do MTE. Ainda assim, a pesquisa tem uma **omissão grave sobre o próprio objeto (a URA da CAIXA)**, várias **fontes atribuídas incorretamente**, um **erro factual** sobre os dados do 158, **atores relevantes ausentes** e algumas **inferências que vão além da evidência**. As falhas estão numeradas por gravidade.

---

## Falha 1 — Omissão de evidência central: existe contrato público em que o MTE paga a CAIXA por "Atendimento URA"

**Tipo:** lacuna de evidência e ator/relação omitidos.

**Trecho da v1:** "Informação não localizada — árvore atual dos menus da URA CAIXA Cidadão, [...] fornecedor específico da plataforma, regras internas de roteamento [...] e indicadores exclusivos da URA referentes ao benefício." E também: "não foi localizada evidência pública de uma 'URA do Seguro-Desemprego da CAIXA' autônoma".

**Justificativa:** o MTE tem um contrato público com a CAIXA para o pagamento do **Abono Salarial** (Contrato MTE nº 04/2023, vigência de 02/04/2023 a 02/04/2028). Esse contrato tem um item específico, **"Atendimento URA"**: cerca de 110,8 milhões de ligações estimadas em 60 meses, a R$ 0,62 por ligação, em um total de aproximadamente R$ 68,7 milhões. O Projeto Básico descreve o serviço como uma central de atendimento gratuita ao trabalhador, via URA, restrita a informações sobre o pagamento do benefício. O faturamento é feito **por ligação atendida**.

Isso importa para o mapa de atores por três motivos:
- **A URA da CAIXA é um serviço contratado e remunerado pelo MTE**, e não apenas um canal próprio do banco. O MTE é contratante e financiador, e há gestores e fiscais de contrato envolvidos. Esses atores e relações estão ausentes da v1.
- **A remuneração por ligação cria um incentivo** diretamente ligado à demanda de falha: quanto mais ligações o cidadão precisar fazer, maior a receita do prestador. A v1 discute demanda de falha sem considerar essa estrutura de incentivo.
- A v1 deveria ter verificado se os contratos do **Seguro-Desemprego** têm item equivalente. Na parte visível do Contrato MTE nº 07/2026, há um único item: pagamento de parcelas, a R$ 2,25 por parcela. Não aparece nenhum item de URA. **A diferença entre os contratos do Abono e do Seguro-Desemprego é, em si, um achado a investigar**: quem paga a URA quando o assunto é Seguro-Desemprego? Ela está embutida na tarifa de pagamento? É custeada pela própria CAIXA?

---

## Falha 2 — Leitura incompleta do Contrato nº 07/2026, que a própria v1 cita

**Tipo:** lacuna de evidência e atores omitidos.

**Trecho da v1:** "o novo Contrato MTE nº 07/2026 com a CAIXA [...] cujo objeto é a operacionalização dos pagamentos do benefício."

**Justificativa:** a v1 usa o contrato só para confirmar que a CAIXA é agente pagador e para informar o valor. Ela ignora cláusulas do Termo de Referência que afetam diretamente o mapa de atores:
- O TR admite **subcontratar o "atendimento ao público"** como serviço acessório. Isso abre espaço para **empresas terceirizadas** no atendimento da CAIXA, um ator que a v1 só considera para o 158.
- Existe um **Portal de Demandas** (atendimentogoverno.caixa.gov.br). É um canal institucional entre MTE e CAIXA, usado por perfis técnicos e gerenciais. Trata-se de um processo de bastidor e de um ponto de coordenação interinstitucional que não aparece na v1.
- A **contestação de saque** deve ser formalizada numa unidade do **contratante (MTE)**, e não da CAIXA. Isso é uma fonte direta de encaminhamento cruzado: o cidadão liga para a CAIXA e é mandado ao MTE.
- O TR atribui à CAIXA o **atendimento a beneficiários com benefício bloqueado**.

Além disso, um termo de apostilamento indica que o **Contrato nº 11/2021**, o contrato anterior com a CAIXA para o mesmo objeto, recebeu dotação orçamentária para o exercício de 2026. A v1 não explica a transição entre os dois contratos nem se houve sobreposição.

---

## Falha 3 — Fontes atribuídas incorretamente ou que não sustentam o que é afirmado

**Tipo:** fontes fracas e atribuições incorretas.

- **Nota [3]:** o valor de R$ 383,3 milhões e a vigência 2026–2031 do Contrato 07/2026 são atribuídos à **Resolução CODEFAT nº 957/2022**. Uma norma de 2022 não pode sustentar dados de um contrato de 2026. A fonte correta é o próprio termo de contrato.
- **Nota [46]:** o Contrato 07/2026 aponta para a página genérica do Plano de Contratações Anual (PCA 2026), e não para o documento do contrato.
- **Notas [13] e [14]:** a afirmação "confirmada pelo TCU como característica da arquitetura vigente auditada em 2025–2026" é atribuída à Resolução 957/2022, e não ao acórdão do TCU.
- **Nota [30]:** a ficha do TCU remete a uma busca no portal do TCU pelos termos "inexigibilidade E economicidade", que não tem relação com o Seguro-Desemprego.
- **Notas [20] e [52]:** a afirmação de que existem "pelo menos cinco camadas distintas" nos bastidores cita a página de "Competências" do MTE. Essa página não descreve essa arquitetura. É uma **inferência da própria v1 apresentada como fato com fonte**.
- **Notas [12] e [25]:** o TED nº 9/2026 é citado apontando para a página que lista todos os TEDs, e não para o documento específico. Isso impede conferir os valores informados (R$ 9,416 milhões e R$ 248 mil).
- **Notas [31] e [49]:** o relatório da Ouvidoria aparece com o título "Verde Escuro e Laranja Quadrante Fonte Grande Governo Relatório de Progresso dos ODS". O título não corresponde ao documento, o que prejudica a rastreabilidade.
- **Dataprev:** o texto do Capítulo 2 sustenta o papel da Dataprev com o Acórdão 2.167/2022 (notas [10] e [28]). Já a Base de Evidências atribui o mesmo ponto ao Acórdão 135/2024 (nota [48]). Em nenhum dos casos a v1 informa o número, o objeto ou a vigência do contrato MTE–Dataprev que afirma existir.

---

## Falha 4 — Erro factual sobre os dados da Central 158

**Tipo:** erro factual.

**Trecho da v1:** "Como o total foi publicado de forma arredondada ('mais de 1,7 milhão'), não é adequado transformar 23% em uma contagem exata de chamadas de Seguro-Desemprego."

**Justificativa:** o MTE divulgou o número exato: **1.726.914 atendimentos** no primeiro semestre de 2025. Com 23% dedicados ao Seguro-Desemprego, é possível estimar cerca de **397 mil atendimentos** sobre o tema no semestre, ressalvando o arredondamento do percentual. A v1 também omite que o **Abono Salarial respondeu por 48%** dos atendimentos. Esse dado é relevante porque Abono e Seguro-Desemprego disputam a mesma capacidade de atendimento em épocas de pico.

---

## Falha 5 — Escopo restrito ao trabalhador formal sem declaração explícita; outras modalidades e seus atores ficam de fora

**Tipo:** atores omitidos e delimitação não declarada.

**Trecho da v1:** a v1 inteira se baseia na auditoria do TCU sobre o "Seguro-Desemprego do trabalhador formal", mas fala do "Seguro-Desemprego" de modo geral.

**Justificativa:** o Seguro-Desemprego tem outras modalidades, que a própria página da CAIXA lista: **empregado doméstico**, **pescador artesanal** (o seguro-defeso) e **trabalhador resgatado de condição análoga à de escravo**. Todas são pagas pela CAIXA e podem chegar ao mesmo canal telefônico. A omissão é especialmente grave no caso do **seguro-defeso**: a **Medida Provisória nº 1.323/2025** transferiu a gestão do seguro-defeso do **INSS** para o **MTE**, para os defesos iniciados a partir de 1º de novembro de 2025. Isso trouxe novos atores e processos para o período estudado: INSS (passivo dos defesos anteriores), pescadores e suas colônias, entrevistas presenciais de habilitação, exigência de CadÚnico e TED com a Telebras para a operacionalização. Essa transição aumenta a probabilidade de demanda nos canais telefônicos em 2025–2026, e a v1 não a menciona.

---

## Falha 6 — INSS ausente do inventário, apesar de aparecer na própria v1

**Tipo:** ator omitido e inconsistência interna.

**Trecho da v1:** "o TED nº 9/2026 entre MTE e INSS [...] prevê prestação de serviços de Contact Center para trabalhadores e empregadores".

**Justificativa:** se o Contact Center que atende o 158 é prestado por meio de um TED com o INSS, o **INSS é um ator institucional** da jornada telefônica, como provedor da infraestrutura de teleatendimento. A v1 cria uma ficha para os "operadores do Contact Center MTE–INSS", mas não para o **INSS como instituição**. O INSS também não aparece nas Tabelas A e B. Somado ao papel do INSS no legado do seguro-defeso (Falha 5), isso deixa uma lacuna relevante.

---

## Falha 7 — Barreiras de acesso ao canal telefônico omitidas: custo da ligação e cobertura de rede móvel

**Tipo:** lacuna de evidência e inferência com base inadequada.

**Trecho da v1:** "Evidência contextual: em 2025, 90,5% da população de 10 anos ou mais utilizou internet, mas o índice rural foi 83%".

**Justificativa:** para um serviço **telefônico**, os indicadores de internet são uma evidência indireta. A v1 deixa de fora dados mais pertinentes:
- **Custo da ligação:** chamadas ao 158 feitas de celular podem ser tarifadas, ao contrário das centrais do INSS (135) e do 0800 da CAIXA. Está em tramitação o Projeto de Lei nº 2.574/2026, que busca tornar essas ligações gratuitas. Isso é uma **barreira econômica justamente para o desempregado**, e afeta a escolha entre o 158 e o 0800. Também cria um ator normativo (o Legislativo) e regulatório (a numeração e a tarifação no setor de telecomunicações).
- **Cobertura de rede móvel:** segundo a mesma PNAD TIC 2025, o serviço de rede móvel celular funcionava em apenas **68,0% dos domicílios rurais**, contra 96,1% dos urbanos. Para o canal telefônico, esse indicador é mais relevante que o uso de internet.
- **Motivo da não utilização da internet:** o IBGE aponta que "não saber usar" continua sendo o principal motivo. Esse dado sustenta melhor a ficha de baixo letramento digital do que o percentual de acesso.

---

## Falha 8 — Atores omitidos na etapa de pagamento e nos canais da CAIXA

**Tipo:** atores omitidos e atribuição incompleta.

**Trecho da v1:** "Dependendo da causa, a competência pode estar no MTE, [...] ou no estágio bancário executado pela CAIXA."

**Justificativa:**
- Segundo a CAIXA, o pagamento pode ser feito por **crédito em conta de outro banco, via TED**. Nesse caso, um **banco recebedor** participa da efetivação do crédito, e um problema de "parcela que não caiu" pode estar fora da CAIXA. A v1 atribui a efetivação do crédito somente à CAIXA.
- A CAIXA indica o **aplicativo CAIXA Tem** como canal para consultar o Seguro-Desemprego. É um canal digital do próprio agente pagador que complementa ou substitui a URA, e não é mencionado.
- O **SAC e a Ouvidoria da CAIXA** aparecem apenas como "eventualmente CAIXA". Na condição de instituição financeira, a CAIXA tem canais formais de reclamação, sujeitos à regulação bancária (Banco Central e Conselho Monetário Nacional). Esses atores não são descritos.

---

## Falha 9 — "Sine/SRTE" tratados como um único ator (atribuição incorreta)

**Tipo:** atribuição incorreta e granularidade inadequada.

**Trecho da v1:** "Ficha — Atendentes da rede Sine e SRTE" e, na Tabela A, "Sine/SRTE | atendentes/retaguarda".

**Justificativa:** as Superintendências Regionais do Trabalho são **unidades do próprio MTE** (federais). Os postos do **Sine** são, em grande parte, operados por **estados e municípios**, em parceria coordenada pelo MTE e financiada com recursos do FAT. São servidores de entes diferentes, com vínculos, incentivos, orçamento e capacidade distintos. Juntar os dois esconde **governos estaduais e municipais** como atores e esconde a relação federativa de financiamento, que é central para entender a capacidade do atendimento presencial para onde o telefone encaminha o cidadão.

---

## Falha 10 — CODEFAT tratado como ator monolítico, sem sua composição tripartite

**Tipo:** ator omitido e atribuição incompleta.

**Trecho da v1:** "Ficha — CODEFAT. Categoria: círculo 6. Papel: conselho deliberativo do FAT".

**Justificativa:** o CODEFAT é um conselho **tripartite e paritário**, com representantes dos trabalhadores (centrais sindicais), dos empregadores (confederações patronais) e do governo. Ao não registrar isso, a v1 omite que **sindicatos e entidades patronais têm poder normativo formal** sobre as regras do benefício. Na Ficha e no Capítulo 9, a v1 trata sindicatos apenas como intermediários de participação "não comprovada".

---

## Falha 11 — Autenticação e identidade digital sem ator responsável

**Tipo:** ator omitido.

**Trecho da v1:** "Solicitação | trabalhador, MTE | Gov.br, Emprega Brasil, CTPS Digital | [...] | barreiras de autenticação".

**Justificativa:** a v1 registra a autenticação como fonte de falhas, mas não identifica **quem é responsável pela identidade digital gov.br** (os níveis de conta e a recuperação de acesso). Esse papel cabe à estrutura de governo digital do Ministério da Gestão e da Inovação em Serviços Públicos, e não ao MTE. Quando o cidadão não consegue acessar o app e por isso liga, a causa está num ator que não aparece no mapa.

---

## Falha 12 — Inferências que vão além da evidência

**Tipo:** inferência mal-suportada.

- **Trecho:** "O fato de o Tribunal recomendar esses indicadores mostra que, no momento da auditoria, a governança pública disponível era insuficiente para demonstrar desempenho satisfatório." **Justificativa:** recomendar o monitoramento de indicadores não prova, por si só, que eles não existiam ou eram insuficientes. Seria preciso citar o trecho do acórdão que constata essa ausência.
- **Trecho:** "O Tribunal denominou esse fenômeno de 'síndrome do balcão'". **Justificativa:** a expressão é atribuída ao TCU entre aspas, mas sem página ou trecho. Ela não aparece nas comunicações públicas do TCU sobre o Acórdão 1.621/2026 consultadas nesta auditoria. Precisa de citação exata. Caso contrário, deve ser apresentada como rótulo analítico da própria v1. O mesmo vale para a afirmação de que o relatório classifica parte da demanda como "artificial".

---

## Falha 13 — Dados da Ouvidoria sem desagregação e sem ressalva de viés de canal

**Tipo:** lacuna de evidência e inferência.

**Trecho da v1:** "Em 2025, o MTE registrou 8.018 manifestações relacionadas ao Seguro-Desemprego".

**Justificativa:** o relatório semestral atualizado da Ouvidoria registra **3.444 manifestações sobre Seguro-Desemprego** num dos semestres. A v1 não mostra como chegou ao total anual nem cita página. Além disso, o mesmo relatório informa que **99,67% das manifestações foram registradas por meio digital**. Isso significa que os dados da Ouvidoria representam pouco justamente o público que depende do telefone. A v1 usa esses dados sem essa ressalva, inclusive na Tabela C, na linha "proporção originada por telefone".

---

## Falha 14 — Graus de certeza incoerentes com a própria evidência

**Tipo:** inferência mal-suportada.

**Trecho da v1 (Tabela A):** "Contact Center MTE–INSS | operadores/supervisão | [...] | TED 9/2026 | alta".

**Justificativa:** no texto, a própria v1 afirma que o "fornecedor final específico não [foi] identificado", e a existência de supervisores e equipes de qualidade é deduzida, e não documentada. Atribuir certeza "alta" contradiz o método de classificação que a v1 declarou. O mesmo ocorre com "Atendente CAIXA | certeza alta": a v1 admite que scripts, autonomia, métricas e até a forma de roteamento da URA para humanos não foram localizados.

---

## Síntese das correções esperadas na v2

1. Investigar a URA da CAIXA como **serviço contratado pelo MTE**, usando os contratos do Abono (04/2023) e do Seguro-Desemprego (11/2021 e 07/2026), e incluir MTE-contratante, fiscais de contrato e o incentivo de remuneração por ligação.
2. Corrigir as atribuições de fonte (notas 3, 12/25, 13/14, 20/52, 30, 31/49, 46 e Dataprev).
3. Corrigir o dado do 158 (1.726.914 atendimentos) e incluir o peso do Abono Salarial.
4. Declarar o escopo de modalidades e tratar o seguro-defeso (MP 1.323/2025) e o INSS.
5. Incluir os atores omitidos: INSS, bancos recebedores, CAIXA Tem, SAC/Ouvidoria CAIXA e reguladores bancários, entes estaduais e municipais do Sine, composição tripartite do CODEFAT, gestor da identidade gov.br e o tema da tarifação do 158.
6. Rever as inferências (indicadores do TCU, "síndrome do balcão", "demanda artificial") e os graus de certeza da Tabela A.

## Fontes consultadas pela auditoria

- Contrato MTE nº 04/2023 com a CAIXA (pagamento do Abono Salarial, item "Atendimento URA"): https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/licitacoes-e-contratos/contratos/pdf/04_2023completo.pdf
- Contrato MTE nº 07/2026 com a CAIXA (pagamento do Seguro-Desemprego): https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/licitacoes-e-contratos/pca/072026completo.pdf
- Termo de Apostilamento do Contrato nº 11/2021 (exercício 2026): https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/licitacoes-e-contratos/contratos/8Termo_de_Apostilamento.pdf
- CAIXA — página do Seguro-Desemprego (agente pagador, modalidades, crédito em outro banco via TED, CAIXA Tem): https://www.caixa.gov.br/beneficios-trabalhador/seguro-desemprego/Paginas/default.aspx
- TCU — notícia e sumário executivo do Acórdão 1.621/2026-Plenário (TC 015.553/2025-6): https://portal.tcu.gov.br/imprensa/noticias/tribunal-avalia-servico-digital-de-seguro-desemprego-para-trabalhadores-formais
- Central Alô Trabalho, 1.726.914 atendimentos no 1º semestre de 2025: https://www.contabeis.com.br/noticias/72162/alo-trabalho-bate-1-7-mi-de-atendimentos/ e https://amdjus.com.br/servico-alo-trabalho-atinge-marca-de-17-milhoes-de-atendimentos/
- Tarifação do 158 por celular e PL 2.574/2026: https://acritica.net/economia/projeto-ligacoes-gratuitas-inss-trabalho/
- IBGE — PNAD TIC 2025 (uso de internet urbano/rural): https://agenciadenoticias.ibge.gov.br/agencia-noticias/2012-agencia-de-noticias/noticias/47408-proporcao-de-usuarios-da-internet-no-pais-ultrapassou-90-da-populacao-de-10-anos-ou-mais-em-2025
- IBGE — PNAD TIC 2025 (rede móvel em domicílios rurais): https://agenciadenoticias.ibge.gov.br/en/agencia-news/2184-news-agency/news/47474-internet-chega-a-95-de-domicilios-do-pais-em-2027
- MP nº 1.323/2025 e transferência do seguro-defeso do INSS ao MTE: https://agenciagov.ebc.com.br/noticias/202511/seguro-defeso-passa-a-ser-administrado-pelo-ministerio-do-trabalho-e-emprego
- Ouvidoria do MTE — relatório semestral atualizado: https://www.gov.br/trabalho-e-emprego/pt-br/canais_atendimento/ouvidoria/relatorios/relatorio-semestral_atualizado.pdf
