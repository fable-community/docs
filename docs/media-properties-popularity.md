# popularity Schema

```txt
https://fable.deno.dev/media.json#/properties/popularity
```

Set the popularity of the media (the number of followers or people who read/watch it)

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                               |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [media.json\*](../out/media.json "open original schema") |

## popularity Type

`integer` ([popularity](media-properties-popularity.md))

## popularity Constraints

**maximum**: the value of this number must smaller than or equal to: `2147483647`

**minimum**: the value of this number must greater than or equal to: `0`
