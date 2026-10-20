# TOC Playground — Interactive Theory of Computation

An interactive web-based learning platform designed to make abstract concepts of **Theory of Computation (TOC)** easier to understand through visual explanations, experimentation, and simulations.

## 📌 About the Project

Theory of Computation involves mathematical concepts such as formal languages, automata, and computational models. These concepts can be difficult to visualize when learned only through textbooks, equations, and static diagrams.

To address this learning challenge, we developed **TOC Playground**, an interactive educational website that allows students to explore concepts, experiment with inputs, and observe how theoretical rules work in practice.

The project currently focuses on two major topics:

1. Pumping Lemma
2. Pushdown Automata (PDA)

---

## 1. Pumping Lemma

### What is it?

The Pumping Lemma is a theoretical tool used to study properties of formal languages. It provides conditions that strings in certain infinite languages must satisfy when divided into specific parts.

For context-free languages, the pumping lemma uses a decomposition of the form:

**s = uvwxy**

The decomposition must satisfy conditions involving the lengths of the selected parts and the ability to pump particular substrings while remaining in the language.

### Problem Statement / Question Given

**[Insert the exact Pumping Lemma question provided in the assignment or by the faculty here.]**

### Our Innovation

Instead of presenting the Pumping Lemma only through mathematical expressions and written proofs, we created an interactive simulator that allows students to:

- Enter a string and pumping length.
- Divide the string into the parts u, v, w, x, and y.
- Change the pumping value *i* and observe the resulting string.
- Check whether the decomposition satisfies the required conditions.
- Compare pumped strings and determine whether they belong to the target language.
- View a summary explaining which conditions pass or fail.

### Why We Built It

The goal was to make the relationship between string decomposition, pumping conditions, and language membership easier to understand. Students can experiment with different inputs and learn from invalid decompositions as well as valid ones.

---

## 2. Pushdown Automata (PDA)

### What is it?

A Pushdown Automaton is a computational model similar to a finite automaton, but with an additional memory structure called a **stack**. The stack allows it to recognize certain context-free languages that finite automata cannot recognize.

A PDA operates through states, input symbols, stack operations, and transition rules.

### Problem Statement / Question Given

**[Insert the exact PDA question or exercise provided in the assignment or by the faculty here.]**

### Our Innovation

We aim to make PDA execution easier to visualize through an interactive simulator that demonstrates how states, input symbols, and stack operations work together.

The PDA section is intended to help students:

- Understand state transitions.
- Observe stack push and pop operations.
- Trace how an input string is processed.
- Understand the role of the stack during computation.
- Follow the execution of a PDA step by step.

### Why We Built It

PDA transitions can be challenging to follow when represented only through transition tables or state diagrams. Our approach focuses on visualizing the execution process so that students can better understand how a PDA processes an input and reaches an accepting or rejecting outcome.

---

## 💡 What Makes This Project Different?

TOC Playground focuses on **learning by experimentation rather than memorization**.

- Interactive inputs instead of static examples.
- Immediate feedback on conditions and results.
- Visual explanations of abstract computational concepts.
- Opportunities to explore valid and invalid cases.
- A student-friendly interface for independent practice.

The objective is to connect theoretical concepts with observable behavior, helping students build a stronger conceptual understanding of Theory of Computation.

## 🛠️ Technology Stack

- HTML — Page structure
- CSS — Styling and layout
- JavaScript — Interactive logic and simulations

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open the project folder.
3. Open the main HTML file in a web browser.
4. Navigate between the learning sections and experiment with the simulators.

No additional installation is required for the standalone HTML version.

## 🎯 Project Objective

To transform selected Theory of Computation concepts into interactive learning experiences that help students understand the underlying logic through exploration, visualization, and experimentation.

## 👩‍💻 Project Status

An educational prototype focused on the Pumping Lemma and Pushdown Automata, with scope for additional TOC concepts and learning activities.

