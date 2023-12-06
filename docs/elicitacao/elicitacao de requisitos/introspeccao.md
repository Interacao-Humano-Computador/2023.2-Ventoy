# Introspecção

## Introdução

A introspecção é uma técnica de elicitação de requisitos que se destaca por sua independência, conforme identificado por Goguen em 1994. Essencialmente introspectiva, essa abordagem envolve o avaliador imergindo profundamente em sua própria compreensão do sistema para prever como ele pode atender às necessidades dos usuários. O avaliador "encarna" um usuário e imagina as funcionalidades necessárias para cumprir tarefas específicas.

Essa técnica oferece vantagens significativas, permitindo que o avaliador visualize rapidamente o sistema em ação. No entanto, a introspecção também tem limitações, principalmente quando o avaliador não consegue se desvincular de suas próprias experiências com o sistema, o que pode obscurecer as necessidades de usuários distintos.

**Vantagens**: Facilita uma rápida compreensão do sistema através de uma simulação mental efetiva, empregando a "encenação" de cenários de uso por um usuário fictício.

**Desvantagens**: Pode haver uma tendência a se concentrar em perspectivas familiares, limitando a exploração de necessidades de diferentes perfis de usuários.

## Metodologia

Na preparação para a técnica de introspecção, delineamos um cenário detalhado, onde o membro Vinícius, em conjunto com as personas criadas, irá encenar uma persona e realizar a técnica de introspecção com mais nível de profundidade. Lembrando que está técnica foi utilizada pela falta de tempo e de usuários disponíveis para realizar outras técnicas de elicitação. 

Imaginamos um usuário adulto, que se chama Steve Vobes que, diante da necessidade de instalar o Linux em notebooks para vários estudantes de uma escola, recorre ao software Ventoy para criar um pen drive bootável. Para operacionalizar o software, ele busca instruções no site do Ventoy, o que nos levou a considerar a experiência do usuário do início ao fim.

Para a realização desta técnica, iremos seguir o cronograma planejado da Tabela 1 logo abaixo:

**Tabela 1** - Cronograma Planejado

| Participantes | Personagens Encenados | Data | Horário |
|---------------|-----------------------|------|---------|
| Vinícius Mendes| Steve Joves | 14/10/2023 | 15:00/15:15 |

**Fonte**: [Vinícius Mendes](https://github.com/yabamiah)

## Requisitos Elicitados

De acordo com o cronograma planejado, foi organizado um tempo para ser realizado o processo introspectivo revelou vários requisitos, que foram catalogados na Tabela 3. E logo abaixo estará o cronograma realizado:

**Tabela 2** - Cronograma Realizado

| Participantes | Personagens Encenados | Data | Horário |
|---------------|-----------------------|------|---------|
| Vinícius Mendes| Steve Joves | 14/10/2023 | 15:40/15:57 |

**Fonte**: [Vinícius Mendes](https://github.com/yabamiah)

Como dito anteriormente, utilizando essa técnica foi possível eliticar vários requisitos com facilidade e em menos tempo utilizando uma persona, porém é importante lembrar que sempre que for possível, é melhor utilizar usuários reais para as técnicas de elicitação. Os requisitos catalogados na Tabela 2 foram codificados iniciando com "ITP", seguidos de um número sequencial. "RF" indica um Requisito Funcional, enquanto "RNF" denota um Requisito Não Funcional. A tabela também especifica se o requisito já está presente na versão atual do aplicativo.

**Tabela 3** - Requisitos elicitados da Introspecção

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

**Fonte**: [Vinícius Mendes](https://github.com/yabamiah)

## Bibliografia
> Elicitação de Requisitos, PUC-Rio. Disponível em: [https://www.maxwell.vrac.puc-rio.br/15760/15760_3.PDF](https://www.maxwell.vrac.puc-rio.br/15760/15760_3.PDF).<br>
> Luiz Eduardo Galvão Martins. Uma Metodologia de Elicitação de Requisitos de Software Baseada na Teoria da Atividade. Unicamp, 2001. <br>
> Marcelo Medeiros Eler. Aula 5 - Requisitos de Software - Conceitos e Técnicas de Elicitação. Universidade de São Paulo, 2006. Disponível em: [https://edisciplinas.usp.br/pluginfile.php/7993139](https://edisciplinas.usp.br/pluginfile.php/7993139/mod_resource/content/1/05%20-%20Requisitos%20de%20Software%20-%20Conceitos%20e%20T%C3%A9cnicas%20de%20Elicita%C3%A7%C3%A3o.PDF).<br>

## 📑 Histórico de Versões
| **Versão**   |   **Data**   | **Descrição** | **Autor** | **Revisor** |
|--------|---------|-----------|--------|---------|
|`1.0`| 14/10/2023 | Criação da página de introspecção | [Vinícius Mendes](https://github.com/yabamiah)| [Luís Miranda](https://github.com/LuisMiranda10) e [Altino Arthur](https://github.com/arthurrochamoreira) |
|`2.0`| 25/11/2023 | Melhoria na clareza dos textos | [Altino Arthur](https://github.com/arthurrochamoreira)| [Limirio Guimarães](https://github.com/LimirioGuimaraes) |
|`3.0`| 05/11/2023 | Correção final do artefato | [Vinícius Mendes](https://github.com/yabamiah) | [Breno Queiroz](https://github.com/brenob6)|