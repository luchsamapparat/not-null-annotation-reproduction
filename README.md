# NotNull Annotation Reproduction

This demo reproduces a bug where a type (`InternetRecipe`) does not consider the nullability of a property got via `allOf` from another type (`Recipe`).

```
./mvnw clean generate-sources
```