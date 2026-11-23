# Segunda auditoria (sobre a v2) — Mapa de atores do Atendimento ao Seguro-Desemprego pela URA da Caixa

**Assistente auditor:** Claude (Anthropic), o mesmo da primeira auditoria. **Documento auditado:** `B_relatorio_assistente_v2.md` (ChatGPT, OpenAI).

**Escopo desta auditoria:**
- (a) verificar se cada falha apontada na primeira auditoria (Falhas 1 a 14) foi de fato endereçada;
- (b) identificar falhas novas introduzidas pela v2;
- (c) listar os pontos que continuam em aberto.

Questões de formatação e estilo não foram consideradas.

## Avaliação geral

A v2 respondeu de forma séria às 14 falhas. A tabela "Tratamento da auditoria" é clara, as correções de atribuição de fonte estão corretas e houve ganho real de rigor na separação entre fato, inferência e pendência. A v2 também acertou ao apontar um problema na própria auditoria anterior: a URL do IBGE em inglês tem um ano inconsistente no endereço. A observação procede, e a fonte primária correta aparece no fim deste documento.

Porém, **a v2 corrigiu as falhas e, ao mesmo tempo, apagou boa parte do conteúdo válido da v1**. Ela caiu de cerca de 5.900 para cerca de 3.800 palavras, e a perda não foi só de texto redundante. Também passou a **usar a auditoria como fonte**, em vez de verificar as fontes primárias. Como a v3 servirá de contexto único para a entrevista de construção do mapa de atores, essas regressões precisam ser revertidas.

---

## Parte A — As falhas da primeira auditoria foram endereçadas?

| Falha da audit_v1 | Endereçada? | Comentário e resíduo |
|---|---|---|
| 1. URA contratada no Abono | **Sim** | Bem tratada, com a hipótese de incentivo formulada com cautela. **Resíduo:** a v2 não verificou se o Contrato 11/2021 (o anterior do Seguro-Desemprego) tinha item de URA, nem se o número atendido no item URA do Abono é o mesmo 0800 726 0207. Ambas são verificações documentais possíveis, e não pendências inevitáveis. |
| 2. Cláusulas do Contrato 07/2026 | **Sim** | Subcontratação, Portal de Demandas, contestação de saque e bloqueio foram incorporados corretamente, com a ressalva de que permissão para subcontratar não prova subcontratação. |
| 3. Fontes mal atribuídas | **Parcialmente** | As notas da v1 foram corrigidas, mas surgiram novos problemas de fonte (ver N2 e N3). A fonte E5 é uma notícia do TCU, e não o acórdão. A própria v2 reconhece isso, mas continua apoiando achados do TCU somente nela. |
| 4. Dados do 158 | **Sim** | Total corrigido para 1.726.914. Ver N8 sobre a precisão aparente das estimativas. |
| 5. Modalidades e seguro-defeso | **Parcialmente** | Escopo declarado e defeso incluído. Mas a afirmação de que o Contrato 07/2026 inclui a "bolsa de qualificação profissional" não tem cláusula citada (ver N4). |
| 6. INSS | **Sim, com contradição** | O INSS entrou no inventário, mas a certeza "média" se apoia num TED que a própria v2 declara não validado (ver N7). |
| 7. Barreiras do canal telefônico | **Sim, sem verificação própria** | Tarifação do 158 e rede móvel rural incluídas, mas com base em "a auditoria relata" e "indicados na auditoria" (ver N2). |
| 8. Bancos recebedores, CAIXA Tem, SAC e regulação | **Sim** | Incorporados com boa distinção entre competência bancária e concessão. Banco Central e CMN aparecem sem fonte. |
| 9. Sine × SRTE | **Sim, sem fonte** | Separação feita, mas a v2 afirma "explicitada coordenação e financiamento federativo" sem citar a base legal do Sine nem explicar o financiamento. |
| 10. CODEFAT tripartite | **Sim, sem fonte** | Correção feita citando "[F10]", ou seja, a própria auditoria, e não a Lei nº 7.998/1990, que define a composição do conselho. |
| 11. Identidade gov.br | **Sim, sem fonte** | MGI incluído citando "[F11]". Falta uma fonte primária sobre a governança do Login gov.br. |
| 12. Inferências sobre o TCU | **Sim, com excesso de correção** | As atribuições literais sem página foram retiradas, como pedido. Mas a v2 também removeu **achados substantivos do TCU** que tinham fonte, como a capacidade insuficiente do 158 e a peregrinação entre canais (ver N1). A auditoria pedia citação exata, e não exclusão. |
| 13. Ouvidoria | **Sim** | Total anual retirado e viés de canal digital explicitado. Correto. |
| 14. Graus de certeza | **Sim** | Graus revistos, com a convenção explicitada. Mas o inventário perdeu as colunas analíticas (ver N1). |

---

## Parte B — Falhas novas introduzidas pela v2

### N1 — Regressão de conteúdo: atores e evidências válidas foram removidos sem justificativa

**Tipo:** atores omitidos e lacuna de evidência (nova).

A v2 não tratou como falha, nem justificou a retirada, de vários elementos da v1 que **não foram contestados** na primeira auditoria e que tinham fonte. Uma busca no texto da v2 confirma que eles desapareceram:
- **Atores:** **Receita Federal** (a v1 documentava que divergências de CPF exigem correção na origem antes do reprocessamento); **CGU**; **Judiciário, Ministério Público e Defensorias**; **pessoas com deficiência e o atendimento em Libras** da CAIXA; **familiares e pessoas de apoio**.
- **Evidências do TCU:** 7,4 milhões de requerimentos gerados no Empregador Web em 2024; 31,6% de recursos posteriormente deferidos; os percentuais de discordância de trabalhadores (21,9%), atendentes do Sine (48,7%) e empregadores (38,9%); a constatação de parcela informada como "paga" pela CAIXA sem efetivação do crédito; e a capacidade insuficiente do 158.
- **Estrutura analítica:** as **fichas por ator**, com interesses, ganhos e perdas, resistências possíveis, poder e dependência e visibilidade para o cidadão. O prompt de pesquisa exigia essas fichas, e elas eram o material mais útil para a entrevista. A v2 também removeu a **Tabela B (relações)** e a **Tabela C (problemas e demandas de falha)**.

O caso da parcela "paga" sem crédito é particularmente grave de perder: é a evidência mais direta de demanda de falha que chega à CAIXA.

**Justificativa:** uma revisão deve abordar as falhas apontadas, e não reduzir o escopo. A v2 se apresenta como "dossiê revisado", mas na prática é um documento de correções que depende da v1 para ser compreendido.

### N2 — Circularidade: a auditoria passou a ser usada como fonte

**Tipo:** fonte fraca ou ausente (nova).

**Trechos:** "[F1, F2]", "[F5]", "[F10]", "[F11]" usados como referências; "conforme fonte indicada na auditoria"; "A auditoria relata que chamadas de celular ao 158 podem ser tarifadas"; "Segundo os dados da PNAD TIC 2025 indicados na auditoria".

**Justificativa:** a auditoria é uma crítica, e não evidência. Ao citar as falhas como fonte, a v2 transfere ao auditor a responsabilidade pela verificação e cria uma prova circular: a afirmação se sustenta porque o auditor a fez. Cada dado incorporado a partir da auditoria precisava ser conferido diretamente na fonte primária e citado por ela. Isso vale para o contrato, a lei, a página do IBGE e a medida provisória.

### N3 — Fontes primárias da v1 eliminadas da base de evidências

**Tipo:** lacuna de evidência (nova).

A base de evidências da v2 (E1 a E12) não inclui mais: a página de Perguntas Frequentes da CAIXA sobre o Seguro-Desemprego (a fonte que sustentava o uso do 0800 para consultar parcelas e o encaminhamento ao MTE nas questões de concessão); a página de Telefones da CAIXA; a Lei nº 7.998/1990; a Resolução CODEFAT nº 957/2022 (que segue válida para as regras normativas); a Carta de Serviços (Solicitar o Seguro-Desemprego); a página oficial da Central Alô Trabalho 158; e o texto integral do Acórdão 1.621/2026.

Consequência: a frase "existe canal telefônico/eletrônico CAIXA Cidadão (0800 726 0207) para informações de benefícios e parcelas", na Etapa C, **ficou sem nenhuma fonte na v2**, embora seja a premissa central do objeto.

### N4 — Afirmação nova sem fonte: "bolsa de qualificação profissional" no Contrato 07/2026

**Tipo:** lacuna de evidência (nova).

**Trecho:** "o Contrato 07/2026 abrange Seguro-Desemprego formal (incluída bolsa de qualificação profissional), pescador artesanal, empregado doméstico e trabalhador resgatado".

**Justificativa:** a inclusão da bolsa de qualificação é informação nova, sem cláusula ou página citada, e apoiada em "[F5]". Só que a primeira auditoria não afirmou isso. É preciso citar a cláusula do objeto do contrato.

### N5 — Pendências declaradas que eram verificáveis

**Tipo:** inferência mal-suportada e lacuna de evidência.

A v2 classifica como "pendente" (c) informações que estão em fontes públicas acessíveis:
- **Vigência do Contrato 07/2026:** a v2 diz que escrever "2026–2031" exige conferência. O registro no Portal Nacional de Contratações Públicas, refletido no próprio documento, informa vigência de **16/04/2026 a 16/04/2031**.
- **TED de Contact Center (E10):** está publicado no portal do MTE um Termo de Execução Descentralizada (documento SEI 9440380, de agosto de 2026) cujo objeto é a prestação de serviços de Contact Center para atendimento a trabalhadores e empregadores, com teleatendimento receptivo, ativo e multimeios. A v2 deveria conferir se esse é o TED nº 9/2026, qual é a unidade parceira (INSS ou outra), os valores e a vigência, em vez de declará-lo pendente.
- **Contrato 11/2021:** está no mesmo portal de contratos do MTE. A v2 poderia verificar se ele tinha item de URA, o que resolveria parte do resíduo da Falha 1.

Marcar como pendente (c) o que pode ser verificado é um tratamento fraco: a opção (c) serve para o que não se consegue resolver com a evidência disponível.

### N6 — O dossiê para a entrevista foi substituído por uma agenda de pesquisa documental

**Tipo:** lacuna em relação ao objetivo da pesquisa.

A v1 terminava com o "Dossiê de contexto para entrevista de construção do mapa de atores", com perguntas sobre **fronteiras e representação do mapa**. Por exemplo: a Dataprev deve aparecer como fornecedora ou coprodutora? Sistemas devem ser atores separados de suas organizações? A Receita Federal entra no mapa principal ou só nos fluxos de exceção? A Seção 8 da v2 troca essas perguntas por **perguntas de coleta documental** (custeio da URA, glosas, scripts). Essas são úteis para pesquisa, mas não para a decisão de modelagem que a estudante tomará na entrevista. O prompt original pedia expressamente esse dossiê autossuficiente.

### N7 — Contradição interna sobre o INSS

**Tipo:** inferência mal-suportada (nova).

**Trechos:** no inventário, "INSS — instituição | Cooperação no Contact Center MTE–INSS [...] | **Média** conforme TED citado"; na base de evidências, "E10 — TED MTE–INSS nº 9/2026: **documento específico pendente de validação**".

**Justificativa:** a v2 não pode atribuir certeza média a uma relação cuja única evidência ela mesma declara não validada. Ou o TED é conferido (ver N5) e a certeza é justificada, ou a relação MTE–INSS no 158 deve ser classificada como hipótese. A participação do INSS no legado do seguro-defeso tem fonte própria e deve ser classificada separadamente.

### N8 — Precisão aparente nas estimativas do 158

**Tipo:** inferência (menor).

**Trecho:** "as estimativas são **397.190** e **828.919** atendimentos".

**Justificativa:** a v2 reconhece que os percentuais são arredondados, mas apresenta as estimativas com precisão de unidade. Com percentuais inteiros, o erro possível é de cerca de ±8,6 mil atendimentos (0,5 ponto percentual de 1.726.914). O correto é apresentar "cerca de 397 mil" e "cerca de 829 mil".

---

## Parte C — Pontos em aberto e o que a v3 precisa entregar

1. **Restaurar o conteúdo removido (N1):** reintegrar Receita Federal, CGU, Judiciário, MP e Defensorias, pessoas com deficiência e Libras, e familiares. Reintegrar os achados quantitativos do TCU e a inconsistência "paga" × crédito, com página do acórdão. Restaurar as fichas analíticas e as Tabelas B e C, já com as correções da v2.
2. **Eliminar a circularidade (N2):** substituir toda referência "[F#]" e "conforme a auditoria" pela fonte primária conferida.
3. **Repor as fontes primárias (N3)**, em especial a página da CAIXA que sustenta o papel do 0800 726 0207.
4. **Citar a cláusula da bolsa de qualificação (N4)** ou retirar a afirmação.
5. **Resolver as pendências verificáveis (N5):** a vigência do 07/2026, a identificação do TED de Contact Center e o item de URA no 11/2021.
6. **Restaurar o dossiê para a entrevista (N6)**, com perguntas sobre fronteiras do mapa, granularidade, sistemas × organizações e tipos de relação (dados, dinheiro, autoridade, orientação, encaminhamento).
7. **Resolver a contradição do INSS (N7)** e arredondar as estimativas (N8).
8. **Manter abertos, como pendências legítimas:** a árvore de menus e os scripts da URA, o custeio da URA no Seguro-Desemprego, as subcontratações efetivas, as métricas por canal e o volume por modalidade.

Para que a evolução seja verificável, a v3 deve incluir uma tabela final **"Gatilho da audit_v2 → mudança na v3"**, listando N1 a N8 e os resíduos da Parte A.

## Fontes consultadas nesta auditoria

- Contrato MTE nº 07/2026 com a CAIXA, incluindo o registro de vigência de 16/04/2026 a 16/04/2031: https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/licitacoes-e-contratos/pca/072026completo.pdf
- Termo de Execução Descentralizada de Contact Center do MTE (SEI 9440380): https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/convenios-e-transferencias/termos-de-execucao-descentralizada/ted7aa.pdf/@@download/file
- IBGE — PNAD Contínua TIC 2025, informativo oficial (fonte primária para a rede móvel urbana/rural, em substituição à URL em inglês com o ano inconsistente apontada pela v2): https://biblioteca.ibge.gov.br/visualizacao/livros/liv102290_informativo.pdf
- Texto da v1 (`B_relatorio_assistente_v1.md`), para comparar o que foi removido.
