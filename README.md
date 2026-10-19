# Segundo Cérebro com IA: Fundamentos do Java ☕

Este repositório contém a documentação do meu projeto de "Segundo Cérebro", desenvolvido com o Gemini Notebook (NotebookLM). O objetivo deste projeto é utilizar a Inteligência Artificial para organizar e interagir com fontes de estudo selecionadas por mim.

## 🎯 Tema e Objetivo
**Tema:** Fundamentos da linguagem Java.
**Objetivo:** Criar um assistente especializado nos fundamentos do Java para me auxiliar na compreensão da sintaxe, estruturas de controlo e nos pilares iniciais da Programação Orientada a Objetos, baseando-se em materiais didáticos confiáveis.

## 📚 Fontes Utilizadas e Critérios de Confiança
Para garantir que a IA me responda com precisão técnica e boa didática, selecionei apenas as seguintes fontes:
1. **Apostila "Java e Orientação a Objetos" (Caelum/Alura)** Escolhi este material porque é uma das referências mais consagradas e didáticas no Brasil para quem está a começar, com grande foco prático.
2. **Java Tutorials (Documentação Oficial da Oracle)** A documentação oficial da criadora da linguagem é a "fonte da verdade" indiscutível para a precisão técnica e compreensão de como a linguagem funciona na base.

## 🤖 Diretriz de Comportamento (Prompt)
Para alinhar o tom das respostas, configurei o notebook com a seguinte instrução:
> *"Comporte-se como um professor sénior de Java, explicando os conceitos para um iniciante de forma didática e baseada estritamente nestes documentos."*

## 💬 Interações e Citações
Aqui estão alguns exemplos das perguntas que fiz ao meu Segundo Cérebro e como ele respondeu com base nas fontes (os prints destas interações estão na pasta de imagens deste repositório):

* **Pergunta 1:** Como funciona o método main em Java?
* **Resumo da Resposta:** O método `main` funciona como o **ponto de entrada** (*entry point*) de uma aplicação Java tradicional. Ele é a "faísca" do programa: quando mandamos a Máquina Virtual do Java (JVM) executar uma classe, é exatamente por esse método que a execução começa.

Sua assinatura padrão é:

```java
public static void main(String[] args)
```

Cada palavra nessa linha tem uma função bem definida para que a JVM consiga rodar o código:

* **`public`**: É o modificador de acesso que torna o método visível e acessível de qualquer lugar. A JVM precisa que ele seja público para conseguir chamá-lo de fora da classe.
* **`static`**: Define que o método pertence à **classe** em si, e não a um objeto/instância específico. Isso permite que a JVM execute o método sem precisar instanciar a classe previamente com o operador `new`.
* **`void`**: É o tipo de retorno e significa "vazio". Ele indica que o método realiza suas tarefas e finaliza sem devolver nenhum valor para quem o chamou.
* **`main`**: É o nome exato que a JVM procura na classe principal. Se esse nome ou a estrutura do método estiverem incorretos, o sistema lança um erro e não executa a aplicação.
* **`String[] args`**: É um parâmetro contendo um vetor (array) de textos (`String`). Ele serve para receber dados ou parâmetros passados diretamente pela linha de comando/terminal no momento da inicialização do programa.

---

**Uma particularidade do ecossistema:**
No desenvolvimento Java padrão, a busca pelo método `main()` é obrigatória para iniciar um programa. No entanto, quando executamos código Java diretamente dentro do **Oracle Database** (Oracle JVM), o ponto de entrada não precisa ser obrigatoriamente chamado de `main()`; o banco permite chamar qualquer método estático publicado na classe carregada.

---

🚀 *Quer que eu mostre um exemplo prático de como passar e ler parâmetros dentro do vetor `String[] args` no terminal?*
* **Fonte citada:** [Insira o número da citação e de que fonte veio, ex: "Citação 2 - Apostila Caelum, página 15"]


## 🔗 Link do Notebook
https://notebook.google.com/notebook/5247fec3-6c74-4ae7-b0d1-85e3f934514e
