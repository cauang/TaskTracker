# 📝 Task Tracker CLI - Java

Uma aplicação de linha de comando (CLI) para gerenciamento de tarefas, desenvolvida em **Java puro**, sem bibliotecas externas. Ideal para praticar manipulação de arquivos, entrada via terminal e programação orientada a objetos.

---

## ✨ Destaques do Projeto

### ✅ Java puro, sem frameworks
Todas as funcionalidades foram implementadas usando apenas as bibliotecas nativas da linguagem Java — sem dependências externas.

### 🧠 Habilidades Demonstradas
- Programação orientada a objetos (POO)
- Manipulação de arquivos com `FileReader`/`FileWriter`
- Serialização e persistência manual em JSON
- Entrada e parsing de argumentos via linha de comando
- Tratamento de erros e casos limite (ex: arquivos inexistentes, IDs inválidos)

### 🔧 Funcionalidades
- Adicionar tarefas
- Atualizar e remover tarefas
- Marcar como "em progresso" ou "concluída"
- Listar todas as tarefas ou por status (`todo`, `in-progress`, `done`)
- Persistência em `tasks.json` criado automaticamente

---

## 🖥️ Como Usar

### 🔨 Compilar o Projeto

```bash
javac -d build src/*.java
cd build
jar cfe task-cli.jar TaskTracker *.class
```
### 
