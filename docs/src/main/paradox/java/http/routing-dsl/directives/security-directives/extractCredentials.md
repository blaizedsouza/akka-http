# extractCredentials

## Description

Extracts the potentially present `HttpCredentials` provided with the request's `Authorization` header,
which can be then used to implement some custom authentication or authorization logic.

See @ref[Credentials and password timing attacks](index.md#credentials-and-timing-attacks-java) for details about verifying the secret.

## Example

Scala
:  @@snip [SecurityDirectivesExamplesSpec.scala]($test$/scala/docs/http/scaladsl/server/directives/SecurityDirectivesExamplesSpec.scala) { #extractCredentials0 }

Java
:  @@snip [SecurityDirectivesExamplesTest.java]($test$/java/docs/http/javadsl/server/directives/SecurityDirectivesExamplesTest.java) { #extractCredentials }
