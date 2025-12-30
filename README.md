
# Challenge ONE Literalura

Bem-vindo(a) ao **Challenge ONE Literalura**!  
Este é um projeto Java desenvolvido como parte do *Challenge ONE*, com o objetivo de aplicar conceitos fundamentais de Java, consumo de APIs, organização de código e uso do Maven para gerenciamento de dependências.

---

## 📌 Sobre o Projeto

O **Literalura** é uma aplicação Java criada como desafio educacional, focada na prática de:

- Programação orientada a objetos
- Consumo de APIs externas
- Manipulação e persistência de dados
- Organização de projetos Java com Maven

O projeto segue boas práticas de estruturação de código e separação de responsabilidades.

Repositório oficial:  
https://github.com/GermanoMacieira/Challenge_ONE_Literalura

---

## 📂 Estrutura do Projeto

O projeto segue o padrão de projetos Maven:

```
├── .mvn/                   # Maven Wrapper
├── src/
│   ├── main/
│   │   ├── java/           # Código-fonte da aplicação
│   │   └── resources/      # Arquivos de configuração
│   └── test/
│       └── java/           # Testes automatizados
├── .gitattributes
├── .gitignore
├── mvnw                    # Maven Wrapper (Linux/Mac)
├── mvnw.cmd                # Maven Wrapper (Windows)
└── pom.xml                 # Configuração do Maven
```

---

## 🛠 Tecnologias Utilizadas

- **Java 21**
- **Spring Boot**
- **JPA**
- **Maven**
- **Jackson** (serialização e desserialização JSON)
- **Utilização de PostgreSQL**

---

## 🚀 Como Executar o Projeto

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/GermanoMacieira/Challenge_ONE_Literalura.git
cd Challenge_ONE_Literalura
```

### 2️⃣ Compilar o projeto

```bash
./mvnw compile
```

No Windows:

```bash
mvnw.cmd compile
```

### 3️⃣ Executar a aplicação

Se for um projeto Spring Boot:

```bash
./mvnw spring-boot:run
```

Caso seja uma aplicação Java padrão:

```bash
./mvnw package
java -jar target/*.jar
```

---

## 📦 Gerenciamento de Dependências

Todas as dependências do projeto estão configuradas no arquivo `pom.xml`.  
O Maven realiza automaticamente o download das bibliotecas necessárias.

Principais dependências:
- Jackson (JSON)
- JPA
- PostgreSQL

---

## 📖 Funcionalidades

- Consumo de dados de uma API pública de livros
- Conversão de dados JSON para objetos Java
- Exibição e manipulação das informações no console
- Organização do código seguindo boas práticas

---

## 🤝 Contribuições

Contribuições são bem-vindas!

1. Faça um fork do projeto
2. Crie uma branch para sua feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Commit suas alterações
4. Envie um Pull Request

---

## 📝 Licença

Este projeto pode ser utilizado para fins educacionais.  
Sinta-se à vontade para adicionar uma licença, como MIT, caso deseje reutilização aberta do código.

---

## 👤 Autor

**Germano Macieira**

Projeto desenvolvido como parte do aprendizado prático em Java no programa **ONE - Oracle Next Education**.
