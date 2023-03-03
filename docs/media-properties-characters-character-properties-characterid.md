# characterId Schema

```txt
https://fable.deno.dev/media.json#/properties/characters/items/properties/characterId
```

Reference an existing character (\[pack:]id)

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                               |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [media.json\*](../out/media.json "open original schema") |

## characterId Type

`string` ([characterId](media-properties-characters-character-properties-characterid.md))

## characterId Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^([-_a-z0-9]+)(:[-_a-z0-9]+)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5B-_a-z0-9%5D%2B\)\(%3A%5B-_a-z0-9%5D%2B\)%3F%24 "try regular expression with regexr.com")
