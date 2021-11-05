# CodingStyle

A description of this package.

Property wrapper @CodingStyle returns string decorated in three styles:
1. Camel case: @CodingSyle(codingStyle: .camelCase) var ...
2. Snake case: @CodingSyle(codingStyle: .snakeCase) var ...
3. Kebab case: @CodingSyle(codingStyle: .kebabCase) var ...

Example:

@CodingSyle(codingStyle: .camelCase) var camelCaseString = "String in camel case"
returns "String In Camel Case"
