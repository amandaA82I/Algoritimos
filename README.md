# 🚀 FOUNDATIONAL LAB: Algoritmos e Pensamento Computacional
### Otimização e Estrutura de Software com Linguagem C

![C Language](https://img.shields.io/badge/Linguagem-C_(ISO_99)-00599C?style=for-the-badge&logo=c&logoColor=white)
![Focus](https://img.shields.io/badge/Foco-Performance_e_Alocação-2ecc71?style=for-the-badge)
![Semestre](https://img.shields.io/badge/Semestre-1º_ADS-8e44ad?style=for-the-badge)

---

## 🔬 O que foi construído neste Módulo?

Este módulo estabeleceu os pilares da Ciência da Computação, movendo o foco da "escrita de código" para a **"engenharia de soluções"**. O objetivo foi dominar como o computador *pensa* e *gerencia* recursos.

> **Resultados Chave:** Domínio de **Modularização**, **Alocação Dinâmica de Memória** e **Análise de Complexidade de Algoritmos**.

---

## 🛠 Kit de Ferramentas e Conceitos

Aqui estão as ferramentas e os conceitos avançados que foram aplicados nos projetos para garantir eficiência e organização:

### ⚙️ Stack & Ferramentas
| Ferramenta | Descrição | Badge |
| :--- | :--- | :--- |
| **Linguagem C** | Padrão ISO 99 para controle de baixo nível. | ![C](https://img.shields.io/badge/C_(Standard_99)-00599C?style=flat-square&logo=c&logoColor=white) |
| **GCC** | Compilador padrão para otimização de código. | ![GCC](https://img.shields.io/badge/GCC_Compiler-D22128?style=flat-square&logo=gnu&logoColor=white) |
| **VS Code** | IDE utilizada para desenvolvimento e debugging. | ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white) |

### 🧠 Princípios de Engenharia Aplicados

```c
// Principais blocos de aprendizado, essenciais para Clean Code e Performance:

// 1. Otimização de Memória
void alocacao_dinamica() {
    // Gerenciamento explícito de Stack vs. Heap.
    TipoDados* ponteiro = (TipoDados*)malloc(sizeof(TipoDados));
    if (ponteiro != NULL) {
        // Uso de Pointers e Structs para dados estruturados.
        // ...
        free(ponteiro); // Garantindo zero memory leaks.
    }
}

// 2. Análise Assintótica
// Foco em performance: Evitando complexidade O(N^2) sempre que possível.
// Medindo o tempo de CPU com <time.h> para benchmarks.
const char* complexidade_bubble = "O(N^2)"; 
📂 Vitrine de Projetos (Destaques de Performance)ProjetoDestaque TécnicoLink para o Código⭐ Calculadora Científica ModularModularização Avançada, Structs, e Malloc. Um software com 27 operações (incluindo Matrizes e Bhaskara), usando Persistência em CSV para histórico.Acessar Arquivos📉 Análise de Algoritmos (Bubble Sort)Estudo prático da Complexidade $O(N^2)$. O projeto mede o tempo de CPU (clock()) para provar o trade-off de performance de algoritmos não-otimizados.Acessar ArquivosCálculo de Média EscolarDemonstração de Lógica Condicional (if/else) e tratamento de entrada/saída (stdio.h).Acessar Arquivos💡 Key Takeaways (Aprendizados Essenciais)Ponteiros e Malloc/Free: Dominar a Alocação Dinâmica para controle fino da memória (Heap), fundamental para evitar memory leaks em C.Modularidade: Aplicação de Princípio da Responsabilidade Única, dividindo o código em funções (.c e .h) para reutilização e fácil manutenção.Persistência de Dados: Implementação de um File System simples para que os programas possam salvar e carregar dados (CSV/Textos) após a execução.Pensamento Crítico: Não apenas programar, mas saber justificar a escolha de um algoritmo em função da sua complexidade e escalabilidade.
## ✨ Resumo das Alterações Criativas:

1.  **Título e Subtítulo Impactantes:** O nome "FOUNDATIONAL LAB" e o subtítulo com foco em "Otimização" dão um toque mais profissional e acadêmico ao repositório.
2.  **Bloco de Código:** O uso do bloco de código estilizado para os "Princípios de Engenharia" é uma forma muito criativa de destacar termos como `malloc`, `free`, e `O(N^2)` diretamente no README.
3.  **Vitrine de Projetos:** A tabela está mais limpa e focada no **benefício técnico** de cada projeto (ex: *Modularização Avançada*).
4.  **Key Takeaways:** Lista de aprendizados mais robusta, usando terminologia de engenharia de software (*Princípio da Responsabilidade Única*, *trade-off*).

Este formato é excelente para impressionar quem busca desenvolvedores com fortes fundamentos!

Você precisa de ajuda para encontrar os caminhos exatos dos links (`[Acessar Arquivos](./)
