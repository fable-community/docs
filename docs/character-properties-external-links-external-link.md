# external link Schema

```txt
https://fable.deno.dev/character.json#/properties/externalLinks/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                       |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [character.json\*](../out/character.json "open original schema") |

## items Type

`object` ([external link](character-properties-external-links-external-link.md))

# items Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                |
| :------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [site](#site) | `string` | Required | cannot be null | [character](character-properties-external-links-external-link-properties-site.md "https://fable.deno.dev/character.json#/properties/externalLinks/items/properties/site") |
| [url](#url)   | `string` | Required | cannot be null | [character](character-properties-external-links-external-link-properties-url.md "https://fable.deno.dev/character.json#/properties/externalLinks/items/properties/url")   |

## site

The title of the site

`site`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [character](character-properties-external-links-external-link-properties-site.md "https://fable.deno.dev/character.json#/properties/externalLinks/items/properties/site")

### site Type

`string`

## url

The full url of the site

`url`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [character](character-properties-external-links-external-link-properties-url.md "https://fable.deno.dev/character.json#/properties/externalLinks/items/properties/url")

### url Type

`string`

### url Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(https:\/\/)?(www\.)?(youtube\.com|twitch\.tv|crunchyroll\.com|tapas\.io|webtoon\.com|amazon\.com)[\S]*$
```

[try pattern](https://regexr.com/?expression=%5E\(https%3A%5C%2F%5C%2F\)%3F\(www%5C.\)%3F\(youtube%5C.com%7Ctwitch%5C.tv%7Ccrunchyroll%5C.com%7Ctapas%5C.io%7Cwebtoon%5C.com%7Camazon%5C.com\)%5B%5CS%5D*%24 "try regular expression with regexr.com")
