# Entrevista

## Introdução
A técnica de entrevista é fundamental na coleta de dados e no processo de elicitação de requisitos. Esta metodologia consiste em uma discussão estruturada, onde o entrevistador utiliza um conjunto de perguntas pré-definidas para extrair informações valiosas de um entrevistado, como identificado por Seidman em 1998. A interação direta nas entrevistas fornece insights profundos sobre as necessidades e expectativas dos usuários em relação ao sistema proposto.

## Metodologia
Realizamos uma entrevista semiestruturada no dia 15 de outubro de 2023 com Wycthor da Silva do Nascimento, um usuário do software Ventoy. A entrevistadora, Mayara Alves de Oliveira, iniciou com a apresentação do Termo de Consentimento, seguida de uma explanação sobre os objetivos do projeto. Utilizando o Microsoft Teams como plataforma, a entrevista seguiu um roteiro meticulosamente preparado de perguntas abertas, permitindo a coleta de dados ricos em um formato flexível e responsivo.

A entrevista foi estruturada em várias fases para maximizar o conforto do entrevistado e a eficácia da sessão:

- **Apresentação**: O entrevistador se apresenta e delineia os objetivos da entrevista.
- **Período de aquecimento**: Perguntas iniciais são feitas para coletar informações demográficas e estabelecer um perfil do usuário.
- **Parte principal**: As questões centrais do roteiro são abordadas, explorando profundamente as necessidades do usuário em relação ao sistema.
- **Período de desaquecimento**: Uma sequência de perguntas mais leves é utilizada para aliviar qualquer tensão remanescente.
- **Conclusão**: A entrevista é encerrada com agradecimentos ao participante, e a gravação é finalizada.

Este método permite um diálogo orgânico, ao mesmo tempo que fornece estrutura suficiente para garantir que todos os tópicos essenciais sejam cobertos.

## Entrevista

<p style="text-align: center"><a href="https://www.youtube.com/watch?v=e7p8hn9R-GQ" target="blanket">Vídeo da Entrevista</a></p>

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/o-aAB8D8C3s?si=efG7a5xVPrjy62PJ&amp;start=2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>


## Roteiro 
Na Tabela 1, é possível contemplar o roteiro empregado para a condução da entrevista.

<p align="center"><b>Tabela 1.</b> Roteiro da entrevista  </p>

  
Página  | Pergunta 
:---------: | :------
Página principal | 1.  Como você avalia o design da página principal? <br> 2.  O que você acha da barra de navegação do site? <br> 3.  A barra de navegação possui termos claros? <br> 4.  Você se incomoda com a disposição de anúncios do site?
Página de documentação | 5. Você utiliza a página de documentação do Ventoy quando faz uso da ferramenta? <br> 6. É fácil encontrar tópicos na documentação? Ou seja, você encontra com facilidade o procura na página de documentação? <br> 7. Como você compara a página de documentação do Ventoy com de outras plataformas? 
Página FAQ | 8. Como você avalia a disposição das perguntas no FAQ? <br> 9. Os simbolos que colapsam as perguntas, são facilmente descritíveis?
Fórum | 10. Você consegue identificar rapidamente os temas que são tratados em cada fórum? <br> 11. Os ícones mostrados na página de post de um fórum elas são descritíveis? você sabe o que elas significam? <br>
Página de TestedISO | 12. Você consegue acha rapidamente se uma distribução que você visa instalar foi testada no Ventoy?
Sobre todo site | 13. Quais são as funcionalidades que acha que são importantes, que foram ou que devem ser implementadas no Ventoy para melhora a usabilidade do mesmo?


## Requisitos Elicitados 
Após a realização da entrevista com o usuário do Ventoy, foi possível eliciar os requisitos apresentados na Tabela 2. Onde cada requisito é classificado por um sigla formada por "ENT" + um número, em que "ENT" é um sigla de entrevista, e para representar o tipo do requisito, será usado as siglas "RF" ou "RNF", que representam o tipo do requisito funcional ou não funcional, além disso também será representado se já há uma implementação do requisito no aplicativo.

<p align="center"><b>Tabela 2</b> - Requisitos elicitados na Entrevista.</p>


| **Identificador** | **Requisitos** | **Tipo** | **Implementado** |
|--------------|-------------|-----|-----------------|
|ENT01| Deve ser possível alterar o idioma para português | RF | Não implementado|
|ENT02| Deve ser possível colocar no tema escuro| RF | Não implementado |
|ENT03| O site deve ser responsivo | RNF | Não implementado |
|ENT04| Deve ser possível alterar o tamanho da fonte do site | RF | Não implementado |
|ENT05| O site deve padronizar o local dos anúncios ( Não deixando anúncios no meio do site)| RF | Não implementado |
|ENT06| O site deve possuir uma organização padronizada da documentação | RF | Não implementado |
|ENT07| A interface deve ser padronizada e responsiva para todas as páginas dentro do site | RNF | Não implementado |
|ENT08| O site deve incorporar uma paleta de cores acessível a indivíduos daltônicos. | RF | Não implementado |
|ENT09| O site deve ter um tempo de resposta inferior a 1.0s | RNF | Não implementado |
|ENT10| O site deve possuir um FAQ de perguntas | RF | Implementado |

<p align="center"><b>Fonte</b>: <a href="https://github.com/Mayara-tech">Mayara Alves.</a></p>


## Referência Bibliográfica
>SEIDMAN, I. Interviewing as Qualitative Research: a guide for researchers in Education
and the Social Sciences. New York, NY: Teachers College Press, 1998

## Bibliografia
>ELICITAÇÃO DE REQUISITOS, PUC-Rio.  Disponível em: https://www.maxwell.vrac.puc-rio.br/15760/15760_3.PDF <br>
>MEDEIROS M. E. Aula 5 - Requisitos de Software - Conceitos e Técnicas de Elicitação.  Universidade de São Paulo, 2006. Disponível em: https://edisciplinas.usp.br/pluginfile.php/7993139/mod_resource/content/1/05%20-%20Requisitos%20de%20Software%20-%20Conceitos%20e%20T%C3%A9cnicas%20de%20Elicita%C3%A7%C3%A3o.PDF <br>
> MARTINS L.E.G. Uma Metodologia de Elicitação de Requisitos de Software Baseada na Teoria da Atividade.  Unicamp, 2001. Disponível em: file://home/yaba/Downloads/Martins_LuizEduardoGalvao_D.pdf.

## 📑 Histórico de versões 

Versão  |   Data   | Descrição | Autor(es) | Revisor(es)
--------- | ------ | ------ | ---------- | ----------
`1.0` | 15/10/2023| Entrevista  | [Mayara Alves](https://github.com/Mayara-tech) e [Breno Queiroz](https://github.com/brenob6) | [Altino Arthur](https://github.com/arthurrochamoreira) e [Luis Miranda](https://github.com/LuisMiranda10) |
