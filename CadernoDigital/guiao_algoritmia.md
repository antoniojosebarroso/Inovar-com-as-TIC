# Guião - Fundamentos de Algoritmia
**Disciplina:** Algoritmia  
**Duração:** 2 aulas de 50 minutos cada  
**Público-alvo:** Estudantes iniciantes em programação  

---

## **AULA 1 - Linguagens Naturais vs Linguagens de Programação (50 min)**

### **Objetivos da Aula:**
- Distinguir linguagens naturais de linguagens de programação
- Compreender os conceitos de sintaxe e semântica
- Identificar as características específicas das linguagens de programação

### **Estrutura da Aula:**

#### **1. Introdução e Motivação (10 min)**
**Pergunta inicial:** "Como é que vocês comunicam com os vossos amigos? E como acham que podemos comunicar com um computador?"

**Atividade quebra-gelo:**
- Pedir aos alunos para darem uma instrução simples (ex: "vai buscar água")
- Mostrar como a mesma instrução pode ser interpretada de diferentes formas
- Introduzir a necessidade de precisão na comunicação com computadores

#### **2. Linguagens Naturais (15 min)**

**Definição e características:**
- **Linguagem:** Sistema de comunicação que permite expressar ideias, pensamentos e informações
- **Linguagens naturais:** Português, inglês, francês, etc.
- Características: flexibilidade, ambiguidade, evolução constante, contexto cultural

**Exemplos práticos:**
- "Banco" (instituição financeira vs. assento)
- "Manga" (fruto vs. parte da roupa)
- Expressões idiomáticas: "Está a chover a potes"

**Sintaxe vs Semântica nas linguagens naturais:**
- **Sintaxe:** Regras gramaticais (sujeito + predicado)
- **Semântica:** Significado das palavras e frases
- Exemplo: "As ideias verdes sem cor dormem furiosamente" (sintaticamente correto, semanticamente incorreto)

#### **3. Linguagens de Programação (20 min)**

**Definição e necessidade:**
- Linguagem formal para comunicar instruções precisas ao computador
- Eliminação de ambiguidades
- Precisão absoluta necessária

**Características fundamentais:**
- **Sintaxe rigorosa:** Regras muito específicas
- **Semântica clara:** Cada instrução tem significado único
- **Não há ambiguidade:** Uma instrução = uma interpretação
- **Vocabulário limitado:** Palavras-chave predefinidas

**Comparação prática:**
```
Linguagem Natural: "Soma estes números"
Linguagem de Programação: soma = numero1 + numero2
```

**Conceitos essenciais:**
- **Programa (código):** Conjunto de instruções escritas numa linguagem de programação
- **Instrução:** Comando individual que o computador consegue executar
- **Algoritmo:** Sequência lógica de passos para resolver um problema

#### **4. Atividade Prática (5 min)**
Exercício em pares: Transformar instruções em linguagem natural para "pseudo-código" mais preciso.

Exemplo:
- Natural: "Faz um bolo"
- Preciso: "1. Mistura farinha, ovos e açúcar; 2. Bate a mistura; 3. Leva ao forno 30 min a 180°"

---

## **AULA 2 - Gerações de Linguagens de Programação (50 min)**

### **Objetivos da Aula:**
- Conhecer a evolução histórica das linguagens de programação
- Classificar linguagens por gerações
- Identificar exemplos e características de cada geração

### **Estrutura da Aula:**

#### **1. Revisão e Ligação (5 min)**
- Recordar conceitos da aula anterior
- Pergunta: "Se as linguagens de programação evoluíram, como terão começado?"

#### **2. Evolução das Linguagens - Linha Temporal (10 min)**

**Contexto histórico:**
- Primeiros computadores (1940s): Muito básicos e complexos de programar
- Necessidade de facilitar a programação
- Aproximação gradual à linguagem humana

**Analogia:** "Como aprender a conduzir"
- 1ª geração: Construir o carro peça a peça
- 2ª geração: Usar ferramentas básicas
- 3ª geração: Carta de condução normal
- 4ª geração: GPS e assistências
- 5ª geração: Carro autónomo

#### **3. As 5 Gerações de Linguagens (30 min)**

##### **1ª Geração - Linguagem Máquina (1940s)**
**Características:**
- Código binário (0s e 1s)
- Comunicação direta com o processador
- Extremamente difícil de programar e debugar

**Exemplo:**
```
10110000 01100001
(Mover o valor 97 para o registo AL)
```

**Vantagens:** Execução muito rápida  
**Desvantagens:** Muito difícil de escrever e compreender

##### **2ª Geração - Linguagem Assembly (1950s)**
**Características:**
- Usa mnemónicos (palavras curtas) em vez de binário
- Correspondência direta 1:1 com linguagem máquina
- Necessita de assembler para converter para linguagem máquina

**Exemplo:**
```assembly
MOV AX, 5
ADD AX, 3
```

**Exemplos:** Assembly x86, MIPS Assembly  
**Vantagens:** Mais legível que linguagem máquina  
**Desvantagens:** Ainda muito técnico, específico para cada processador

##### **3ª Geração - Linguagens de Alto Nível (1960s-presente)**
**Características:**
- Sintaxe próxima da linguagem humana
- Independentes do hardware
- Um comando pode corresponder a várias instruções máquina

**Exemplo:**
```python
resultado = (a + b) * c
```

**Exemplos:** 
- **Procedurais:** C, Pascal, COBOL, FORTRAN
- **Orientadas a objetos:** Java, C++, Python, C#

**Vantagens:** Fáceis de aprender e usar  
**Desvantagens:** Menos controlo sobre o hardware

##### **4ª Geração - Linguagens Muito Alto Nível (1980s-presente)**
**Características:**
- Foco em "o quê" fazer, não em "como" fazer
- Ferramentas visuais e declarativas
- Orientadas para domínios específicos

**Exemplos:**
- **SQL:** `SELECT nome FROM alunos WHERE idade > 18`
- **MATLAB:** Computação científica
- **R:** Análise estatística
- **HTML:** Estruturação de páginas web

##### **5ª Geração - Linguagens de Inteligência Artificial (1990s-presente)**
**Características:**
- Baseadas em lógica e restrições
- Programação declarativa
- Sistemas especialistas

**Exemplos:**
- **Prolog:** Programação lógica
- **LISP:** Processamento simbólico
- **Linguagens para ML:** TensorFlow, PyTorch

#### **4. Atividade de Consolidação (5 min)**

**Jogo "Classificar a Linguagem":**
Apresentar linguagens e os alunos identificarem a geração:
1. `10110000 01100001` (1ª geração)
2. `MOV AX, 5` (2ª geração)  
3. `print("Olá mundo!")` (3ª geração)
4. `SELECT * FROM produtos` (4ª geração)
5. `rule(X) :- condition(X).` (5ª geração)

---

## **Recursos Necessários:**
- Computador com projetor
- Quadro/flip chart
- Exemplos de código em diferentes linguagens
- Ficha de exercícios (opcional)

## **Avaliação:**
- Participação nas discussões
- Correção dos exercícios práticos
- Mini-teste oral no final da segunda aula (opcional)

## **Trabalho de Casa/Extensão:**
- Pesquisar sobre uma linguagem de programação específica e identificar a sua geração
- Encontrar exemplos de como a mesma tarefa é realizada em diferentes gerações de linguagens

---

## **Notas para o Professor:**
- Ajustar exemplos conforme o nível da turma
- Usar analogias do quotidiano sempre que possível
- Incentivar perguntas e discussão
- Preparar exemplos adicionais caso a aula termine mais cedo
- Considerar mostrar código real em diferentes linguagens se houver tempo