# O DESAFIO

Trabalho final - AWS

# EXECUTAR APLICAÇÃO

git clone https://gitlab.com/mathssilvan/championship_management.git

mvn install

java -jar target/championship_management-0.0.1-SNAPSHOT.jar

# EXECUTAR TESTE UNITARIO

mvn test

# ACESSAR ENDPOINTS PELO SWAGGER

http://localhost:8080/swagger-ui.html#/

# ACESSAR BASE DE DADOS

http://localhost:8080/h2/

username=spring

password=spring

# PARA CRIAÇÂO DE NOVOS ENDPOINTS SEGUROS

para que o novo endPoint seja protegido bastar passar o paramentro

@SecurityRequirement(name = "finalaws")

segue login e senha para acesso dos endpoints: 

Login: finalAWS
Senha: admin