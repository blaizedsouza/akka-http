# extractDataBytes

## Description

Extracts the entities data bytes as `Source<ByteString, NotUsed>` from the `RequestContext`.

The directive returns a stream containing the request data bytes.

## Example

Scala
:  @@snip [BasicDirectivesExamplesSpec.scala]($test$/scala/docs/http/scaladsl/server/directives/BasicDirectivesExamplesSpec.scala) { #extractDataBytes-example }

Java
:  @@snip [BasicDirectivesExamplesTest.java]($test$/java/docs/http/javadsl/server/directives/BasicDirectivesExamplesTest.java) { #extractDataBytes }
