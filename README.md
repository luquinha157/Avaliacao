# Avaliacao
Avaliação sobre Django
<h1 align="center">Configurações Iniciais do Django</h1>
## O que é o Django e qual é o seu propósito principal no desenvolvimento web?
:point_right: O Django é um framework de desenvolvimento web em Python que segue o padrão arquitetural Model-View-Controller (MVC). 

:point_right: Seu propósito principal é facilitar a construção de aplicativos web robustos, escaláveis e seguros, permitindo que os desenvolvedores foquem no desenvolvimento de funcionalidades específicas.

:point_right: Ao invés de lidar com tarefas repetitivas e complexas relacionadas à manipulação de bancos de dados, gerenciamento de URLs, autenticação de usuários, entre outros.

## Quais são as principais características do framework Django que o diferenciam de outros frameworks web em Python?
O Django possui várias características distintivas que o diferenciam de outros frameworks web em Python. Algumas das principais características incluem:

:point_right: ORM Integrado (Object-Relational Mapping): Django inclui um ORM que mapeia objetos Python para tabelas de banco de dados, facilitando a interação com o banco de dados sem a necessidade de escrever SQL diretamente.

:point_right: Administração Automática: Oferece uma interface de administração automática que permite aos desenvolvedores criar facilmente interfaces de administração para seus aplicativos, com suporte a operações CRUD (Create, Read, Update, Delete) sem a necessidade de desenvolvimento adicional.

:point_right: Bateria Incluída: Django segue a filosofia de "bateria incluída", fornecendo uma ampla gama de funcionalidades prontas para uso, como autenticação de usuário, manipulação de formulários, manipulação de URLs, entre outros.

:point_right: Padrões Convenção sobre Configuração: Django adere ao princípio de "convenção sobre configuração", o que significa que muitas decisões de configuração são tomadas por padrão, permitindo que os desenvolvedores foquem mais no desenvolvimento de funcionalidades do que em configurações detalhadas.

:point_right: Segurança Integrada: O Django possui várias medidas de segurança integradas para proteger contra ameaças comuns na web, como proteção contra injeção de SQL, ataques CSRF (Cross-Site Request Forgery), e outras vulnerabilidades.

:point_right: Padrão MTV (Model-Template-View): Enquanto muitos frameworks web seguem o padrão MVC (Model-View-Controller), Django segue o padrão MTV, onde o Controller é substituído pelo Template. Essa abordagem é considerada mais adequada para o desenvolvimento web.

:point_right: Documentação Abundante: Django é conhecido por sua documentação extensa e bem escrita, facilitando o aprendizado e a resolução de problemas.

## Explique o conceito de "Model-View-Controller" (MVC) e como ele se aplica ao Django.
O conceito de Model-View-Controller (MVC) é um padrão arquitetural amplamente utilizado no desenvolvimento de software, incluindo frameworks web. O MVC divide uma aplicação em três componentes principais, cada um com uma responsabilidade específica:

Model (Modelo): Representa a camada de dados e lógica de negócios da aplicação. Ele gerencia o acesso e a manipulação dos dados, bem como as regras de negócios. No contexto de um framework web como Django, o modelo está frequentemente associado ao banco de dados e é responsável por representar e manipular os dados.
