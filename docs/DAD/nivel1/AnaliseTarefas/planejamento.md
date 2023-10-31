# Planejamento da Avaliação da Análise de Tarefas

## Introdução

Durante a etapa da Análise de requisitos, foi realizada a Análise de tarefas com o objetivo de obter mais informações sobre as tarefas realizadas pelos usuários do site do ventoy, levando em consideração o Perfil do usuário obtido. Para uma análise mais detalhada, é necessário avaliar a qualidade de uso da solução de IHC e identificar problemas na interação e na interface que prejudiquem a experiência do usuário. Para isso, será feita uma avaliação da Análise de tarefas, utilizando o método de investigação de entrevistas com usuários reais do produto, baseadas no perfil de usuário. Assim, será possível avaliar sua perspectiva de forma dinâmica e fazer um julgamento de valor sobre a solução de IHC proposta. A avaliação de IHC é um processo essencial para que o desenvolvimento consiga produzir um sistema interativo com alta qualidade, conforme afirmam Simone Barbosa e Bruno Diniz^1^.

## Metodologia

As atividades que serão avaliadas na análise foram obtidas com os métodos de 
[análise hierárquica de  tarefas](../../../AnaliseDeRequisitos/analisedetarefas/analiseHierarquicaDeTarefas.md)
(HTA) e [concur task tree](../../../AnaliseDeRequisitos/analisedetarefas/ConcurTaskTrees.md) (CTT).
A estrutura deste planejamento foi construída utilizando o *framework* DECIDE, que pode ser descrito como na tabela 1 abaixo.

<p align="center"><b>Tabela 01</b> - Framework DECIDE </p>

<center>

| Letra |                          Definição                           |
| :---: | :----------------------------------------------------------: |
|   D   |            Determinar os objetivos da avaliação.             |
|   E   |   Explorar perguntas a serem respondidas com a avaliação.    |
|   C   |     Escolher os métodos de avaliação a serem utilizados.     |
|   I   | Identificar e administrar as questões práticas da avaliação. |
|   D   |          Decidir como lidar com as questões éticas.          |
|   E   |          Avaliar, interpretar e apresentar os dados          |

**Fonte**:  BARBOSA e SILVA (2011).

</center>

## Objetivos (D)

O objetivo da avaliação é investigar a qualidade das tarefas obtidas através dos métodos HTA e CTT.
Os aspectos das tarefas que serão avaliados são:

- Ideias e alternativas de design.
- Conformidade com padrão.
- Problemas na interação e na interface.

## Perguntas (E)

Neste tópico é listado um conjunto de perguntas que deverão ser respondidas com a análise de tarefas
de acordo com cada aspecto citado anteriormente.

**Ideias e alternativas de design.**

- Quais soluções de IHC já consolidadas possuem mecanismos de documentação, fórum e/ou FAQ?
- Qual das alternativas é mais eficientes?
- Quais características dessas soluções podem ser incorporadas ao site Ventoy?

**Conformidade com um padrão**

- As páginas de fórum, documentação e FAQ estão em conformidade com os padrões comumente utilizados
nesses domínios?

**Problemas na interação e na interface**

- O usuário entende o que significa e para que serve cada elemento de interface?
- O usuário atige seu objetivo? Com quanta eficiência? Em quanto tempo?
- Que problemas de IHC dificultam ou impedem o usuário de alcançar seus objetivos?
- Quais barreiras o usuário encontra para atingir seus objetivos?

## Métodos de Avaliação (C)

Será utilizado o método de avaliação heurística para avaliar os aspectos de alternativas de design,
conformidade com padrão e problemas de IHC.

Neste método o avaliador irá inspecionar de maneira sistemática a interface utilizando para tal,
um conjunto de diretrizes, também chamadas de heurísticas.

As heurísticas que serão avaliadas na análise serão:

- Visibilidade do estado do sistema.
- Correspondência entre o sistema e o mundo real.
- Consistência e padronização.
- Projeto estético e minimalista.

Para avaliar alternativas de design e problemas de IHC será utilizado prototipação em papel.

Para esse método é criado um protótipo de baixa fidelidade em papel, e então um usuário é
convocado para simular uma interação com o protótipo. Durante esssa interação o avaliador atuará
como um "computador" que simula as execuções feitas pelo usuário.

O objetivo principal desse método é encontrar alternativas de design, e avaliar soluções
parciais da interface.

Grupos de foco são uma técnica qualitativa de pesquisa em que um moderador facilita
uma discussão em grupo com participantes selecionados, com o objetivo de explorar suas
opiniões, atitudes, percepções e experiências sobre um tópico específico.

Serão utilizados para avaliar alternativas de design e problemas
de IHC.

## Questões Práticas (I)

### Recrutamento

Deve ser feito o recrutamento de pessoas para a realização do método de avaliação por protopitação
em papel e para o grupo de foco. As pessoas recrutadas devem está de acordo com as 
[personas](../../../elicitacao/Persona.md) e com o [perfil de usuário](../../../elicitacao/PerfilUsuario.md).

Para o grupo de foco deve ser recrutados ao menos 3 pessoas.

O usuário recrutado deve concordar com o termo de consentimento.

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


### Prazo

Responsável| Descrição | Local |  Horário                               |Data    |
 ---        | ---       | ---  |              --  |  ---            |
Limírio | Avaliação em protótipo de papel       | Discord| 20:00        |02/11/2023 |
Breno   | Avaliação em protótipo de papel       | FGA | 12:30           |07/11/2023 |
Mayara   | Avaliação em protótipo de papel      | FGA | 12:30           |06/11/2023 |
Altino   | Avaliação em protótipo de papel      | FGA | 12:30           |04/11/2023 |
Vinícius    | Avaliação em protótipo de papel   | FGA | 12:30           |03/11/2023 |
Milena   | Avaliação em protótipo de papel      | FGA | 12:30           |07/11/2023 |
Luis   | Avaliação em protótipo de papel        | FGA | 12:30           |07/11/2023 |

## Aspectos Éticos (D)

A pesquisa científica envolvendo seres humanos demanda um respeito fundamental pela
dignidade e autonomia dos participantes, juntamente com a consideração de sua vulnerabilidade
e liberdade de consentimento. No Brasil, a resolução nº 466/2012 do Conselho Nacional
de Saúde^2^ estabelece diretrizes éticas que incluem princípios como a autonomia, beneficência
, não maleficência e justiça. Esses princípios são aplicáveis a qualquer tipo de pesquisa
, visando assegurar o respeito aos direitos dos participantes, a maximização dos benefícios
e a prevenção de danos, bem como a equidade na distribuição de benefícios. Respeitar
esses princípios não apenas protege os participantes, mas também fortalece a integridade
da pesquisa e a confiança do público na ciência e na comunidade acadêmica.

Neste projeto, utilizaremos essas diretrizes e princípios éticos como alicerces fundamentais
para conduzir a pesquisa de forma responsável e respeitosa em relação aos participantes
. Essas diretrizes nos guiarão na obtenção de consentimento informado através do 
[termo de consertimento](../../../../analisedetarefas/aspectosEticos). O cumprimento rigoroso desses 
princípios garantirá a integridade do nosso trabalho e reforçará a confiabilidade da pesquisa, promovendo,
assim, a confiança do público na ciência e na comunidade acadêmica.

## Avaliar, Interpretar e Apresentar os Dados (E)

Após a conclusão da avaliação, os dados serão cuidadosamente documentados e processados, levando em consideração o contexto em que foram gerados, a fim de determinar sua confiabilidade e a possibilidade de aplicação geral para representar a totalidade dos usuários do site do Ventoy.

Este processo de documentação abrangerá a identificação e registro de problemas e desafios
encontrados durante a interação, abordando questões relacionadas à usabilidade, funcionalidades
ausentes e problemas de desempenho. Faremos anotações detalhadas das descrições dos
problemas, e sua classificação. Após a coleta destas anotações, os resultados serão
analisados para identificar padrões e tendências nas respostas dos participantes. A
análise dos dados fornecerá insights sobre os problemas de usabilidade do site do Ventoy
e nos fornecerá uma melhor visão para as sugestões de melhoria.

## Planejamento do teste piloto

O objetivo do teste piloto é avaliar o próprio planejamento, e analisar se a avaliação
, tal como planejada, produz os dados necessários para responder a questões e objetivos
do estudo. O avaliador deve conduzir o teste-piloto como se fosse uma sessão normal
de avaliação. Dessa forma, ele tem oportunidade de verificar se a linguagem nas explicações
e nos materiais fornecidos é clara e objetiva, e se esses materiais contêm informações
adequadas e suficientes para orientar o participante durante a avaliação.

Neste projeto, a realização do teste-piloto será executada de forma a simular entrevistas
com os usuários reais do Ventoy, com o objetivo de identificar quaisquer lacunas ou
aprimoramentos necessários no processo. Na tabela 2 temos o cronograma para realização
do teste-piloto.

<p align="center"><b>Tabela 02</b> - Cronograma Teste Piloto </p>
<center>

| **Entrevistador** | **Entrevistado** | **Horário de início** | **Horário de término** | **Data** |  **Plataforma** |
|:---------------:|:------------:|:---------:|:------------------:|:----------------:|:----------------:|
| [Mayara Alves](https://github.com/Mayara-tech)  | [Breno Queiroz](https://github.com/brenob6) | 21h30min | 21h45min | 30/10/2023  | Teams |  

**Fonte**: [Mayara Alves](https://github.com/Mayara-tech).

</center>

## Resultado do teste piloto 

O teste piloto foi realizado no dia 30/10/2023 às 21:47 e teve a duração de 7 minutos, onde tivemos [Mayara Alves](https://github.com/Mayara-tech) como entrevistadora e [Breno Queiroz](https://github.com/brenob6) como entrevistado, com intuito de testar todas as questões propostas nesta avaliação, de modo a avaliar se somente essas questões seriam suficientes para válida para determinar se as análises de tarefas estão de acordo com as tarefas executadas pelo usuário. No video 1 podemos observar o teste piloto realizado. 

<p style="text-align: center"><a href="https://www.youtube.com/watch?v=etJTsYTvYU&feature=youtu.be" target="blanket">Vídeo - teste piloto </a></p>

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/eUFJTstvYU?si=0nzUGyppLLr7AR0y" title="Apresentação 02/10/2023" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<font size="3"><p style="text-align: center">Fonte: [Mayara Alves](https://github.com/Mayara-tech).</p></font>

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.
> <a id="REF2" href="#anchor_1">2.</a> CONSELHO NACIONAL DE SAÚDE. Resolução nº 466, de 12 de dezembro de 2012. Brasília, DF: Diário Oficial da União, 2013. Disponível em: <https://conselho.saude.gov.br/resolucoes/2012/Reso466.pdf>. Acesso em: 30/10/2023.


## Bibliografia
> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.<br/>
> ALVES, Douglas *et al.* **Bilheteria Digital** Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital>. Acesso em: 29 de outubro 2023.


## 📑 Histórico de versões:

 Versão  |    Data    |        Descrição|Autor(es)|      Revisor(es)                   
 :-----: | :--------: | :-------------: | :-------------------: | :------: 
  `1.0`  | 29/10/2023 |Criação do Perfil de Usuário| [Mayara Alves](https://github.com/Mayara-tech), [Limírio Guimarães](https://github.com/LimirioGuimaraes)  e [Breno Queiroz](https://github.com/brenob6) | [](https://github.com/)  [](https://github.com/)  
  
