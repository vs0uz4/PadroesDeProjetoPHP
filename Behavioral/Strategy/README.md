# Strategy

## Terminologia

* Context (Contexto)
* Strategy (Estratégia)
* Concrete Strategy (Estratégia Concreta)

## Propósito

Separar estratégias e permitir uma troca rápida entre elas. Esse padrão também 
é uma boa alternativa a herança -- não é preciso ter uma classe abstrata que é 
estendida.

## Exemplos

* Ordenar uma lista de objetos, uma estratégia por data, outra por ID
* Simplificar teste unitário: alternar entre armazenado em arquivo e em memória

## Diagrama UML

![Alt Strategy UML Diagram](uml/uml.png)
