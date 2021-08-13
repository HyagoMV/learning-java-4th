https://www.oreilly.com/library/view/learning-java-4th/9781449372477/ch01s04.html

# JDK
- inclui o compilador, 
- inclui o interpretador e
- inclui outras ferramentas

# Convenções de Codificação
- thisIsAVariable
- thisIsAMethod()
- ThisIsAClass
- THIS_IS_A_CONSTANT

# Java
- Java é uma linguagem compilada e interpretada
- O código-fonte Java é transformado em instruções para uma máquina virtual
- Java é compilado para bytecode e executado por um interpretador em um ambiente seguro chamado Java Runtime
- O mesmo bytecode Java pode ser executado em qualquer plataforma que forneça um ambiente de Java Runtime
- Java possui classes com métodos que são dependentes da plataforma
- Esses métodos nativos servem como o gateway entre a máquina virtual Java e o plataforma subjacente
- Segura:
    - Verificação de bytecode

# JIT
- Compilador dinâmico
- Compila o bytecode para o código de máquina nativo 
- Vantagens
    - Melhora o desempenho
    - Mantém a portabilidade e a segurança
- Desvantagens
    - A compilação leva tempo

# JVM
- Modo Client:
    - Ênfase no Tempo de inicialização rápida 
- Modo Server:
    - Ênfase na Economia de memória e no desempenho

---

# HotSpot
- Interpretador de bytecode Java
- Realiza a compilação adaptativa
- Monitora o código em execução para saber quais são as seções de códigos executadas com maior frequência
- Compila essas seções de códigos para código de máquina nativo 
- Otimiza o código de máquina nativo recem compilado
- As demais seções de código permanecem sendo interpretadas - economizando tempo e memória

---

# Classe
- As classes são localizadas e carregadas dinamicamente conforme são requisitacas pelo aplicativo

---


- A classe é o bloco de construção fundamental da Orientaçã a Objeto
- Uma classe representa algo concreto ou algo abstrato
- Uma classe contém declarações de variáveis e declarações de funções
- A classe é usada para construção de um objeto
