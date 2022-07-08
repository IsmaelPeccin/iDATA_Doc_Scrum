 # Documentação para aplicação do Framework SCRUM 

Esta documentação tem por objetivo demonstrar um overview sobre o funcionamento da metodologia Scrum e como adaptar e aplicar o framework para o time de desenvolvimento front-end do projeto Comex360, na empresa iDATA.


# Princípio das  Metodologias Ágeis

Os métodos ágeis são uma alternativa à gestão tradicional de projetos. Eles nasceram nos braços do desenvolvimento de software, mas hoje são aplicados a qualquer tipo de projeto. Esses métodos vêm ajudando muitas equipes a encarar as imprevisibilidades de um projeto através de entregas incrementais e ciclos iterativos.

Os métodos ágeis buscam promover um processo de gerenciamento de projetos que incentiva a inspeção e adaptação frequente. É uma filosofia que acaba por incentivar o maior trabalho em equipe, a auto-organização, a comunicação frequente, o foco no cliente e a entrega de valor.

Basicamente, os métodos ágeis são um conjunto de práticas eficazes que se destinam a permitir a entrega rápida e de alta qualidade do produto, tendo uma abordagem de negócios que alinha o desenvolvimento do projeto com as necessidades do cliente e os objetivos da empresa.

# Manifesto Ágil

O nascimento dos métodos ágeis dá-se com o lançamento do Manifesto Ágil. Esse manifesto traz princípios para o desenvolvimento de software que tem como objetivo colocar clientes no centro do desenvolvimento, buscando entregar softwares que satisfaçam suas dores e necessidades. Com isso, os produtos respondem mais rapidamente às mudanças, entregando com maior frequência versões novas do software com melhorias incrementais.

O desenvolvimento tradicional, forma predominante antes da publicação do manifesto ágil, tinha como centro a documentação completa do projeto. O cliente só era envolvido quando o produto estava pronto. Esta forma tradicional, também chamada de cascata, tem um tempo muito mais lento de resposta à mudança, aprendizado e feedback, o que pode comprometer a entrega de valor e a relevância do produto. Sem envolver o cliente desde o início, corremos o risco de não atender nenhuma dor e entregar um produto obsoleto.

<details>
    <summary><strong> Principais pilares do Manifesto Ágil</strong></summary><br />
    <ol>
        <li>Indivíduos e interações mais que processos e ferramentas</li>
        <li>Software em funcionamento mais que documentação abrangente</li>
        <li>Colaboração com o cliente mais que negociação de contratos</li>
        <li>Responder a mudanças mais que seguir um plano</li>
    </ol>
</details><br />

É importante frisar que as metodologias ágeis não são aplicadas apenas na área de Desenvolvimento de Software. As técnicas e filosofias ágeis são aplicadas em empresas e organizações de diversas outras áreas. Essa popularização acabou por criar subtipos para a gestão ágil, cada um com suas peculiaridades: os chamados "frameworks" ágeis.

# Framework Scrum 

## Definição: 
- O Scrum é um <i>framework</i> ágil baseado em entregas iterativas e incrementais e baseado em em processos empíricos.
- A estrutura do Scrum é baseada no aprendizado contínuo e na adaptação aos fatores variáveis. O Scrum reconhece que a equipe não sabe tudo no início de um projeto e que evoluirá de acordo com a experiência. Ele é estruturado para ajudar as equipes a se adaptarem naturalmente às mudanças e aos requisitos do usuário, com repriorização integrada no processo e ciclos curtos de liberação para que sua equipe aprenda e melhore constantemente.


## Equipe Scrum (Papéis)


### Fazem parte da Equipe Scrum: 

<details>
  <summary><strong>Time de desenvolvimento</strong></summary>

  Pessoas que trabalham no desenvolvimento dos incrementos do produto.

  - Equipe  auto-organizada e multifuncional.

  - Gerenciam o `backlog` do produto.

  Bons times de desenvolvimento Scrum se organizam e abordam projetos de forma coletiva, impondo claramente o "nós". É esperado que todos os membros do time se ajudem para garantir a conclusão bem-sucedida da Sprint.

</details>
<br/>
<details>
  <summary><strong>Scrum Master</strong></summary>

  - `Coach` da equipe.

  - Líder Servidor.

  O Scrum Master é o facilitador das cerimônias do Scrum, é o responsável por garantir que todos os integrantes da equipe compreendam e sigam as regras do `Scrum`. Gerencia processos de forma que as pessoas possam trabalhar de forma colaborativa, motivada e auto-organizada.

</details>
<br/>
<details>
  <summary><strong>Product Owner</strong></summary>

  São responsabilidades  `Product Owner`:

  - Elaborar a visão do produto.
  - Gerenciar o escopo do produto (`Backlog do Produto`), garantindo valor, entendimento e visibilidade.

</details>

---

## Regras do Scrum 

### Sprint 

  O Sprint representa um espaço de tempo, normalmente de 2 a 4 semanas, no qual um conjunto de atividades deve ser executado. As funcionalidades a serem implementadas em um projeto são mantidas em uma lista que é conhecida como Product Backlog. Este material contém todas as funcionalidades que foram elencadas como importantes para quem usa o produto, e é responsabilidade do PO (a partir deste ponto, usaremos a sigla PO para referir ao Product Owner) definir seu conteúdo. Estas informações não precisam necessariamente estar disponíveis no início de um projeto, podendo ser acrescidas, alteradas e melhoradas à medida que se aprende mais sobre o produto e quem o usa.

## Cerimônias do Scrum 

### Planejamento da Sprint

  Reunião realizada no primeiro dia da `Sprint`, dividida em duas partes:
   - Parte 1 : O PO apresenta o `Backlog do Produto` ordenado e alinha com o Time de desenvolvimento quais itens poderão ser entregues dentro da capacidade da equipe, definindo a meta da `Sprint`
   - Parte 2: O Time de desenvolvimento define e estima as tarefas necessárias para atingir a meta da `Sprint`.

### Daily Scrum

  Reunião diária como o objetivo de disseminar a evolução do projeto, e identificar impedimentos que podem ser resolvidos com ajuda dos membros da equipe. A Daily deve ser breve, com `timebox` de no máximo 15 minutos, e cada integrante deve basicamente responder à três perguntas:
  - O que você fez ontem?
  - O que fará hoje?
  - Há algum impedimento no seu caminho?

### Revisão da Sprint 

  Ao final de um Sprint, o Time de desenvolvimento apresenta as funcionalidades implementadas, e o PO aprova ou não as entregas. Devem participar desta reunião a pessoa PO, a pessoa Scrum Master, o Scrum Team e, opcionalmente, clientes, a gerência e, se pertinente, pessoas técnicas de outros projetos. 

### Retrospectiva da Sprint

  Finalmente, faz-se uma Sprint Retro Meeting (ou Sprint Retrospective), onde são apontados os pontos positivos e negativos do último Sprint, assim como ações para mitigar os pontos negativos e evitar que se repitam. Após essa reunião, a equipe parte para o planejamento do próximo Sprint.
  Para o sucesso da Retrospectiva da Sprint, é importante que três questões - chave sejam respondidas:
  - O que deu certo durante a Sprint?
  - O que precisa ser melhorado durante as próximas Sprints?
  - Quais ações de melhoria iremos incorporar na Sprint seguinte?

  ## Artefatos que compõem o Scrum 

  ### Backlog do Produto 

  Lista ordenada de requisitos necessários para o produto. Gerenciado única e exclusivamente pelo PO.

  ### Sprint Backlog 

  Lista de tarefas que deverão ser executadas durante a Sprint para atingir sua meta. Gerenciado única e exclusivamente pelo time de desenvolvimento.

  ### Definição de Pronto (`Done`)

  Critérios que deverão ser atendidos para verificar se um item do `Backlog do Produto` foi finalizado (done) ou não.

  # Aplicação do Scrum no contexto do Projeto Comex360 

  ## Visão Geral

  De modo geral, o Scrum é uma estrutura que ajuda as equipes a trabalharem de forma colaborativa, aprenderem com as experiências, a se organizarem enquanto resolvem um problema e refletirem sobre os êxitos e fracassos buscando a melhoria continua. Além disso, o Scrum em si é simples, suas regras, artefatos e eventos são fáceis de entender.
  
  Partindo da premissa que a equipe de desenvolvimento do Comex360 será composta por membros que estarão em home office e membros que estarão presencialmente no escritório, a implementação das cerimônias do Scrum serão de grande importância para suportar um time colaborativo e que de fato seja possível implementar uma cultura ágil que atinja a todos os colaboradores do projeto.
  

  ## Time Scrum

  O Time Scrum do Comex360 terá a seguinte configuração: 

  <details>
    <summary><strong>Product Owner</strong></summary>
      Bráulio Nienow
  </details>
  <br/>
  <details>
    <summary><strong>Scrum Master</strong></summary>
      Marco 
  </details>
  <br/>
  <details>
    <summary><strong> Time de Desenvolvimento</strong></summary>
      Time composto por 7 pessoas programadoras, sendo uma ou duas dessas pessoas também responsáveis pelo QA. 
  </details>

  ## Organização das cerimônias

  As cerimônias serão realizadas de forma online e presencial simultaneamente, através de vídeo-conferência.
  As cerimônias de Planejamento, Revisão e Retrospectiva da Sprint não possuem datas nem horários fixos para acontecerem, e seus respectivos timebox dependem do tempo de duração da Sprint. 
  Já as Daily Meets são diárias, no período da manhã e terão timebox de 15 minutos. 







