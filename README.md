📘 Sistema de Cadastro de Alunos com Java, JPA e Banco de Dados
Este projeto é uma aplicação web desenvolvida em Java que realiza operações de cadastro, listagem e remoção de registros de alunos. Utiliza a especificação JPA (Java Persistence API) para gerenciar a persistência dos dados em um banco relacional, sendo compatível com H2 ou MySQL. O sistema é ideal para fins acadêmicos e demonstra o uso de arquitetura MVC com Front Controller.
🚀 Como usar:
1. Extraia o arquivo ZIP
Após o download, extraia o conteúdo para uma pasta de sua preferência.

2. Abra o projeto no NetBeans
Recomenda-se usar o NetBeans IDE 17 com suporte a Java EE.

3. Configure o banco de dados
Para H2: a configuração já está pronta para uso com banco em memória.

Para MySQL: ajuste as credenciais no arquivo persistence.xml.

4. Execute o projeto
Inicie o servidor integrado (como GlassFish ou Payara) e acesse via navegador.

🛠 Tecnologias Utilizadas
Java (JDK 17): Linguagem de programação principal.

JPA (Jakarta Persistence): API de persistência de dados.

NetBeans IDE 17: Ambiente de desenvolvimento.

Banco de Dados H2/MySQL: Armazenamento das entidades.

Servlets: Controladores da aplicação (padrão Front Controller).

JSP: Camada de visualização (View).

HTML/CSS: Estrutura e estilo das páginas.

🎯 Objetivos do Projeto
Implementar operações de CRUD (Create, Read, Update, Delete) para entidades Aluno.

Demonstrar o uso da JPA com banco de dados relacional.

Aplicar arquitetura MVC com Servlet como Front Controller.

Permitir fácil adaptação para outras entidades ou bancos.

📊 Resultados esperados
Cadastro eficiente de alunos com validação de dados.

Visualização clara da lista de alunos cadastrados.

Remoção segura e eficaz de registros.

Banco de dados funcionando com persistência confiável.
