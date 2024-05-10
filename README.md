# Localizador de Séries da Netflix com IA Gemini

Bem-vindo ao projeto Localizador de Séries da Netflix, alimentado pela IA Gemini!

Este projeto foi desenvolvido como parte de um programa de imersão em IA realizado pela Alura em colaboração com o Google. Utilizando técnicas de ponta em Processamento de Linguagem Natural (PLN) e aprendizado de máquina, esta aplicação permite aos usuários descobrir séries da Netflix com base em seus interesses ou tópicos específicos.

## Como Funciona

O Localizador de Séries da Netflix aproveita modelos de incorporação (embedding) de última geração, como `models/embedding-001`, para codificar informações semânticas das sinopses das séries em representações vetoriais de alta dimensão. Essas incorporações capturam a essência de cada série, permitindo comparação e recuperação eficientes com base na entrada do usuário.

Além disso, o modelo de chat Gemini, `gemini-1.0-pro`, fornece uma interface intuitiva para os usuários interagirem com o sistema. Os usuários podem inserir tópicos ou critérios, e a IA Gemini analisará os dados para recomendar as séries da Netflix mais adequadas, deixando a sinopse mais descontraída e resumida.

## Exemplos de Consultas

Aqui estão alguns exemplos de consultas que você pode experimentar:

- "Drama baseado em eventos reais"
- "Guerra"
- "Drama jurídico"
- "Séries temáticas de aviação"
- "Séries dirigidas pelo mesmo diretor de La Casa de Papel"

Em nossos testes, o Localizador de Séries da Netflix forneceu consistentemente recomendações precisas com base nessas consultas, mesmo levando em consideração preferências direcionais específicas.

Foram testados também as restrições de segurança de termos. Em algumas sinopses existem termos inadequados, o que faz com que o modelo exiba apenas o nome da série e não exiba a sinopse.

## Fonte das Sinopses

As sinopses das séries foram obtidas de [Oficina da Net](https://www.oficinadanet.com.br/netflix/23416-as-40-melhores-series-para-assistir-na-netflix-em-2018), onde foram listadas as 50 melhores séries para assistir na Netflix em 2024 (apesar do link estar descrito 40 séries para assistir em 2018).

## Como Começar

Para começar com o Localizador de Séries da Netflix, basta acessar o projeto no google colab.

## Agradecimentos

Um agradecimento especial à Alura e ao Google por fornecerem os recursos e suporte para este projeto. Também reconhecemos as contribuições da equipe de IA Gemini por suas técnicas inovadoras de chat e incorporação.
