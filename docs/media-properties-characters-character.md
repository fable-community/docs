## items Type

`object` ([character](media-properties-characters-character.md))

# items Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                       |
| :-------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [role](#role)               | `string` | Required | cannot be null | [media](media-properties-characters-character-properties-role.md "https://fable.deno.dev/media.json#/properties/characters/items/properties/role")               |
| [characterId](#characterid) | `string` | Required | cannot be null | [media](media-properties-characters-character-properties-characterid.md "https://fable.deno.dev/media.json#/properties/characters/items/properties/characterId") |

## role

Choose the role the character plays in the media

`role`

*   is required

*   Type: `string` ([role](media-properties-characters-character-properties-role.md))

*   cannot be null

*   defined in: [media](media-properties-characters-character-properties-role.md "https://fable.deno.dev/media.json#/properties/characters/items/properties/role")

### role Type

`string` ([role](media-properties-characters-character-properties-role.md))

### role Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"MAIN"`       |             |
| `"SUPPORTING"` |             |
| `"BACKGROUND"` |             |

## characterId

Reference an existing character (\[pack:]id)

`characterId`

*   is required

*   Type: `string` ([characterId](media-properties-characters-character-properties-characterid.md))

*   cannot be null

*   defined in: [media](media-properties-characters-character-properties-characterid.md "https://fable.deno.dev/media.json#/properties/characters/items/properties/characterId")

### characterId Type

`string` ([characterId](media-properties-characters-character-properties-characterid.md))

### characterId Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^([-_a-z0-9]+)(:[-_a-z0-9]+)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5B-_a-z0-9%5D%2B\)\(%3A%5B-_a-z0-9%5D%2B\)%3F%24 "try regular expression with regexr.com")
