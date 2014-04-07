Simple PHP generator from UML model
===================================

Simple PHP generator from UML class diagram using Acceleo templates.

## Sources ##
Model to text (m2t) source is located in `simple-php/codegen` folder while generator is described by `simple-php/generator.xml` file.

## Translation rules ##

Class diagrams contained in an UML project are used for PHP code generation and follows this rules in order to translate UML elements to PHP.

| UML | PHP  |
| :-: |:-------:|
| Package | namespace |
| Class | class |
| Interface | Interface |
| Property | variable |
| Operation | function |
| Enumeration | class |
