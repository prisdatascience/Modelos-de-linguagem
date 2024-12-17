# Modelos-de-linguagem

Em Semeval.ipynb encontra-se o código que gera os templates para o método TabletoContex

Em Metricas.ipynb encontra-se o código que geram as métricas utilizadas no arquivo Método_TabletoContex.pdf

1.	Introdução

Modelos de linguagem em larga escala (Large Language Models  LLMs), como GPT, LLaMA e T5, têm revolucionado o campo do Processamento de Linguagem Natural (NLP) ao alcançar desempenhos impressionantes em tarefas variadas, como geração de texto, sumarização e perguntas e respostas (Question Answering  QA). Contudo, sua aplicação a dados estruturados, como tabelas, permanece um desafio devido à natureza compacta e sem contexto dessas informações. Diferentemente de textos narrativos, que possuem conectivos e semântica explícita, tabelas dependem de relações implícitas entre colunas e linhas para transmitir significado.
Dada essa lacuna, várias abordagens têm sido propostas para integrar dados tabulares com LLMs. Métodos tradicionais frequentemente dependem de arquiteturas especializadas para dados tabulares ou do uso direto de formatos estruturados, como CSV, que, embora eficazes em alguns cenários, podem limitar a capacidade do modelo de interpretar nuances e contextos semânticos mais ricos. Um exemplo disso é o modelo OLLAMA 3 8B, que foi projetado para processar diretamente dados tabulares em formato CSV, mas sem transformar as tabelas em texto narrativo.
Neste trabalho, propomos uma metodologia alternativa que utiliza o poder do Prompt Engineering para transformar dados tabulares em entradas textuais contextualizadas. Denominada TabletoContext, nossa abordagem gera automaticamente templates narrativos a partir da descrição das colunas e do conteúdo das tabelas. Esses templates enriquecem o contexto semântico das tabelas, utilizando conectivos e construções linguísticas que tornam os dados mais compreensíveis para LLMs, permitindo que eles processem informações tabulares como se fossem texto narrativo.
