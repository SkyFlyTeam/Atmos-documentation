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
O principal objetivo nessa sprint a ser comprido era **proporcionar a recepção de dados à partir de uma conexão mqtt**. E de forma adicional também desenvolvemos a **Dashboard da aplicação.**

Os requisitos funcionais atendidos nesta sprint foram:

- ✔️ **RFN01. Conectar novas estações meteorológicas:** A aplicação deve ter a capacidade de conectar-se a novas estações meteorológicas (físicas) de maneira simples e rápida; <br> <br>
- ✔️ **RFN02. Coleta de dados meteorológicos:** A aplicação deve ter a capacidade de coletar e armazenar os dados enviados pelas estações meteorológicas, a partir de diferentes sensores (dinâmico), de forma segura e persistente bem como interpretar tais dados; <br> <br>
- ✔️ **RFN05. Alertas meteorológicos:** A aplicação deve enviar alertas e notificações baseadas em condições meteorológicas específicas; <br> <br>
- ✔️ **RFN06. Guias interativos:** A aplicação deve conter guias interativos sobre os parâmetros e possíveis riscos;

 <br> <br>

<br> 

<span id="entregas">

# 📲 Entregas
Durante esta sprint, o time entregou artefatos SCRUM validados, como o Backlog do Produto, o Backlog das Sprints e as User Stories, com a participação direta do P.O. e comunicação constante com o cliente. Para entender e alinhar as expectativas do cliente. Dito isso, juntamente ao cliente, acordamos entregar as seguintes funcionalidades:

### RF 01: Conectar novas estações meteorológicas:
A aplicação deve ter a capacidade de conectar-se a novas estações meteorológicas (físicas) de maneira simples e rápida;

### RF 02: Coleta de dados meteorológicos::
A aplicação deve ter a capacidade de coletar e armazenar os dados enviados pelas estações meteorológicas, a partir de diferentes sensores (dinâmico), de forma segura e persistente bem como interpretar tais dados;

### RF 05: Alertas meteorológicos:
A aplicação deve enviar alertas e notificações baseadas em condições meteorológicas específicas;

### RF 06: Guias interativos:
A aplicação deve conter guias interativos sobre os parâmetros e possíveis riscos;


<br />

<span id="metricas">

# 📈 Métricas do Time
A sprint foi composta por 3 user stories e 14 tasks. Embora o gráfico de burndown mostre que o trabalho foi concentrado no final, a realidade é que o time começou a trabalhar antes da sprint, realizando atividades como a criação do mockup, definição de DoR e DoD, elaboração do Backlog da Sprint, e configuração das branches de backend e frontend.

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
| 01 | 13 | Baixa | Eu como ADMINISTRADOR desejo conectar estações à aplicação para poder exibir e manipular seus parâmetros. | 05 | 3 | - A estação deve ter a capacidade de se conectar a aplicação por wifi; <br> - A instalação da estação deve ser simples e rápida; |
| 02 | 14 | Baixa | Eu como ADMINISTRADOR desejo receber parâmetros das estações para administrar e visualizar tais dados. | 08 | 3 | - A estação deve coletar os parâmetros à partir dos sensores e enviá-los para o broker (datalogger); <br> - A estação deve garantir que, mesmo que um data não tenha sida coletado devidamente, os outros sejam enviados sem problemas; |
| 05 | 15 | Baixa | Eu como ADMINISTRADOR E USUÁRIO COMUM desejo receber alertas sobre condições meteorológicas extremas. | 08 | 3 | - O ADMINISTRADOR E USUÁRIO COMUM devem receber alertas sob condições meteorológicas extremas; <br> - O alerta deve ser exibido em notificação do website; |
| 06 | 16 | Baixa | Eu como USUÁRIO COMUM desejo visualizar guias explicativos sobre os parâmetros e sua coleta para compreender os conceitos físicos por trás dos mesmos. | 05 | 3 | Os guias devem ser ilustrados atrativos para o público infanto-juvenil; <br> - Todos os parâmetros devem apresentar os guias com informações sobre, a coleta, a unidade de medida, a física e no que isso afeta o ambiente (no caso de situação excessiva ou escassa); <br> - Além disso guias sobre a estação; |


<span id="links">

# 🔗 Links úteis

- Tags geradas em cada repositório que simbolizam o fim da 1ª sprint:
  - [Repositório frontend](https://github.com/SkyFlyTeam/Atmos-frontend/releases/tag/v3.0)
  - [Repositório backend](https://github.com/SkyFlyTeam/Atmos-backend/releases/tag/v3.0)
  - [Repositório processador-de-dados](https://github.com/SkyFlyTeam/Atmos-processador-dados/releases/tag/v3.0)
  - [Repositório receptor-de-dados](https://github.com/SkyFlyTeam/Atmos-receptor-dados/releases/tag/v3.0)
<br>

