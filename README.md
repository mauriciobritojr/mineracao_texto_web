# mineracao_texto_web
Repositório Criado para as Atividades da Disciplina Mineração de Texto e Web
Projeto 01 - Análise de Linguagem Ofensiva no Twitter
Este trabalho é baseado na tarefa Ofensivo que ocorre no âmbito das competições anuais da Semântica Computacional - SEMEVAL, edições de 2019 e 2020.

Seguem links para consulta:

SemEval 2019

OfensasEval 2019
A linguagem ofensiva é massivamente difundida nas mídias sociais. Os indivíduos selecionados podem usar anonimato nas comunicações mediadas por computador, para envolver em aplicações, os que não consideram a vida real. Comunidades on-line, plataformas de mídia social e empresas de tecnologia têm investido fortemente em maneiras de lidar com a linguagem ofensiva para evitar o abuso de mídias sociais.

Uma das estratégias mais usadas para resolver esse problema é usar os métodos computacionais para identificar ofensas, agressões e discursos de ódio no conteúdo gerado pelo usuário (por exemplo, postagens, comentários, microblogs etc.). Em Processamento de Linguagem Natural (PLN), considere uma aplicação de classificação textual ( Classificação de Texto )

Objetivos
Neste projeto, são propostas duas abordagens para analisar discursos ofensivos em tweets:

(A) Subtarefa A - Identificação de Linguagem Ofensiva

(NÃO) Não ofensivo - o tweet ou texto NÃO contempla ofensa ou profanidade.
(OFF) Ofensiva - o tweet ou o texto contem qualquer tipo de linguagem não aceitável (ofensa ou profanidade) ou uma ofensa direcionada (velada ou direta).
(B) Subtarefa B: Categorização dos tipos de ofensa

(TIN) Insulto e ameaças direcionadas - o tweet contem um insulto ou ameaça a um indivíduo, um grupo ou outros.
(UNT) Não segmentado - o tweet contem insultos, palavrões ou ofensas não direcionadas.
Conjuntos de dados
Dados de treinamento (arquivo de texto simples "olid-training-v1.0.tsv")

Um conjunto com 13.240 tweets anotados com os seguintes dados:

eu tweet
texto do tweet
label para subtarefa A
label para subtarefa B
label para subtarefa C (desconsiderar)
Exemplo:

Eu iria	twittar	subtarefa A	subtarefa B	subtarefa C
90194	@USER @USER Vá para casa, você está bêbado !!! @USER #MAGA # Trump2020 👊🇺🇸👊 URL	FORA	LATA	IND
16820	A Amazon está investigando funcionários chineses que estão vendendo dados internos a vendedores de terceiros, buscando uma vantagem no mercado competitivo. URL # Amazônia #MAGA #KAG #CHINA #TCOT	NÃO	NULO	NULO
Entregas
ATIVIDADE 01 - Pré-processamento dos textos (Prazo: 11/05/2020 - 30%)

Tokenização
Lematização
Identificação de POS
Normalização (hashtags, menções, emojis e símbolos especiais)
NER (entidades nomeadas)
Palavras-chave de remoção
ATIVIDADE 02 - Representação Semântica (Prazo: 22/06/2020 - 30%)

Uso de bases de conhecimento externas
Identificação de tópicos
Representação vetorial das palavras e textos
ATIVIDADE 03 - Análise da Linguagem Ofensiva - Subtarefas A e B (Data: 27/07/2020 - 40%)

Resultado da subtarefa Um conjunto de teste a ser fornecido
Resultado da subtarefa B para um conjunto de teste a ser fornecido
