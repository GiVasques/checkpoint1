# Checkpoint 1

Código do 1º checkpoint da disciplina de *Microservice and Web Engineering.*

## Informações 

**Nome:** Giovanna Vasques Alexandre

**Turma:** 2SIR

## Descrição do Projeto - Parte 1

Criação de API para responder requisições HTTP ``(POST, GET, DELETE e PUT)``:

- Criar Paciente ``(POST)``;
- Atualizar Paciente ``(PUT)``;
- Deletar Paciente ``(DELETE)``;
- Buscar Paciente por Id ``(GET)``;
- Buscar todos os Pacientes ``(GET)``;

## Classes criadas

### Model

Para mapeamento de entidades do banco de dados.

### Controller

Gerencia as requisições HTTP direcionando-as para os serviços adequados.

### DTO

Transporta dados entre camadas de aplicação.

### Service

Contém a lógica de negócio.

## Instalação

- Configuração do Swagger
    - https://springdoc.org/properties.html

- application.properties
    
    ```
    spring.application.name=checkpoint1
    springdoc.swagger-ui.path=/
    ```

## Navegação

### Executar a API
- *Executando* **Maven**

    mvn spring-boot:run

### Documentação API (swagger)
	
- http://localhost:8080/swagger-ui/index.html

## Referencias

https://springdoc.org/
