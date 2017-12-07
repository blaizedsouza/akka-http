# mapSettings

## Description

Transforms the `RoutingSettings` with a `Function<RoutingSettings, RoutingSettings>`.

See also @ref[withSettings](withSettings.md) or @ref[extractSettings](extractSettings.md).

## Example

Scala
:  @@snip [BasicDirectivesExamplesSpec.scala]($test$/scala/docs/http/scaladsl/server/directives/BasicDirectivesExamplesSpec.scala) { #withSettings-0 }

Java
:  @@snip [BasicDirectivesExamplesTest.java]($test$/java/docs/http/javadsl/server/directives/BasicDirectivesExamplesTest.java) { #mapSettings }
