# Restaurante-Final

Projeto final desenvolvido para o curso de **ADS** na matéria de **Desenvolvimento de Sistemas (Web)**.

---

## **GEN - PIZZARIA GENÉRICA**

A **Gen** é uma pizzaria que une a tradição das receitas italianas à inovação tecnológica, oferecendo uma experiência prática e eficiente tanto para clientes quanto para administradores. Mais que um restaurante, é um exemplo de como a tecnologia pode transformar o setor gastronômico.

No cenário atual, pizzarias enfrentam desafios como organização de pedidos, gerenciamento de reservas e feedbacks de clientes. A **Gen** propõe um sistema digital moderno, intuitivo e escalável para solucionar essas dificuldades.

---

### **PROPÓSITO**
A **Gen** foi idealizada para ser uma ferramenta acessível e inteligente, ajudando pizzarias de pequeno e médio porte a se destacarem no mercado enquanto oferecem uma experiência única para seus clientes.

---

### **WIREFRAMES**
Foram projetadas cinco telas principais:  
1. **Tela Inicial**: Contém header, home, menu, avaliações e footer, com links para as demais páginas.  
2. **Página de Carrinho**: Integração com o Firestore para gerenciar os itens selecionados.  
3. **Login e Cadastro**: Utilizam o Firebase Authentication para autenticação segura.  

---

### **EXPLICAÇÃO DO CÓDIGO**
O site foi desenvolvido utilizando **HTML**, **CSS** e **JavaScript**. A integração com **Node.js** e **Express.js** permitiu a criação de rotas que conectam as wireframes de maneira eficiente. Após essa etapa, foi implementado o **Firebase**, com foco no:

- Reconhecimento de usuários logados por meio do **Authentication**.
- Gerenciamento de pratos e pedidos utilizando o **Firestore**.

---

### **FUNCIONALIDADES TÉCNICAS (FIREBASE)**

**Estrutura do Banco de Dados**  
- **Coleções**: Pratos, pedidos e usuários.  
- **Operações CRUD**: Inserção, atualização e exclusão de dados.  
- **Firebase Authentication**: Login com e-mail e senha.

**Rotas no Backend**
- **GET /pratos**: Lista todos os pratos.  
- **POST /pedidos**: Cria um novo pedido.  
- **PUT /pedidos/:id**: Atualiza o status do pedido.  
- **DELETE /pratos/:id**: Remove um prato do sistema.

---

### **DESAFIOS ENFRENTADOS**
1. **Integração do Firebase**: Muitos tutoriais disponíveis estavam desatualizados, tornando o processo desafiador.  
2. **Gerenciamento de Estoque**: Apesar de demandar atenção, a implementação completa ficou pendente devido à incompatibilidade com a abordagem inicial.  
3. **Interface Responsiva**: Garantir uma UI consistente foi um processo contínuo ao longo do desenvolvimento.

---

### **CONCLUSÃO**
Apesar dos desafios, o projeto proporcionou uma grande evolução técnica e prática. A experiência com o **Firebase** foi enriquecedora e será essencial em projetos futuros. Ainda há oportunidades de melhoria, especialmente no uso do **Node.js** e do **Express.js**, que exigem mais estudos e prática para aproveitamento pleno.

Planos futuros para o projeto incluem:  
- Finalização completa do backend para os pratos.  
- Integração de pagamentos online.  
- Notificações otimizadas para usuários e administradores.

---

### **REFERÊNCIAS**
- [Firebase - Autenticação de Usuários (YouTube)](https://www.youtube.com/watch?v=oFp7twsVEiE)  
- [Introdução e Implementação do Firebase (YouTube)](https://www.youtube.com/watch?v=NZzekYgLYdg)  
- [Documentação Oficial do Firebase](https://firebase.google.com/docs/web/setup?hl=pt-br)

--- 

Essa versão apresenta as informações de forma estruturada, clara e com destaque para os aspectos mais relevantes do projeto.
