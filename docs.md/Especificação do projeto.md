# Especificações do Projeto 

Sistema Web que conecta ONGs grupos de proteção animal, voluntários e tutores que tenham interesse de resgatar, cuidar e adotar animais em situações de vulnerabilidade, o sistema oferece informações sobre adoção, serviços veterinários gratuitos, campanhas e parcerias com empresas do setor pet. 

Tecnologias: 

*Front: 

-  HTML + CSS; 

- BootStrap; 

*Back:  

- JavaScript 

- Local Storage 

- CrudServerJSON 


## Personas 

- Persona 1:  

Aline é uma veterinária de 27 anos, tutora de dois gatinhos resgatados, que encontrou abandonados em uma caixa de papelão enquanto voltava do trabalho. Engajada na causa animal e parte de um grupo protetor que oferece atendimento gratuito para tutores de pet em vulnerabilidade social e para animais resgatados em sua clínica. Ela usaria nossa aplicação para divulgar seus serviços e as campanhas que seu grupo protetor promove para adoções responsáveis e bem-estar animal. 

- Persona 2: 

Gustavo é um estudante do ensino médio de 18, que estagia em uma em uma pequena empresa de distribuição e recebe menos de um salário-mínimo, e gostaria de adotar um animal resgatado de forma responsável e precisa receber auxílio com os cuidados médicos de seu bichinho e saber melhor como cuidar devidamente dele. 

- Persona 3: 

Camila é uma fisioterapeuta, recém formada, que tem seu próprio consultório, nos momentos em que não está atendendo, ela sempre dedica seu tempo a causa animal, dona de 4 cachorros e 2 gatos, todos adotados, que estavam em situação vulnerável, Camila em seu tempo livre auxilia uma veterinária em uma clínica no bairro onde mora, essa clinica cuida de pets em situação de vulnerabilidade e presta serviços sociais para pessoas de baixa renda, sempre engajada, posta em suas redes sociais sobre eventos de adoção, castração, além de divulgar pets perdidos, e pets para adoção. 

- Persona 4: 

Sofia é uma empresária de sucesso no ramo pet, tem 40 anos e vasta experiência em administrar seu próprio negócio. Ela é conhecida por sua ética empresarial e seu compromisso com a responsabilidade social. Além de seu sucesso nos negócios, Sofia tem uma paixão profunda por animais e acredita que as empresas têm a responsabilidade de fazer a diferença na sociedade, com esse pensamento ela sempre está engajada em campanhas e projetos da causa animal oferendo em sua empresa serviços gratuitos e a preço social para tutores de baixa renda e parcerias com ONGs 

- Persona 5: 

Robson trabalhou durante muitos anos de sua vida como um agente de controle zoonose, por esse motivo teve muita empatia e apego por animais. Atualmente não está trabalhando como um agente de controle, mas atua como voluntário em uma ONG de resgate de animais abandonados e faz parte de um grupo protetor que sempre realiza campanhas de adoção consciente.  

- Persona 6: 

Silvania é professora de matemática de 60 anos. Aposentada, ela agora criou um hobby de cuidar de animais domésticos, sendo os seus próprios pets ou ajudando vizinhos e familiares com problemas com seus animais. 

- Persona 7: 

Laura Soares tem 55 anos e, atualmente, é cuidadora de animais. Depois de se aposentar como professora da rede pública de Contagem em 2017, ela se dedica aos cuidados de animais de rua. Ciente dos custos e demais dificuldades de dar cuidados adequados a animais domésticos, Laura recorreu inicialmente a grupos de apoio locais e, posteriormente, a redes sociais para angariar fundos que propiciassem o acolhimento de seus 18 cães, todos resgatados da rua, a maioria em situação de maus tratos. Essa experiência fez com que ela chegasse a conclusão que, sem uma rede de apoio ampla e sólida, o combate ao problema do grande número de pets abandonados seria insuficiente.  

- Persona 8: 

Maria da Silva de 40 anos cresceu em uma família de baixa renda e sempre teve uma ligação especial com animais. Ela passou a maior parte de sua vida cuidando de gatos de rua e cães abandonados. Mesmo enfrentando dificuldades financeiras, ela nunca deixou de ajudar os animais de sua comunidade. Ela mora em um bairro de classe baixa onde o abandono de animais é comum e os recursos para cuidados com animais são limitados e deseja criar um projeto que ajude as pessoas de baixa renda em sua comunidade a encontrar serviços sociais para seus animais de estimação. Ela pretende achar uma plataforma online simples que liste clínicas veterinárias que ofereçam tratamento gratuito ou a preços acessíveis, programas de castração e datas de ações de vacinação. Maria também quer estabelecer parcerias com voluntários locais para auxiliar as famílias a acessar esses serviços. 


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários: 

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Tutor de pet        | Me cadastrar           | Encontrar campanhas em andamento e serviços por perto |
|Futuro tutor de pet       | Me cadastrar                 | Encontrar instituições por perto onde possa adotar um pet |
|Voluntário  | Me cadastrar           | Encontrar instituições e grupos de proteção animal que precisem de auxilio               |
|Doador       | Me cadastrar                 | Encontrar instituições, grupos de proteção animal ou tutores de pet que precisem de doação |
|Tutor de pet  | Ter acesso ao perfil/página das instuições           | Obter informações e/ou buscar ou agendar um serviço e, entrar em contato com as mesmas|
|Futuro tutor de pet       | Ter acesso ao perfil/página das instuições                 | Obter informações sobre as instituições e os pets disponíveis para adoção e consegir contato com elas |
|Voluntário  | Ter acesso ao perfil/página das instuições           | Obter informações de contato das instituições e grupos que precisam de apoio e meios de entrar em contato com elas               |
|Doador       | Ter acesso ao perfil/página das instuições e de tutores de pet                 | Obter informações básicas acerca das instituições ou tutores que precisam de doação e meios de contata-los|
|Lideres de Ongs e grupos protetores  | Cadastrar minha instituição ou grupo           | Linkar dados de contato, redes sociais e endereçar o local de atuação               |
|Lideres de Ongs e grupos protetores       | Editar minha página/aba                 | Divulgar ações e campanhas de doação, adoção, resgaste, saúde e bem-estar animal. Além de animais disponíveis para adoção e vagas para voluntariado |
|Lideres de Ongs e grupos protetores  | Ter acesso a dados básicos e de contato de outras instituições e empresas           | Estabelecer parcerias e receber doações               |
|Administradores de petshops e empresas pet       | Cadastrar minha empresa                 | Linkar dados de contato, redes sociais e endereçar o local de atuação |
|Administradores de petshops e empresas pet  | Editar minha página/aba           | Divulgar serviços, promoções e campanhas sociais oferecidas com suas respectivas datas e horários               |
|Administradores de petshops e empresas pet       | Ter acesso a dados básicos e de contato de outras instituições e empresas                 | Ter acesso a dados básicos e de contato de outras instituições e empresas       | Oferecer parcerias e campanhas de divulgação e colaboração mutua |
|Donos de clínicas veterinárias       | Clinica                 | Linkar dados de contato, redes sociais e endereçar o local de atuação |
|Donos de clínicas veterinárias  | Editar minha página/aba           | Divulgar os serviços oferecidos, com suas datas valores e horários               |
|Donos de clínicas veterinárias       | Ter acesso a dados básicos e de contato de outras instituições e empresas                 | Ter acesso a dados básicos e de contato de outras instituições e empresas       | Oferecer parcerias e campanhas de divulgação e colaboração mutua |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | Responsável |
|------|-----------------------------------------|----| ----|
|RF-001| Registro De Usuário | ALTA | PROGRAMADOR |
|RF-002| Perfil De Usuário Comum ou Administrador   | ALTA | PROGRAMADOR |
|RF-003| Modulo de doações | ALTA | PROGRAMADOR |
|RF-004| Gerenciamento de parceiros   | MÉDIA | PROGRAMADOR|
|RF-005| Busca de serviços e detalhes | ALTA | PROGRAMADOR |
|RF-006| Notificações   | MÉDIA | PROGRAMADOR |
|RF-007| Avaliações e Comentários dos Serviços | BAIXA | PROGRAMADOR |
|RF-008| Suporte ao usuário   | MÉDIA | PROGRAMADOR |
|RF-009| Mapa interativo | BAIXA | PROGRAMADOR |
|RF-010| Agendamentos online   | MÉDIA | PROGRAMADOR |
|RF-011| Fóruns de discussão | BAIXA | PROGRAMADOR |
|RF-012| Aba educacional com suporte em texto e vídeo   | BAIXA | PROGRAMADOR |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | ALTA | 
|RNF-002| Deve processar requisições do usuário em no máximo 5s |  MÉDIA |
|RNF-003| Acessibilidade | MÉDIA | 
|RNF-004| Segurança de dados |  ALTA | 
|RNF-005| O sistema deve deve realizar backups regulares | MÉDIA | 
|RNF-006| Deve permitir que o usuário faça a customização de seu perfil |  BAIXA | 
|RNF-007| O sistema deve eve permitir que usuarios possam compartilhar informações nas redes sociais | BAIXA | 
|RNF-008| Deve permitir que usuario escolha sua localização |  ALTA | 
|RNF-009| O sistema deve ter suporte a incremetos | ALTA | 
|RNF-010| O sistema deve ter robustez | MÉDIA | 
|RNF-011| O sistema deve ter a possibilidade de trabalhar integradamente a outro sistema |  ALTA | 




## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |



