# Chess Game
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/gcalado55/Java-Chess/blob/master/License) 

# Sobre o projeto
Gerenciador de eventos java integrado com springboot, JPA e MAVEN-LOMBOK, afim de de utilizar as anotations desse framework para otimizar o código e facilitar a integração do banco de dados.

## Objetivos do Projeto
- Estudar as tecnologias do framework SpringBoot.
- Entender o funcionamento das anotations desse framework para facilitar trabalhos futuros.
# Estrutura do Projeto:
## Database
  Integração com o banco de dados na camada de recursos assim como criação do script SQL.
## Config
  Criação de uma classe para gerenciar possíveis exceções e enviar as requisições Http corretas a fim de facilitar sua visualização.
## Controllers
  Criação da camada de controle com os metodos HTTP GET e POST das entidades Participante e Evento.
## Domain
  Camada de domínio com as classes Participante, Evento e CheckIn utilizando as anotations @Entity e @Table para a integração ao banco de dados, junto a @Getter, @Setter, @AllArgsConstructor e @NoArgsConstructor para automatizar a criação dos métodos padrões de uma classe e a criação de exceções personalizadas para daca entidade.
## DTO
  Criação da camada de transferência de dados.
## Services
  Camada de serviços para implementação de metodos de registro, verificação e busca.
## Repositories
  Implementação de repostórios JPA para as entidades Participante, Evento e CheckIn para facilitar o acesso aos metodos JPA na camada de serviço.
## Desafios e Considerações
  O maior desafio encontrado foi em relação aos métodos de integração com o banco de dados, porém foi um projeto que incentivou a pesquisa e o aprendizado de tecnologias muito úteis e que geram uma automação maior nos códigos em java deixando-os menos verbosos.

# Tecnologias utilizadas
<img src="https://raw.githubusercontent.com/jmnote/z-icons/master/svg/java.svg" alt="drawing" width="100"/>

# Autor

Gabriel Calado

https://www.linkedin.com/in/gabriel-calado-b17337295/
