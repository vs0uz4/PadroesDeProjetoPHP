# DesignPatternsPHP

Essa é uma coleção de Padrões de Projeto (Design Patterns) cnhecidos junto com 
exemplos de códigos mostrando como implementá-los em PHP. Cada Padrão tem uma 
pequena lista de exemplos (a maioria do Zend Framework, Symfony2 ou Doctrine2).

Provavelmente o maior problema com Padrões de Projeto é que frequentemente as 
pessoas os conhecem, mas não sabem quando aplicá-los.

## Padrões de Projeto

Os Padrões de Projeto podem ser estruturados em 3 categorias diferentes. Clique 
no [:notebook:](http://pt.wikipedia.org/wiki/Software_design) para uma 
explicação completa na Wikipedia -- sempre que possível em português, mas pode 
haver algumas em inglês.

### [Creacional](Creacional)

* [AbstractFactory](Creational/AbstractFactory) [:notebook:](http://pt.wikipedia.org/wiki/Abstract_Factory)
* [Builder](Creational/Builder) [:notebook:](http://pt.wikipedia.org/wiki/Builder)
* [FactoryMethod](Creational/FactoryMethod) [:notebook:](http://pt.wikipedia.org/wiki/Factory_Method)
* [Multiton](Creational/Multiton) (considerado um anti-pattern! :no_entry:)
* [Pool](Creational/Pool) [:notebook:](http://en.wikipedia.org/wiki/Object_pool_pattern)
* [Prototype](Creational/Prototype) [:notebook:](http://pt.wikipedia.org/wiki/Prototype)
* [SimpleFactory](Creational/SimpleFactory)
* [Singleton](Creational/Singleton) [:notebook:](http://pt.wikipedia.org/wiki/Singleton) (considerado um anti-pattern! :no_entry:)
* [StaticFactory](Creational/StaticFactory)

### [Estrutural](Estrutural)

* [Adapter](Structural/Adapter) [:notebook:](http://pt.wikipedia.org/wiki/Adapter)
* [Bridge](Structural/Bridge) [:notebook:](http://pt.wikipedia.org/wiki/Bridge_(padr%C3%A3o_de_projeto_de_software)
* [Composite](Structural/Composite) [:notebook:](http://pt.wikipedia.org/wiki/Composite)
* [DataMapper](Structural/DataMapper) [:notebook:](http://en.wikipedia.org/wiki/Data_mapper_pattern)
* [Decorator](Structural/Decorator) [:notebook:](http://pt.wikipedia.org/wiki/Decorator)
* [DependencyInjection](Structural/DependencyInjection) [:notebook:](http://en.wikipedia.org/wiki/Dependency_injection)
* [Facade](Structural/Facade) [:notebook:](http://pt.wikipedia.org/wiki/Fa%C3%A7ade)
* [FluentInterface](Structural/FluentInterface) [:notebook:](http://en.wikipedia.org/wiki/Fluent_interface)
* [Proxy](Structural/Proxy) [:notebook:](http://pt.wikipedia.org/wiki/Proxy_(padr%C3%B5es_de_projeto)
* [Registry](Structural/Registry) [:notebook:](http://en.wikipedia.org/wiki/Service_locator_pattern)

### [Comportamental](Comportamental)

* [ChainOfResponsibilities](Behavioral/ChainOfResponsibilities) [:notebook:](http://pt.wikipedia.org/wiki/Chain_of_Responsibility)
* [Command](Behavioral/Command) [:notebook:](http://pt.wikipedia.org/wiki/Command)
* [Iterator](Behavioral/Iterator) [:notebook:](http://pt.wikipedia.org/wiki/Iterator)
* [Mediator](Behavioral/Mediator) [:notebook:](http://pt.wikipedia.org/wiki/Mediator)
* [Memento](Behavioral/Memento) [:notebook:](http://pt.wikipedia.org/wiki/Memento_(inform%C3%A1tica))
* [NullObject](Behavioral/NullObject) [:notebook:](http://en.wikipedia.org/wiki/Null_Object_pattern)
* [Observer](Behavioral/Observer) [:notebook:](http://pt.wikipedia.org/wiki/Observer)
* [Specification](Behavioral/Specification) [:notebook:](http://en.wikipedia.org/wiki/Specification_pattern)
* [State](Behavioral/State) [:notebook:](http://pt.wikipedia.org/wiki/State)
* [Strategy](Behavioral/Strategy) [:notebook:](http://pt.wikipedia.org/wiki/Strategy)
* [TemplateMethod](Behavioral/TemplateMethod) [:notebook:](http://pt.wikipedia.org/wiki/Template_Method)
* [Visitor](Behavioral/Visitor) [:notebook:](http://pt.wikipedia.org/wiki/Visitor_pattern)

### [Mais](Mais)
* [Delegation](More/Delegation) [:notebook:](http://en.wikipedia.org/wiki/Delegation_pattern)
* [ServiceLocator](More/ServiceLocator) [:notebook:](http://en.wikipedia.org/wiki/Service_locator_pattern)
* [Repository](More/Repository)

## Contribua

Este projeto é a tradução do repo [DesignPatternsPHP](https://github.com/domnikl/DesignPatternsPHP). 
Para complementar/corrigir algo, por favor, faça um pull request no repo original 
(em inglês) e, assim que possível, a correção/melhoria será colocada aqui.

## Licença

(The MIT License)

Copyright (c) 2014 Dominik Liebler and [contributors](https://github.com/domnikl/DesignPatternsPHP/graphs/contributors)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
