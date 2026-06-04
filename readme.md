# 🗳️ Sistema de Votação - Linguagens de Programação

Um sistema interativo de votação que coleta preferências de linguagens de programação e exibe o resultado consolidado das votações.

## 📋 Descrição

Este programa implementa uma pesquisa de votação simples onde **3 usuários** podem votar em sua linguagem de programação favorita entre as opções disponíveis. Após coletar todos os votos, o sistema exibe um relatório com a contagem de votos para cada linguagem.

## 🎯 Funcionalidades

- ✅ Coleta de dados do votante (nome)
- ✅ Votação em linguagens de programação (C++, Java, Python)
- ✅ Armazenamento de votos em estrutura de dicionário
- ✅ Contagem automática de votos por linguagem
- ✅ Exibição de resultado consolidado

## 🚀 Como Usar

### Pré-requisitos
- Python 3.x instalado

### Executando o programa

```bash
python main_sistema.py
```

### Exemplo de Execução

```
Informe o seu nome: João
Informe a linguagem de programação dentre as opções (1) C++ - (2) Java - (3) Python
Digite a sua opção (1, 2 e 3): 3

Informe o seu nome: Maria
Informe a linguagem de programação dentre as opções (1) C++ - (2) Java - (3) Python
Digite a sua opção (1, 2 e 3): 1

Informe o seu nome: Pedro
Informe a linguagem de programação dentre as opções (1) C++ - (2) Java - (3) Python
Digite a sua opção (1, 2 e 3): 3

{'João': 'Python', 'Maria': 'C++', 'Pedro': 'Python'}

 RESULTADO
C++: 1
Java: 0
Python: 2
```

## 📚 Conceitos Abordados

- **Estruturas de Dados**: Dicionários em Python
- **Laços de Repetição**: `for` para iteração
- **Entrada de Dados**: `input()` para coleta de dados
- **Lógica Condicional**: `if/elif/else` para validação
- **Manipulação de String**: Conversão e concatenação

## 🔧 Estrutura do Código

```python
# 1. Coleta de votos (loop de 3 iterações)
# 2. Armazenamento em dicionário
# 3. Contagem por linguagem
# 4. Exibição do resultado
```

## 📝 Autor

**Matheus Lopes**

---

*Prática de Algoritmos e Estrutura de Dados - PUC Minas*