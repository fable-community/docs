## trailer Type

`object` ([trailer](media-properties-trailer.md))

# trailer Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                   |
| :------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------- |
| [site](#site) | `string` | Required | cannot be null | [media](media-properties-trailer-properties-site.md "https://fable.deno.dev/media.json#/properties/trailer/properties/site") |
| [id](#id)     | `string` | Required | cannot be null | [media](media-properties-trailer-properties-id.md "https://fable.deno.dev/media.json#/properties/trailer/properties/id")     |

## site

The name of the site (only supports youtube)

`site`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [media](media-properties-trailer-properties-site.md "https://fable.deno.dev/media.json#/properties/trailer/properties/site")

### site Type

`string`

### site Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"youtube"` |             |

## id

The id of the video

`id`

*   is required

*   Type: `string` ([id](media-properties-trailer-properties-id.md))

*   cannot be null

*   defined in: [media](media-properties-trailer-properties-id.md "https://fable.deno.dev/media.json#/properties/trailer/properties/id")

### id Type

`string` ([id](media-properties-trailer-properties-id.md))

### id Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
([A-Za-z0-9_\-]{11})
```

[try pattern](https://regexr.com/?expression=\(%5BA-Za-z0-9_%5C-%5D%7B11%7D\) "try regular expression with regexr.com")
