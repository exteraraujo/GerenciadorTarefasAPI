# Gerenciador de Tarefas - API REST com Spring Boot

Este projeto é uma **API funcional em Java com Spring Boot**, desenvolvida para praticar conceitos de back-end e mostrar domínio de construção de APIs RESTful completas.

Ela permite:

- ✅ Criar tarefas
- 📋 Listar tarefas
- ✏️ Atualizar tarefas
- ❌ Deletar tarefas

A API segue os padrões do CRUD (Create, Read, Update, Delete).

---

## Como executar o projeto

1. Certifique-se de ter o **Java 17+** instalado.

2. Importe o projeto em uma IDE como o Eclipse ou IntelliJ.
   
3. Rode a aplicação com a classe principal:
@SpringBootApplication
public class GerenciadorTarefasApplication {
public static void main(String[] args) {
SpringApplication.run(GerenciadorTarefasApplication.class, args);
}
}

4. A API ficará disponível em:  
`http://localhost:8081/tarefas`

---

## Estrutura do Projeto
src/
└── main/java/
│ └── com.ester.gerenciador/
│ └── GerenciadorTarefasApiApplication.java/
│ ├── controller/
│ │ └── TarefaController.java
│ ├── model/
│ │ └── Tarefa.java
│ ├── repository/
│ │ └──  TarefaRepository.java
│ ├── service
│   └── TarefaService.java
└── resources/
  └── application.properties
└── test/java
└── JRE System Library
└── Mavem Dependencies
└── src/pom.xml

---

## 🔌 Endpoints disponíveis

### 🔹 Criar Tarefa – POST
- **URL:** `http://localhost:8081/tarefas`
- **Método:** POST  
- **Corpo JSON:**
```json
{
  "descricao": "Terminar Projeto Gerenciador de Tarefas",
  "concluida": false
}
<img width="1269" height="697" alt="image" src="https://github.com/user-attachments/assets/b4ffe275-3a5d-43d8-82e8-489f4523cd6c" />´´´
