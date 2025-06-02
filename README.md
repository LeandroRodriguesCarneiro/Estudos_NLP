# 📚 Estudos em Processamento de Linguagem Natural (NLP)

Este repositório reúne estudos práticos em Processamento de Linguagem Natural (NLP), explorando bibliotecas populares como **NLTK**, **spaCy** e **Word2Vec**. O objetivo é consolidar conhecimentos teóricos por meio de implementações práticas em Python. 

### Algumas definições
- Processamento de Linguagem Natural (Natural Language Processing): O computados tem dificuldade em processar dados não estruturados, printipalmento no que se refere a texto e linguagem, com o surjimento da demanda e foram criando formas de fazer o computador processar textos e com o surgimento do machine learning e as redes neurais artificiais trouxe mais possibilidades
- Corpus: Conjunto de documentos(Textos não estruturado) em linguagem natural

- Annotations: Localizar e classificar elementos especificos no texto.
   * Exemplos:
      * Anotar sentimentos para treinamento de IA
  * Podendo ser especifica por dominio ex. Medicina;
  * Existem empresas especificas especializadas em anotar
  * Existem ferramentas expecializadas como: Doccano, Brat etc.
  * Alguns tipos podem ser feitas por maquinas

- Tokenização: Processo de subdivisão das sentenças em partes: palavras, pontos e símbulos etc.

- Parts-of-speech (POS) tagging: Adiciona tags a cada tokem por exemplo sé é verbo, substantivo, adjetivo etc.

- Lemmatizing (lemma): Trazer a palavra na sua flexão, de modo que possam ser analizadas juntas.

- stemming:
  * Corta palavras, buscando ter uma representação raiz unica
  * Diferentes tecnicas
  * Lemmatization é mais sofisticado
  * Amigo, amigos, amiga, amigas => amig

- Dependency parsing: Busca encontrar relação entre palvras

- Ngram:
  * N palavras sonsecutivas
  * Bigrams e trigrams
  * 4 ou mais não é utilizado devido a esparsidade
  * pode ser aplicado em letras

- Modelo:
  Um modelo de banco de dados linguistico 
  * Analize:
     * Verbo, substantivo, quais são as flexôes? Quais são as dependencias
  * Especifico para cada idioma
  * Maioria das bibliotecas de NLP tem seus próprios modelos (ou usam modelos de terceiros)
  * Pode criar seu

- Word Embedding: É representações computacionais de texto:
  * independente de contexto
  * dependente de contexto

- One-hot encode: É uma representação matricial de uma fraze em uma matriz formada por zeros e uns

- TF-IDF: É feita pela frequencia das palavras utilizadas na frase palavras mais frequentes tendem a se aproximar de 0 e palavras menos frequentes tendem a ter valor mais alto

- word2vec: Atravez de um processo de treinamento, produz um vetor demonstrando matematicamente a relação entre palavras existem duas formas principais:
  * CBOW: busca prever uma palavra baseadono contexto
  * Skip-gram: busca prever o contexto a partir de uma palavra central

### O que encontrará nesse projeto:
- nltk/: Explorações com a biblioteca NLTK, incluindo tokenização, stemming, lematização e análise de sentimentos.
- spacy/: Aplicações com spaCy, abordando reconhecimento de entidades nomeadas (NER), dependências sintáticas e vetores de palavras.
- word2vec/: Implementações de modelos Word2Vec para representação vetorial de palavras juntamente com um classificador de NER desenvolvido por mim.
- classificador_span/: Desenvolvimento de um classificador de sentimentos utilizando spaCy e dados em espanhol.
