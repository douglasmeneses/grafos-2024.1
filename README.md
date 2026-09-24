# 🕸️ Estruturas de Dados em Grafos — 2024.1

![Java](https://img.shields.io/badge/Java-11%2B-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Algorithms](https://img.shields.io/badge/Teoria_dos_Grafos-Estrutura_de_Dados-blue?style=for-the-badge)

Projeto acadêmico com foco na modelagem, construção e manipulação de **Estruturas de Dados de Grafos** em **Java**, desenvolvido para a disciplina de Teoria dos Grafos (período 2024.1). O projeto explora a implementação de nós, conexões, listas de adjacência e percursos fundamentais.

---

## 📌 Conteúdo Implementado

- 🔵 **Vértices & Arestas:** Definição das classes `Vertice` e `Aresta` com suporte a identificadores e pesos.
- 🗺️ **Modelagem de Grafos:** Classe `Grafo` com inserção dinâmica de nós, criação de conexões direcionadas e não-direcionadas.
- 📊 **Consultas Estruturais:** Métodos para verificação de vizinhança, grau de incidência e validação de caminhos.
- 🚀 **Simulação:** Ponto de entrada (`Main.java`) exemplificando montagem de redes e validação dos algoritmos.

---

## 🏗️ Estrutura do Projeto

```text
src/app/
├── Aresta.java        # Representação de aresta (origem, destino e peso)
├── Grafo.java         # Estrutura do grafo e operações principais
├── Vertice.java       # Representação de vértice/nó do grafo
└── Main.java          # Demonstração e testes de execução
```

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** [Java](https://www.oracle.com/java/) (Java 11 ou superior)
- **Paradigma:** Orientação a Objetos e Algoritmos de Grafos

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
- [JDK 11](https://adoptium.net/) ou superior instalado

### 1. Clonar o repositório
```bash
git clone https://github.com/douglasmeneses/grafos-2024.1.git
cd grafos-2024.1
```

### 2. Compilar e executar via terminal
```bash
javac -d bin src/app/*.java
java -cp bin app.Main
```

---

## 👨‍💻 Autor

Desenvolvido por **Douglas Meneses**.

- 💼 GitHub: [@douglasmeneses](https://github.com/douglasmeneses)
- ✉️ Email: [meneses.doug@gmail.com](mailto:meneses.doug@gmail.com)
