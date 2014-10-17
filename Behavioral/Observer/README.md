# Observer

## Propósito

Implementar um comportamento publicar/subscrever a um objeto. Sempre que um  
objeto "Subject" ("Assunto") muda seu estado, os "Observers" ("Observadores") 
anexos serão notificados. Isso é usado para diminuir a quantidade de objetos 
acoplados e proporcionar baixo acoplamento

## Exemplos

* Um sistema de fila de mensagem é "observado" para mostrar o progresso de um 
job em uma GUI

## Nota

PHP já define 2 interfaces que podem ajudar a implementar esse padrão: SplObserver and SplSubject.

## Diagrama UML

![Alt Observer UML Diagram](uml/uml.png)
