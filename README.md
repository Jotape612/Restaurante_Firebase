# Restaurante-final
Projeto final dedicado ao curso de ADS na materia de Desenvolvimetno de Sistemas (Web).

**GEN - PIZZARIA GENÉRICA**

A Gen é uma pizzaria inovadora que busca combinar a tradição das receitas italianas com a modernidade de um sistema de gerenciamento digital. Criada para atender tanto os clientes quanto os administradores de forma eficiente e prática, a Gen é mais do que apenas um restaurante; ela é uma experiência gastronômica com tecnologia integrada.

No mundo dinâmico de hoje, as pizzarias enfrentam desafios como a organização de pedidos, gerenciamento de reservas e feedback de clientes. A Gen resolve essas questões com um sistema moderno, intuitivo e escalável que facilita o controle do dia a dia do negócio.

**PROPÓSITO**
A Gen foi projetada para ser uma solução inteligente e acessível, proporcionando uma gestão completa e integrada que ajuda pizzarias de pequeno e médio porte a crescerem e entregarem experiências melhores aos seus clientes.

**WIREFRAMES**
Cinco telas foram criadas: tela inicial (com header, home, menu, avaliação e footer), a página matriz do projeto onde o usuario será redirecionado para as outras; uma página carrinho, com relação no firestore; login e cadastro, para autenticação dos usuarios.

**EXPLICAÇÃO DE CÓDIGO**
A partir da criação do site, utilizando HTML, CSS e o JS, foi necessario vincular ele ao node.js, consequentemente o express.js com intuito de criar rotas para facilitar o caminho das wireframes. Assim que esse processo foi completo, a instalação e vinculação do firebase foi necessaria.

O Firebase foi utilizado, principalmente, para que o site pudesse fazer o reconhecimento dos usuarios logados, com o authentication, gerenciamento, exclusão e acrescimo de pratos, utilizando o firestore, e a partir disso o backend do projeto estará implementado.

**FUNCIONALIDADES TECNICAS (FIREBASE)**
A estrutura do BD foi: Coleções (pratos, pedidos, usuarios), CRUD (Inserção, atualização e exclusão de dados), Firebase Authentication, Login com email e senha. As Rotas no Backend: GET /pratos (Lista todos os pratos), POST /pedidos (Cria um novo pedido), PUT /pedidos/:id (atualizar o status) e DELETE /pratos/:id (remover).

**DESAFIOS ENFRENTADOS**
Para mim, os principais desafios enfrentados foi, inicialmente, vincular o firebase ao projeto. Por terem videos um pouco mais antigos, coisa de 2 a 4 anos, pegar a base do projeto em tutorial e aplicar ao meu próprio foi um verdadeiro desafio. Gerenciamento de estoque, com as rotas Backend, foi algo que demandou muito atenção mas, infelizmente, não foi algo que consegui entregar ao código como gostaria, dependendo de uma base do projeto menos compativel com a ideia que foi requisitada. Por fim, a interface responsiva que muitas vezes quebrada com o decorrer do projeto.

**CONCLUSÃO**
Apesar de ser dificil, e não ter aplicado 100% do que foi solicitado, o projeto trouxe uma grande experiência e inovação, podendo ser replicado em futuros projetos e, principalmente, do próprio curso. A experiência de mexer com o firebase foi interessante e, sem sombra de dúvidas, será utilizado futuramente. Por outro lado, ainda me falta um pouco de conhecimento em como, e porquê, utilizar o node.js/express.js - embora tenha entendido sua ideia, como usa-lo em projetos futuros será uma nova etapa de recolhimento de informações e estudos. 

Futuramente pretendo retornar ao projeto, finalizando o backend para os pratos, adicionando pagamentos online e melhorar o sistema de notificação para usuarios/administradores.

**REFERENCIAS**
Para entender a base do firebase, mas sem sucesso em aplicar no projeto:
https://www.youtube.com/watch?v=oFp7twsVEiE

Introdução e implementação do firebase no projeto:
https://www.youtube.com/watch?v=NZzekYgLYdg

Documentação oficial do firebase
https://firebase.google.com/docs/web/setup?hl=pt-br
