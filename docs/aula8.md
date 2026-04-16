# Aula 8 - Ciclo de Vida de Engenharia de Usabilidade

## 1. Características da Plataforma

O projeto Goriah consiste em uma rede social acadêmica voltada à integração universitária, à troca de conhecimento e à conexão entre estudantes em diferentes momentos da graduação. Conforme já definido nas etapas anteriores, a aplicação será utilizada por alunos e professores, com foco especial no uso por estudantes em contexto institucional universitário. O sistema foi pensado para ser acessado principalmente por computador e smartphone, tanto dentro quanto fora da universidade, em situações como intervalos entre aulas, deslocamentos, biblioteca, residência e pausas no trabalho.

Além disso, as personas construídas ao longo do projeto mostram que o uso da plataforma ocorre em um ambiente dinâmico, fragmentado e com diferentes objetivos: enquanto estudantes ingressantes buscam pertencimento, socialização e descoberta de oportunidades, estudantes veteranos e trabalhadores buscam eficiência, segmentação de conteúdo, networking e apoio ao TCC.

### 1.1 Descrição de software e hardware da plataforma prevista para o projeto

| Item                   | Descrição                                                                                                                                                                                                                                                                                |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Software da plataforma | Aplicação web responsiva, voltada ao ambiente universitário, com funcionalidades como cadastro, login, visualização de feed, criação de publicações, comentários, filtros, busca por tags e palavras-chave, visualização e edição de perfis, além de recursos de conexão entre usuários. |
| Hardware da plataforma | Acesso principal por notebooks, desktops e smartphones, considerando que o público utiliza com frequência dispositivos móveis e computadores na rotina acadêmica.                                                                                                                        |

### 1.2 Capacidades da plataforma

| Capacidade                                           | Justificativa                                                                                                                                                                                                                              |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Acesso por computador e smartphone                   | O contexto de uso definido nas etapas anteriores mostra que os estudantes acessam sistemas e redes sociais tanto em computadores quanto em smartphones, dentro e fora da universidade. Isso amplia a disponibilidade de acesso ao sistema. |
| Mobilidade                                           | Como parte importante do público utiliza o celular durante deslocamentos, intervalos e momentos curtos da rotina, a plataforma tem capacidade de apoiar interações rápidas em diferentes ambientes.                                        |
| Responsividade                                       | A aplicação pode adaptar sua interface a diferentes tamanhos de tela, favorecendo o uso contínuo por perfis com rotinas distintas, como a Ana e o Lucas.                                                                                   |
| Centralização de informações acadêmicas e sociais    | O sistema tem capacidade de reunir em um único ambiente conteúdos que hoje estão dispersos entre grupos, redes sociais e canais informais, reduzindo fragmentação informacional.                                                           |
| Segmentação por interesses, curso ou tema            | Como o projeto prevê filtros, busca por tags e palavras-chave, a plataforma pode organizar melhor os conteúdos e facilitar o acesso a discussões relevantes para cada perfil de usuário.                                                   |
| Apoio à interação social-acadêmica                   | A proposta da rede favorece comentários, conexões, trocas de dúvidas, divulgação de eventos, projetos e pesquisas, respondendo diretamente às necessidades levantadas nas personas e na pesquisa.                                          |
| Apoio à divulgação de TCC, pesquisas e questionários | A persona Lucas e os dados levantados mostram valor em recursos que ajudem na circulação de pesquisas, feedback e networking acadêmico.                                                                                                    |

### 1.3 Restrições da plataforma

| Restrição                                                    | Justificativa                                                                                                                                                                                                                                         |
| ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Dependência de internet                                      | Por ser uma aplicação web, seu funcionamento depende de conexão com a internet, o que pode impactar usuários em deslocamento ou em ambientes com rede instável.                                                                                       |
| Limitações de tela em smartphones                            | Como boa parte do uso ocorre em dispositivos móveis, há restrições relacionadas ao espaço reduzido para exibir muitos elementos, filtros e conteúdos simultâneos. Isso exige organização visual cuidadosa.                                            |
| Atenção fragmentada do usuário                               | O contexto de uso mostra que muitos acessos acontecem em momentos curtos, em ambientes ruidosos ou com atenção dividida. Isso limita interações longas e exige fluxos simples e objetivos.                                                            |
| Excesso de informação pode prejudicar a experiência          | As análises de concorrência e das personas mostram que muito conteúdo simultâneo e mal organizado pode gerar confusão e ruído informacional, especialmente para usuários como Lucas.                                                                  |
| Variação de familiaridade entre usuários                     | Embora muitos estudantes tenham forte uso de redes sociais, nem todos possuem o mesmo repertório digital ou a mesma forma de interação com sistemas acadêmicos. Isso exige interface intuitiva e familiar.                                            |
| Necessidade de equilíbrio entre socialização e produtividade | O sistema precisa atender tanto usuários que buscam integração e acolhimento quanto usuários que buscam eficiência e relevância. Isso cria uma restrição de projeto importante, pois a interface não pode pender excessivamente para um único perfil. |

## 2. Princípios Gerais do Projeto

| Nome                                                        | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Link                                                                                   |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------- |
| Descrição do Contexto                                       | O Goriah é uma rede social acadêmica voltada à integração universitária, à troca de conhecimento e à conexão entre estudantes em diferentes momentos da graduação. A aplicação será utilizada principalmente por alunos em ambiente universitário, por meio de computador e smartphone, tanto dentro quanto fora da universidade. O contexto de uso envolve situações como intervalos entre aulas, deslocamentos, biblioteca, residência e pausas no trabalho, com interações rápidas, busca de informações acadêmicas, divulgação de oportunidades, participação em discussões e apoio ao desenvolvimento do TCC. |
| Lei Geral de Proteção de Dados (LGPD) - Lei n.º 13.709/2018 | A LGPD é a legislação brasileira que regulamenta o tratamento de dados pessoais no Brasil. É importante para o projeto porque o Goriah envolve cadastro, autenticação, perfil de usuário, interações e circulação de informações pessoais, exigindo cuidado com coleta, armazenamento, processamento e proteção desses dados, garantindo privacidade e segurança aos usuários.                                                                                                                                                                                                                                     | https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm                |
| Lei n.º 10.098/2000 - Lei da Acessibilidade                 | Esta lei brasileira estabelece normas gerais e critérios básicos para a promoção da acessibilidade das pessoas com deficiência ou com mobilidade reduzida. É importante para o projeto porque a plataforma deve oferecer uma interface acessível, compreensível e utilizável por diferentes perfis de usuários, independentemente de limitações físicas, visuais ou cognitivas.                                                                                                                                                                                                                                    | https://www.planalto.gov.br/ccivil_03/leis/l10098.htm                                  |
| ABNT NBR ISO 9241 Ergonomia da interação humano-sistema     | Esta série de normas brasileiras, baseada na ISO 9241, fornece diretrizes para o design centrado no usuário de sistemas interativos, incluindo a concepção de interfaces. É importante para o projeto porque orienta decisões relacionadas à usabilidade, eficiência, eficácia e satisfação do usuário, ajudando a garantir que a interface do Goriah atenda às necessidades e expectativas do público universitário.                                                                                                                                                                                              | https://www.inf.ufsc.br/~edla.ramos/ine5624/_Walter/Normas/Parte%2011/iso9241-11F2.pdf |

## 3. Metas de Usabilidade

A definição das metas de usabilidade do Goriah foi feita com base no perfil dos usuários, no contexto de uso e nas tarefas analisadas anteriormente. O sistema precisa apoiar dois grandes grupos de necessidades: de um lado, a integração, descoberta e participação social-acadêmica; de outro, a eficiência, a filtragem de informação e a utilidade prática para tarefas mais objetivas, como encontrar conteúdos, responder dúvidas e apoiar o desenvolvimento do TCC.

Além disso, os dados da coleta reforçam a importância de um ambiente que facilite conversa, troca de conhecimento e conexão acadêmica. A pesquisa mostra que a maior parte dos participantes vê valor em conversar e trocar conhecimento de forma dinâmica, e também aponta demanda por um espaço que facilite essa troca. [pesquisa.pdf](./aula7/pesquisa.pdf)

### 3.1 Exigências qualitativas para a interface

As exigências qualitativas do Goriah são:

- a interface deve ser simples de compreender já no primeiro contato, principalmente para estudantes ingressantes;
- o sistema deve apresentar organização clara do feed e das publicações, evitando excesso de informação visual;
- as principais ações do usuário, como comentar, reagir, criar publicação, buscar e filtrar, devem estar visíveis e acessíveis;
- a navegação deve ser consistente entre as páginas, mantendo padrão visual e de interação;
- o sistema deve oferecer feedback claro após ações como publicar, comentar, editar, denunciar ou excluir conteúdos;
- a plataforma deve favorecer interações rápidas e objetivas, considerando o uso em momentos curtos e contextos fragmentados;
- a interface deve reduzir ruído informacional e facilitar a localização de conteúdos relevantes;
- a aplicação deve apoiar tanto a integração social quanto a produtividade acadêmica;
- a experiência deve ser responsiva e adequada ao uso em smartphone e computador;
- a plataforma deve respeitar princípios de acessibilidade, legibilidade e clareza visual.

### 3.2 Exigências quantitativas para a usabilidade

Seguindo a orientação apresentada pelo professor, foram consideradas as cinco metas de usabilidade de Nielsen, com distribuição equilibrada de peso, já que todas são relevantes para o projeto. Os próprios materiais da aula reforçam que, quando não há motivo forte para eliminar ou priorizar uma meta específica, a distribuição igualitária é válida.

| Meta de usabilidade       | Peso | Justificativa                                                                                                                                                            |
| ------------------------- | ---: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Facilidade de aprendizado |  20% | É importante para usuários como Ana, que precisam se sentir confortáveis ao entrar em um novo ambiente digital voltado à universidade.                                   |
| Facilidade de memorização |  20% | Como o uso da plataforma pode ocorrer de forma intermitente ao longo da rotina acadêmica, o usuário deve conseguir retomar tarefas sem dificuldade.                      |
| Eficiência                |  20% | Essa meta é especialmente importante para usuários como Lucas, que valorizam rapidez, filtragem e objetividade.                                                          |
| Baixa taxa de erro        |  20% | O sistema deve evitar confusão em ações importantes, como denunciar, publicar, editar ou excluir conteúdos. Isso também aparece na análise de tarefas feita pela equipe. |
| Satisfação do usuário     |  20% | Como o projeto busca se tornar um espaço de uso recorrente, a experiência deve ser agradável, útil e confiável, estimulando continuidade de uso e participação.          |

## 4. Síntese da Etapa

A etapa de ciclo de vida de engenharia de usabilidade permitiu consolidar elementos já levantados nas fases anteriores do projeto, articulando contexto de uso, perfis de usuários, tarefas, plataforma e metas de usabilidade. No caso do Goriah, ficou evidente que o sistema deve equilibrar acolhimento, integração e descoberta para estudantes ingressantes com eficiência, segmentação e utilidade prática para estudantes veteranos e trabalhadores.

Dessa forma, as características da plataforma, os princípios gerais de projeto e as metas de usabilidade passam a orientar as próximas decisões de design, prototipação e avaliação da interface, mantendo coerência com o problema identificado ao longo da disciplina.
