# quick-map-search

### Alunos: Erik Tomelin, Gustavo Malkovski, Vinícius Ferri

- O projeto tem como base encontrar a rota mais rápida entre os pontosescolhidos pelo usuário, um exemplo que temos é de um entregador que tem queadicionar cada ponto separadamente em seu aplicativo de mapa online. Com issopodemos economizar o tempo e também combustível/esforço utilizado pelo mesmo.O intuito do aplicativo é realizar da maneira mais limpa e fácil o possível a escolhados pontos que devem ser feitas as entregas e também uma linguagem maissimples para a aplicação ser mais fluida em diversos dispositivos. Futuramentepodemos integrar diretamente com algum aplicativo de delivery (exemploZéDelivery).

#

- O código fonte será feito com base na linguagemangularque tem umtemplate feito de como deve-se escrever o código e como organizar as pastas.Utilizaremos a metodologiaKISSe tambémSOLIDe desenvolvemostestesunitários baseados no que já existe noangular.

Nosso sistema possuirá testes unitários, tanto nofrontend, quanto nobackend, porém, nofrontend, não há necessidade nacriação de testes unitários emtodos os componentes do sistema, justamente por conta de alguns componentesserem menos funcionais que outros. Os que de fato, tiverem mais funçõesatribuídas a si, serão criados seus testes unitários correspondentes.Nofrontend, em Angular, usaremos oframeworkLinte nobackend, emPython,usaremos oSonarCube. O sistema não possui ferramentasde integração contínuae no momento, ainda não foi definida nenhuma estratégia de monitoramento naaplicação. Dentro do aspecto de Infraestrutura e características de projeto. Oframeworkusado para Infraestrutura será oKubernetspor conta daInfrastructure ascode(IaC) em nuvem. A aplicação está sendo pensadapara ser a mais resilientepossível. O projeto tem como foco a venda do serviço em si, ou a integração doserviço em outros sistemas.

- Testes unitários
  - frontend e backend (alguns baseados no que já existe no Angular)
- Fron-end
  - Angular
- Back-end
  - Python
  - SonarCube
- Infraestrutura e características de projeto
  - Kubernet (por conta da Infrastructure ascode(IaC) em nuvem)
- Metodologias 
  - KISS
  - SOLID 
