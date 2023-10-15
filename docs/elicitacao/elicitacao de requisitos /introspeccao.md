# Introspecção
## Introdução
Quando falamos em técnicas de elicitação, de acordo com Goguen (1994), a técnica de introspecção é uma das mais utilizadas, já que depende apenas do avaliador. A introspecção é uma técnica na qual a atividade é baseada em "imaginar" como o sistema deve ser e se comportar para solucionar um determinado problema do usuário.

Como foi dito, esta técnica é realizada pelo próprio avaliador, levando em consideração um ponto de vista particular. Isso nos traz benefícios e vantagens ao utilizar esta técnica, que são:

**Vantagens**: Dá a oportunidade para o avaliador conseguir ter uma concepção de como o sistema funciona e se comporta rapidamente, especialmente quando está utilizando uma certa "encenação" de um usuário imaginário.

**Desvantagens**: O avaliador pode estar fortemente vinculado ao uso do sistema, o que pode dificultar a visão na perspectiva de algum outro tipo de usuário.

## Metodologia
Para a preparação da técnica, foi necessário elaborar mentalmente um cenário de como o sistema deve ser para um usuário que busca resolver um determinado problema.

O cenário imaginário elaborado foi: "Um usuário jovem precisa instalar o linux em seu notebook e, ao necessitar criar um pen drive bootável, ele encontra o software Ventoy. Porém, para utilizá-lo, ele precisa saber como proceder e, assim, acessa o site do Ventoy.".

## Requisitos Elicitados
Após o exercício mental de utilizar o site Ventoy para solucionar o problema de um usuário imaginário, conseguimos eliciar os requisitos apresentados na Tabela 1. Identificamos cada requisito por uma sigla formada por "ITP" + um número. Para representar o tipo do requisito, serão usadas as siglas "RF" ou "RNF", que representam o tipo do requisito funcional ou não funcional. Também indicaremos se já há uma implementação do requisito no aplicativo.

<p align="center"><b>Tabela 01</b> - Requisitos elicitados do Glossário. Fonte: Autores.</p>

| **Identificador** | **Requisitos** | **Tipo** | **Implementado** |
|--------------|-------------|-----|-----------------|
|ITP01| Deve ser possível colocar no tema escuro| RF | Não implementado |
|ITP02| Deve ser possível alterar o idioma para qualquer idioma | RF | Não implementado|
|ITP03| O site deve possuir uma demonstração de instalação na página de Downloads | RNF | Não implementado |
|ITP04| O site deve ter uma interface responsiva na mudança de dimensões da tela | RNF | Não implementado |
|ITP05| O site deve ter uma interface agradável, utilizando padrões de cores consistentes e agradáveis ao usuário | RNF | Não implementado |
|ITP06| O site deve ter uma barra lateral na documentação dividida em tópicos, mais minimalista e direcionada a um tópico| RNF | Implementado |
|ITP07| O site deve possuir uma área de respostas de perguntas frequentes | RF | Implementado |
|ITP08| O site deve garantir que o usuário acesse o que procura na documentação em 2 cliques | RNF | Implementado |
|ITP09| O site deve permitir que o usuário consiga entrar em contato com o autor dos artigos postados | RNF | Não implementado |
|ITP10| A interface deve ser padronizada e responsiva para todas as páginas dentro do site | RNF | Não implementado |

<p align="center"><b>Fonte</b>:  <a href="https://github.com/yabamiah">Vinicius Mendes.</a></p>

## Referências
- Elicitação de Requisitos, PUC-Rio. Disponível em: [link](https://www.maxwell.vrac.puc-rio.br/15760/15760_3.PDF).
- Marcelo Medeiros Eler. Aula 5 - Requisitos de Software - Conceitos e Técnicas de Elicitação. Universidade de São Paulo, 2006. Disponível em: [link](https://edisciplinas.usp.br/pluginfile.php/7993139/mod_resource/content/1/05%20-%20Requisitos%20de%20Software%20-%20Conceitos%20e%20T%C3%A9cnicas%20de%20Elicita%C3%A7%C3%A3o.PDF).
- Luiz Eduardo Galvão Martins. Uma Metodologia de Elicitação de Requisitos de Software Baseada na Teoria da Atividade. Unicamp, 2001.

## 📑 Histórico de Versões
| **Versão**   |   **Data**   | **Descrição** | **Autor** | **Revisor** |
|--------|---------|-----------|--------|---------|
|`1.0`| 14/10/2023 | Criação da página de introspecção | [Vinícius Mendes](https://github.com/yabamiah)| [Luís Miranda](https://github.com/LuisMiranda10) e [Altino Arthur](https://github.com/arthurrochamoreira) |
