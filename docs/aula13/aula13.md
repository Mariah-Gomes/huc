# Avaliação de IHC através de Inspeção Heurística — Goriah

## Evidência e detalhamento do relatório completo

O relatório completo da avaliação, contendo o detalhamento das violações, prints das telas analisadas, graus de severidade, impactos na usabilidade e recomendações de melhoria, está disponível no arquivo abaixo:

**PDF da avaliação heurística:** [Relatório completo em PDF](./Avaliacao_Heuristica_Goriah_v2.pdf)

> Este arquivo em Markdown apresenta uma versão resumida e objetiva da avaliação, com foco na síntese das heurísticas, totais encontrados e visão geral dos resultados. O PDF deve ser consultado como evidência principal e detalhamento completo da inspeção.

---

## Plataforma avaliada

- **Sistema:** Goriah
- **Tipo de avaliação:** Avaliação de IHC através de inspeção heurística
- **Método:** Heurísticas de Nielsen
- **Ambiente avaliado:** Localhost / ambiente de desenvolvimento
- **Navegador utilizado:** Google Chrome
- **Versão:** Em desenvolvimento

Esta avaliação foi realizada em uma versão local do sistema Goriah, ainda em desenvolvimento. Portanto, os problemas identificados representam pontos de melhoria antes da consolidação da próxima versão da plataforma. A equipe pretende realizar os ajustes necessários e disponibilizar a versão atualizada em ambiente de homologação/produção posteriormente.

---

## Descrição da avaliação

A avaliação heurística é um método de inspeção de usabilidade no qual um avaliador analisa a interface de um sistema com base em um conjunto de princípios gerais de usabilidade, conhecidos como heurísticas.

Neste relatório, a interface do Goriah foi analisada com base nas dez heurísticas de Nielsen. Durante a avaliação, foram observadas diferentes telas e fluxos do sistema, como cadastro, login, seleção inicial de interesses, perfil, edição de perfil, feed, comentários, denúncia, chat, criação de publicação, configurações e telas responsivas.

O objetivo da avaliação foi identificar violações de usabilidade que possam prejudicar a compreensão, a eficiência, a consistência ou a experiência geral do usuário na plataforma.

---

## Observação sobre a classificação das violações

Um problema pode se relacionar com mais de uma heurística, mas neste relatório cada violação foi classificada pela heurística predominante, para evitar duplicidade na contagem.

Dessa forma, cada problema identificado foi associado à heurística que melhor representa o impacto principal observado na experiência do usuário.

---

## Dez Heurísticas de Nielsen

| Nº  | Heurística                                                        |
| --- | ----------------------------------------------------------------- |
| 1   | Visibilidade do status do sistema                                 |
| 2   | Compatibilidade entre sistema e mundo real                        |
| 3   | Controle e liberdade para o usuário                               |
| 4   | Consistência e padrões                                            |
| 5   | Prevenção de erros                                                |
| 6   | Reconhecimento em lugar de lembrança                              |
| 7   | Flexibilidade e eficiência de uso                                 |
| 8   | Projeto minimalista e estético                                    |
| 9   | Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros |
| 10  | Ajuda e documentação                                              |

---

## Grau de severidade dos problemas de usabilidade

| Grau | Tipo            | Descrição                                                     |
| ---- | --------------- | ------------------------------------------------------------- |
| 0    | Sem importância | Não afeta a operação da interface                             |
| 1    | Cosmético       | Não há necessidade imediata de solução                        |
| 2    | Simples         | Problema de baixa prioridade, mas que pode ser reparado       |
| 3    | Grave           | Problema de alta prioridade, que deve ser reparado            |
| 4    | Catastrófico    | Problema muito grave, que deve ser reparado de qualquer forma |

---

# Parte 1 — Violações encontradas

As violações completas, com descrição do problema, tela avaliada, heurística predominante, grau de severidade, justificativa, recomendação e print, estão documentadas no relatório em PDF indicado no início deste arquivo.

De forma geral, foram identificados problemas relacionados a:

- ausência ou baixa clareza de feedback visual;
- mensagens de erro genéricas;
- falta de instruções em fluxos pouco intuitivos;
- inconsistências visuais entre componentes;
- problemas de organização em telas responsivas;
- excesso de informação visual em determinados componentes;
- ausência de contadores ou indicação clara de limites em campos;
- dificuldade de compreensão em alguns fluxos de comentários, denúncias e edição de perfil.

## Síntese quantitativa das violações

| Indicador                             |   Resultado |
| ------------------------------------- | ----------: |
| Total de violações registradas        |          24 |
| Heurísticas violadas                  |    10 de 10 |
| Heurísticas sem violação identificada |           0 |
| Severidade predominante               | 2 — Simples |
| Maior severidade identificada         |   3 — Grave |

## Violações por heurística

| Heurística | Descrição                                                         | Quantidade de violações |
| ---------- | ----------------------------------------------------------------- | ----------------------: |
| H1         | Visibilidade do status do sistema                                 |                       7 |
| H2         | Compatibilidade entre sistema e mundo real                        |                       1 |
| H3         | Controle e liberdade para o usuário                               |                       1 |
| H4         | Consistência e padrões                                            |                       4 |
| H5         | Prevenção de erros                                                |                       1 |
| H6         | Reconhecimento em lugar de lembrança                              |                       3 |
| H7         | Flexibilidade e eficiência de uso                                 |                       2 |
| H8         | Projeto minimalista e estético                                    |                       3 |
| H9         | Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros |                       1 |
| H10        | Ajuda e documentação                                              |                       1 |

## Violações por severidade

| Grau | Tipo            | Quantidade |
| ---- | --------------- | ---------: |
| 0    | Sem importância |          0 |
| 1    | Cosmético       |          6 |
| 2    | Simples         |         17 |
| 3    | Grave           |          1 |
| 4    | Catastrófico    |          0 |

---

# Parte 2 — Indicação de boas práticas de heurística

## Síntese das heurísticas avaliadas

Durante a inspeção, foram encontradas violações relacionadas às dez heurísticas de Nielsen. Portanto, considerando o conjunto de telas e fluxos avaliados, nenhuma heurística ficou totalmente sem violação.

| Heurística                                                             | Situação na avaliação | Quantidade de violações |
| ---------------------------------------------------------------------- | --------------------- | ----------------------: |
| H1 — Visibilidade do status do sistema                                 | Violada               |                       7 |
| H2 — Compatibilidade entre sistema e mundo real                        | Violada               |                       1 |
| H3 — Controle e liberdade para o usuário                               | Violada               |                       1 |
| H4 — Consistência e padrões                                            | Violada               |                       4 |
| H5 — Prevenção de erros                                                | Violada               |                       1 |
| H6 — Reconhecimento em lugar de lembrança                              | Violada               |                       3 |
| H7 — Flexibilidade e eficiência de uso                                 | Violada               |                       2 |
| H8 — Projeto minimalista e estético                                    | Violada               |                       3 |
| H9 — Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros | Violada               |                       1 |
| H10 — Ajuda e documentação                                             | Violada               |                       1 |

## Quantidade de heurísticas violadas

- **Total de heurísticas avaliadas:** 10
- **Total de heurísticas com ao menos uma violação:** 10
- **Total de heurísticas sem violação identificada:** 0
- **Total de violações registradas:** 24

Nesta versão, conforme solicitado, a Parte 2 foi mantida apenas como síntese. Os exemplos positivos de boas práticas podem ser preenchidos posteriormente, caso a equipe opte por indicar telas em que cada heurística foi atendida.

---

## Considerações finais

A avaliação permitiu identificar pontos importantes de melhoria na interface do Goriah, principalmente em relação à clareza de feedbacks, consistência visual, responsividade, prevenção de erros e orientação ao usuário.

Como o sistema ainda está em desenvolvimento, os problemas encontrados serão utilizados como base para ajustes futuros antes da disponibilização da próxima versão da plataforma. A inspeção heurística contribui para antecipar dificuldades de uso e melhorar a experiência dos usuários antes de uma nova entrega do sistema.
