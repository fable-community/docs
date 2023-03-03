# id Schema

```txt
https://fable.deno.dev/character.json#/properties/id
```

A unique alphanumeric id

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                       |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [character.json\*](../out/character.json "open original schema") |

## id Type

`string` ([id](character-properties-id.md))

## id Constraints

**maximum length**: the maximum number of characters for this string is: `20`

**minimum length**: the minimum number of characters for this string is: `1`

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[-_a-z0-9]+$
```

[try pattern](https://regexr.com/?expression=%5E%5B-_a-z0-9%5D%2B%24 "try regular expression with regexr.com")
