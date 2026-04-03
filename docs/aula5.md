# Organização do Espaço de Problema

## HTA

<img width="1760" height="704" alt="HTA" src="https://github.com/user-attachments/assets/0eac4f85-b986-40c4-a189-5c2d74d62abd" />

| Objetivos/Operações | Problemas e Recomendações |
|---|---|
| **0. Participar do feed**<br>**Plano:** 1 + 2 | **Input:** feed com publicações disponíveis e ações acessíveis ao usuário.<br>**Feedback:** o usuário consegue explorar o feed, interagir com conteúdos e manipular conteúdos próprios.<br>**Plano:** explorar o feed e/ou manipular conteúdo no feed.<br>**Recomendação:** manter navegação clara e ações principais visíveis na interface. |
| **1. Explorar feed**<br>**Plano:** 1.1 / (1.1 > 1.2) | **Plano:** acompanhar conteúdos do feed e, quando desejado, interagir com eles. |
| **1.1 Acompanhar conteúdo** | **Problema:** o usuário pode ter dificuldade para acompanhar as publicações caso o feed não seja organizado ou legível.<br>**Recomendação:** apresentar os conteúdos com hierarquia visual clara e navegação fluida. |
| **1.2 Interagir com conteúdo**<br>**Plano:** 1.2.1 / 1.2.2 / 1.2.3 | **Plano:** permitir ao usuário reagir, comentar ou denunciar publicações conforme sua necessidade. |
| **1.2.1 Reagir a publicações** | **Problema:** o usuário pode não perceber facilmente a possibilidade de reagir ou não compreender o efeito da ação.<br>**Recomendação:** exibir o botão de reação de forma visível e fornecer retorno imediato após a interação. |
| **1.2.2 Comentar publicações** | **Problema:** campos de comentário pouco evidentes ou com fluxo confuso podem dificultar a participação textual do usuário.<br>**Recomendação:** facilitar a abertura da área de comentários e apresentar feedback claro após o envio. |
| **1.2.3 Denunciar publicações** | **Problema:** se o processo de denúncia for pouco claro, o usuário pode desistir de reportar conteúdos inadequados.<br>**Recomendação:** manter o fluxo de denúncia simples, com seleção objetiva do motivo e confirmação da ação realizada. |
| **2. Manipular conteúdo no feed**<br>**Plano:** 2.1 / 2.2 / 2.3 | **Plano:** permitir ao usuário publicar, editar ou excluir conteúdos de sua autoria no feed. |
| **2.1 Publicar conteúdo** | **Problema:** um fluxo confuso ou excessivamente longo pode dificultar a criação de publicações.<br>**Recomendação:** simplificar a criação de conteúdo, destacando campos obrigatórios e o botão de publicar. |
| **2.2 Editar conteúdo** | **Problema:** o usuário pode não perceber como alterar uma publicação já criada ou ter receio de perder informações.<br>**Recomendação:** permitir edição de forma acessível, com conteúdo previamente carregado e confirmação após salvar. |
| **2.3 Excluir conteúdo** | **Problema:** a exclusão acidental de uma publicação pode gerar perda de conteúdo relevante.<br>**Recomendação:** solicitar confirmação antes de excluir e apresentar feedback após a remoção. |

## GOMS

### Goal 0: Participar do feed

- **Goal 1: Explorar o feed**
  - **Goal 1.1: Acompanhar conteúdo**
    - **Method 1.1.A: Navegar pelo feed rolando a tela**
    - **Selection Rule:** usar este método quando o usuário não tiver preferência por um conteúdo específico e quiser apenas acompanhar as publicações disponíveis.
        - **OP. 1.1.A.1:** visualizar a tela inicial do feed
        - **OP. 1.1.A.2:** identificar as publicações exibidas
        - **OP. 1.1.A.3:** rolar a tela para visualizar mais conteúdos
      
    - **Method 1.1.B: Filtrar conteúdo por tags**
    - **Selection Rule:** usar este método quando o usuário tiver interesse em conteúdos de um assunto específico e houver publicações associadas às tags desejadas.
        - **OP. 1.1.B.1:** visualizar a tela inicial do feed
        - **OP. 1.1.B.2:** clicar no botão **Filtrar**
        - **OP. 1.1.B.3:** buscar a(s) tag(s) desejada(s), selecioná-la(s) e clicar em **Aplicar**
        - **OP. 1.1.B.4:** visualizar a tela do feed filtrada com a(s) tag(s) utilizada(s)
      
    - **Method 1.1.C: Buscar conteúdo pelo campo de busca**
    - **Selection Rule:** usar este método quando o usuário quiser localizar uma publicação ou assunto específico.
        - **OP. 1.1.C.1:** visualizar a tela inicial do feed
        - **OP. 1.1.C.2:** clicar no campo de busca para ativar a escrita
        - **OP. 1.1.C.3:** escrever palavras-chave do conteúdo desejado
        - **OP. 1.1.C.4:** visualizar a tela do feed com conteúdos que possuam as palavras-chave informadas

  - **Goal 1.2: Interagir com conteúdo**
    - **Method 1.2.1.A: Reagir a publicações**
    - **Selection Rule:** usar este método quando o usuário quiser expressar uma reação rápida a uma publicação sem adicionar um comentário.
        - **OP. 1.2.1.A.1:** visualizar a publicação desejada no feed
        - **OP. 1.2.1.A.2:** identificar o botão de reação da publicação
        - **OP. 1.2.1.A.3:** clicar no botão de reação desejado
        - **OP. 1.2.1.A.4:** visualizar a reação aplicada à publicação

    - **Method 1.2.2.A: Comentar publicações**
    - **Selection Rule:** usar este método quando o usuário quiser se manifestar de forma textual sobre uma publicação.
        - **OP. 1.2.2.A.1:** visualizar a publicação desejada no feed
        - **OP. 1.2.2.A.2:** identificar e clicar na opção de comentar
        - **OP. 1.2.2.A.3:** visualizar o campo de comentário
        - **OP. 1.2.2.A.4:** escrever o comentário desejado
        - **OP. 1.2.2.A.5:** clicar no botão para enviar o comentário
        - **OP. 1.2.2.A.6:** visualizar o comentário publicado na publicação

    - **Method 1.2.3.A: Denunciar publicações**
    - **Selection Rule:** usar este método quando o usuário identificar uma publicação inadequada e quiser reportá-la.
        - **OP. 1.2.3.A.1:** visualizar a publicação desejada no feed
        - **OP. 1.2.3.A.2:** identificar e clicar no menu de opções da publicação
        - **OP. 1.2.3.A.3:** selecionar a opção **Denunciar**
        - **OP. 1.2.3.A.4:** visualizar a tela ou modal de denúncia
        - **OP. 1.2.3.A.5:** selecionar o motivo da denúncia
        - **OP. 1.2.3.A.6:** clicar no botão para confirmar a denúncia
        - **OP. 1.2.3.A.7:** visualizar a confirmação do envio da denúncia

- **Goal 2: Manipular conteúdo no feed**
  - **Goal 2.1: Publicar conteúdo**
    - **Method 2.1.A: Criar uma nova publicação**
    - **Selection Rule:** usar este método quando o usuário quiser compartilhar um novo conteúdo no feed.
        - **OP. 2.1.A.1:** visualizar a tela inicial do feed
        - **OP. 2.1.A.2:** identificar e clicar no botão de criar publicação
        - **OP. 2.1.A.3:** visualizar a tela de criação de publicação
        - **OP. 2.1.A.4:** preencher os campos obrigatórios
        - **OP. 2.1.A.5:** clicar no botão **Publicar**
        - **OP. 2.1.A.6:** visualizar a publicação criada no feed

  - **Goal 2.2: Editar conteúdo**
    - **Method 2.2.A: Editar uma publicação existente**
    - **Selection Rule:** usar este método quando o usuário quiser alterar informações de uma publicação já criada.
        - **OP. 2.2.A.1:** visualizar uma publicação de sua autoria no feed
        - **OP. 2.2.A.2:** identificar e clicar no menu de opções da publicação
        - **OP. 2.2.A.3:** selecionar a opção **Editar**
        - **OP. 2.2.A.4:** visualizar a tela de edição da publicação
        - **OP. 2.2.A.5:** alterar o conteúdo desejado
        - **OP. 2.2.A.6:** clicar no botão para salvar as alterações
        - **OP. 2.2.A.7:** visualizar a publicação atualizada no feed

  - **Goal 2.3: Excluir conteúdo**
    - **Method 2.3.A: Excluir uma publicação existente**
    - **Selection Rule:** usar este método quando o usuário quiser remover do feed uma publicação de sua autoria.
        - **OP. 2.3.A.1:** visualizar uma publicação de sua autoria no feed
        - **OP. 2.3.A.2:** identificar e clicar no menu de opções da publicação
        - **OP. 2.3.A.3:** selecionar a opção **Excluir**
        - **OP. 2.3.A.4:** visualizar a mensagem de confirmação da exclusão
        - **OP. 2.3.A.5:** clicar no botão para confirmar a exclusão
        - **OP. 2.3.A.6:** visualizar o feed sem a publicação excluída

## CTT
<img width="763" height="901" alt="CTT drawio" src="https://github.com/user-attachments/assets/6223ea58-a1da-496d-9ea0-638f0e7bed1a" />
