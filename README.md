# cadastro_v1
Pagina de cadastro armazenando os dados em um banco de dados e exibindo 

io.github.joaomgsa.dao: Pacote que armazena as classes referentes à persistência de dados baseada no padrão Data Access Object;

io.github.joaomgsa.domain: Classe de domínio (modelo) da aplicação, a qual recebe o mapeamento objeto relacional por anotações; 

io.github.joaomgsa.cadastro.web.controller:pacote com as classes que representam os controllers no padrão MVC;

io.github.joaomgsa.cadastro.web.conversor: Classes para realizar a conversão de tipos de dados entre recursos utilizados na view e no controller;

src/main/resources: Arquivo de propriedades que contém as mensagens de validação do Bean Validation;

/webapp/WEB-INF/resources: É nesta pasta que adicionamos os arquivos estáticos, como CSS, JS ou imagens. Aqui temos também o script SQL com a base de dados MySQL que deve ser importada no SGDB;

/webapp/WEB-INF/views:Páginas web da aplicação;

pom.xml: Configurações do Maven para gerenciamento das dependências e build.
