ApiCycle
========

Demo project for ["Use Swagger to document a Symfony API"](https://dev.to/mathieuks/use-swagger-to-document-a-symfony-api-790) blog post

# Apps

- [Movies Api](https://github.com/matks/ApiCycle/blob/master/apps/movies-api\README.md)
- [Movies Api Client](https://github.com/matks/ApiCycle/blob/master/apps/movies-api-client\README.md)


Movies API is the Symfony app which is the topic of the blog post.

Movies API Client is an API Client generated by [Jane](https://github.com/janephp/openapi)
using the [Swagger file](https://github.com/matks/ApiCycle/blob/master/apps/movies-api-client/swagger/swagger.json)
which describes the Movies API.

Movies API Client also allows to perform behat tests for the API.

Each app README explains how to set it up and run it.