![1° Sprint](./mgt/BannerSmartFarm.png)

<br>

<p align="center">
    <a href="#objetivos"> Objetivos da Sprint </a> &nbsp |&nbsp &nbsp
    <a href="#entregas"> Entregas </a> &nbsp |&nbsp &nbsp
    <a href="#metricas"> Métricas do Time </a>  &nbsp |&nbsp &nbsp  
    <a href="#backlog"> Backlog da Sprint </a>  &nbsp |&nbsp &nbsp  
    <a href="#links"> Links úteis </a>
</p>

No início do desenvolvimento da aplicação de controle de ponto eletrônico, a primeira sprint focou no MVP (Produto Mínimo Viável), priorizando as funcionalidades mais essenciais. A equipe concentrou seus esforços no CRUD básico do sistema. Entre as funcionalidades desenvolvidas, destacam-se o cadastro de estações, parâmetros, alertas e usuários, bem como o sistema de login da plataforma.

<span id="objetivos">

# 🎯 Objetivos da Sprint
Os requisitos funcionais atendidos nesta sprint foram:

- ✔️ **RFN04. Configuração de parâmetros de estações:** <br> A aplicação deve ter a capacidade de configurar individualmente a unidade de medida dos parâmetros recebidos além dos nomes de suas respectivas estações; <br> <br>
- ✔️ **RFN05. Alertas meteorológicos:** <br> A aplicação deve enviar alertas e notificações baseadas em condições meteorológicas específicas; <br> <br>
- ✔️ **RFN07. Cadastro e gestão de administradores:** <br> A aplicação deve ter a capacidade de cadastrar e gerenciar usuários administradores; <br> <br>

<br> 

<span id="entregas">

# 📲 Entregas
Durante esta sprint, o time entregou artefatos SCRUM validados, como o Backlog do Produto, o Backlog das Sprints e as User Stories, com a participação direta do P.O. e comunicação constante com o cliente. Para entender e alinhar as expectativas do cliente, foi criado um protótipo inicial no Figma, que ajudou a definir a identidade visual e o design do sistema. Esse protótipo foi validado com o cliente e traduzido em uma aplicação React, integrando as funcionalidades acordadas para esta sprint.

### RF 04: Configuração de parâmetros de estações
O usuário tem a capacidade de cadastrar parâmetros e atrelá-los às estações, definindo quais estações carregam quais tipos de parâmetros, além de, claro, possuir a capacidade de cadastrar e administrar as estações do sistema;

### RF 05: Alertas meteorológicos
O usuário tem a capacidade de cadastrar e administrar tipos de alertas meteorológicos na aplicação dessa forma dando a capacidade do usuário de 
preparar alertas específicos após cada recepção; 

### RF 03: Cadastro e gestão de administradores
O usuário tem a capacidade de cadastrar e gerir administradores da aplicação. Apenas esses são capazes de realizar os cadastros préviamente citados.


<br />

<span id="metricas">

# 📈 Métricas do Time
A sprint foi composta por 8 user stories e 27 tasks. Embora o gráfico de burndown mostre que o trabalho foi concentrado no final, a realidade é que o time começou a trabalhar antes da sprint, realizando atividades como a criação do mockup, definição de DoR e DoD, elaboração do Backlog da Sprint, e configuração das branches de backend e frontend.

O gráfico de burndown mostra a evolução do trabalho ao longo da sprint. A linha horizontal representa o tempo, ou seja, as datas da sprint, enquanto a linha vertical indica os pontos de história que representam o esforço total planejado para a sprint. A linha cinza mostra a taxa de progresso ideal, indicando como o trabalho deveria ser realizado de maneira constante ao longo dos dias. Já a linha vermelha indica o trabalho realizado, que no gráfico reflete a conclusão das User Stories 100% finalizadas. O pico no gráfico ocorre quando as User Stories são concluídas, explicando a aparente concentração de trabalho no final da sprint. Na prática, a maior parte das subtasks já estava concluída antes das últimas entregas.

<br />
    
<div align="center">
<img src="./mgt/burndown.png" alt="Gráfico Burndown" />
</div>

<br>

<span id="backlog">

# 📃 Backlog da Sprint

| **RFN** | **Rank** | **Prioridade** | **User Story** | **Estimativa** | **Sprint** | **Critérios de Aceitação** |
|---------|----------|----------------|----------------|----------------|------------|---------------------------|
| 04 | 01 | Alta | Eu como ADMINISTRADOR e USUÁRIO COMUM desejo visualizar as estações conectadas | 08 | 1 | - TODOS OS USUÁRIOS devem visualizar as estações conectadas; <br> - Todas as estações devem exibir o nome e imagem referente; <br> - Paginação contendo 15 itens cada; Barra de pesquisa por nome; |
| 04 | 02 | Alta | Eu como ADMINISTRADOR E USUÁRIO COMUM desejo visualizar os parâmetros dentro de uma estação. | 03 | 1 | - TODOS OS USUÁRIOS devem visualizar os parâmetros das estações e suas devidas unidades se cadastradas; <br> - Parâmetros sem unidade de medida definida devem ser sinalizados por meio um elemento gráfico; |
| 04 | 03 | Alta | Eu como ADMINISTRADOR desejo cadastrar e alterar parâmetros de uma estação. | 05 | 1 | - O ADMINISTRADOR deve conseguir alterar as unidades de medida dos parâmetros de uma estação em específico; <br> - Os parâmetros não alterados devem permanecer com seus respectivos valores após alteração de outros; <br> - Deve ser gravada a data da alteração de tal parâmetro; |
| 04 | 04 | Alta | Eu como ADMINISTRADOR desejo alterar o nome e imagem da estação conectada. | 02 | 1 | - O ADMINISTRADOR deve conseguir alterar o nome e imagem de uma estação; <br> - O nome ou imagem não alterado deve permanecer o mesmo após alteração do outro; <br> - Nome é um campo obrigatório; |
| 07 | 05 | Alta | Eu como ADMINISTRADOR desejo efetuar login para acessar funcionalidades exclusivas do meu papel. | 08 | 1 | - O ADMINISTRADOR deve conseguir efetuar login devidamente na aplicação; |
| 07 | 06 | Baixa | Eu como SUPER ADMINISTRADOR desejo cadastrar outros usuários administradores para facilitar a administração da aplicação. | 03 | 1 | - O SUPER ADMINISTRADOR deve conseguir cadastrar devidamente um novo administrador; | 
| 07 | 07 | Baixa | Eu como ADMINISTRADOR desejo alterar minhas próprias informações de cadastro para a manutenção do perfil. | 02 | 1 | - O ADMINISTRADOR deve conseguir alterar suas informações com sucesso; |
| 05 | 08 | Baixa |Eu como ADMINISTRADOR desejo cadastrar tipos de alertas para visualizar que tipo de alertas os usuários poderão receber. | 03 | 1 | - O ADMINISTRADOR deve conseguir cadastrar/editar tipos com sucesso; <br> - TODOS OS USUÁRIOS devem poder visualizar os tipos de alertas cadastrados | 


<span id="links">

# 🔗 Links úteis

- Tags geradas em cada repositório que simbolizam o fim da 1ª sprint:
  - [Repositório frontend](https://github.com/SkyFlyTeam/Atmos-frontend/releases/tag/v1.0)
  - [Repositório backend](https://github.com/SkyFlyTeam/Atmos-backend/releases/tag/v1.0)
  - [Repositório processador-de-dados](https://github.com/SkyFlyTeam/Atmos-processador-dados/releases/tag/v1.0)
<br>

