# Forms

This package gives you a method to handle forms in any forms in any framework
from front-end to back-end.

# How it works ?

Forms will be expressed by an `AbstractType`.
Those `AbstractType` will allow the package to build a `ConcreteType`
by using a `FormFactory`. Those `ConcreteType` will have
method to check if the form has been submitted or if valid.

## Rendering

Rendering will be handled by rendering functions / components.
Implementations will be specific for each framework.

## Validation and submission

Validation will be deferred to validation libraries in order
to NOT create yet another validation lib.

## Binding

Any form could be bound to an object or a class.
This way it will be really easy to extract form data.
This binding will also help to do validation a entity level with
decorators based validation.

 

 
