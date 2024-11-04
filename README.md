# Projeto de Estudo - Eureka Server

Este projeto é um estudo sobre o uso do Eureka Server no ecossistema Spring Cloud, configurado com Kotlin e Spring Boot. O Eureka Server é um serviço de registro e descoberta de serviços que facilita a comunicação e o balanceamento de carga entre microsserviços.

## Pré-requisitos

- **JDK 21**: Este projeto utiliza Java 21. Certifique-se de que a versão correta do JDK está instalada.
- **Kotlin 1.9.25**: Utilizamos a versão 1.9.25 do Kotlin.
- **Spring Boot 3.3.5**: O projeto é baseado no Spring Boot 3.3.5.
- **Spring Cloud 2023.0.3**: A versão do Spring Cloud utilizada para integração com o Eureka Server é a 2023.0.3.

## Configuração do Projeto

O projeto está configurado com Gradle como sistema de build e utiliza a estrutura de plugins e dependências necessárias para o funcionamento do Eureka Server. Abaixo estão os plugins e dependências principais do projeto.

### Plugins

- **Kotlin JVM**: `kotlin("jvm")` - para compilação do código Kotlin na JVM.
- **Kotlin Spring**: `kotlin("plugin.spring")` - para melhor integração com o Spring.
- **Spring Boot**: `org.springframework.boot` - gerenciamento das dependências do Spring Boot.
- **Spring Dependency Management**: `io.spring.dependency-management` - para facilitar a gestão de dependências do Spring.

### Dependências

As principais dependências do projeto são:

- `org.springframework.cloud:spring-cloud-starter-netflix-eureka-server`: Biblioteca necessária para configurar o Eureka Server.
- `org.jetbrains.kotlin:kotlin-reflect`: Recurso para reflexão em Kotlin, necessário para o Spring.
- **Dependências de Teste**:
  - `org.springframework.boot:spring-boot-starter-test`: Starter para testes no Spring Boot.
  - `org.jetbrains.kotlin:kotlin-test-junit5`: Suporte para testes usando JUnit 5 em Kotlin.

O projeto também usa o JUnit Platform Launcher para execução de testes.

## Executando o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
2. **Compilando o projeto**:
   ```bash
    ./gradlew bootRun
3. **Acessando o Eureka Server**:
    ```bash
    http://localhost:8761

## Estrutura de Código
O projeto está organizado para demonstrar o funcionamento básico do Eureka Server, com foco em sua configuração e funcionamento como serviço de registro e descoberta em ambientes de microsserviços.

## Contribuições
Este é um projeto de estudo, mas sinta-se à vontade para sugerir melhorias ou enviar pull requests.
