This is a skeleton application based on GWT having following key features,

## Data access layer ##
  * Implementation of generic super entity so that each of entities has ability to keep properties in a vertical table when required.
  * Built on top of dbgate library, which allows complex relationships with powerful data protection mechanisms to avoid dirty writes.
  * Easy extensibility to add new entity types
  * Covered most of the areas with unit tests

## MVC Layer ##
This is a simple implementation of MVC framework which is easy to understand and very easy to extend.

## Authentication ##
The skeleton contains authentication system including a log on screen. With session state checks to redirect and to prevent calling services without proper authentication. However this is a very basic authentication system, which may required to add user rights section.

## CRUD Layer ##
CRUD layer of this application has 2 sections,
  1. Service level CRUD implementation
  1. UI level CRUD implementation

both above sections can be extended for new entities with fairly easily with very low amount of code.

Refer wiki for more information