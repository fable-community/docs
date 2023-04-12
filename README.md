# manifest.json

## Top-Level Parameters

{

<dl>
  <dd>

<kbd><br> [id](docs/schema.md#id) <br><br></kbd>  
_`A unique alphanumeric id`_

<kbd><br> [title?](docs/schema.md#title) <br><br></kbd>  
_`The display name of the pack`_

<kbd><br> [description?](docs/schema.md#description) <br><br></kbd>  
_`Small description about the pack and what it contains`_

<kbd><br> [nsfw?](docs/schema.md#nsfw) <br><br></kbd>  
_`If the pack contains any nsfw (explicit) content`_

<kbd><br> [author?](docs/schema.md#author) <br><br></kbd>  
_`The name of the pack's author`_

<kbd><br> [image?](docs/schema.md#image) <br><br></kbd>  
_`The icon of the pack or its author`_

<kbd><br> [url?](docs/schema.md#url) <br><br></kbd>  
_`A url to pack's homepage`_

<kbd><br> [depends?](docs/schema.md#depends) <br><br></kbd>  
_`A list of packs that are required to make your pack function properly`_

<kbd><br> [conflicts?](docs/schema.md#conflicts) <br><br></kbd>  
_`A list of packs that might conflict with your pack`_

<kbd><br> [media?](docs/schema.md#media) <br><br></kbd>: {
  <dl>
    <dd>
<kbd><br> <a href="docs/schema-properties-media.md#conflicts">conflicts?</a> <br><br></kbd>: [ <i><code>"[pack-id:media-id]"</code></i> ]</br>
<kbd><br> <a href="docs/schema-properties-media.md#new">new?</a> <br><br></kbd>: [
  <dl>
    <dd>
      <kbd><br> <a href="docs/media.md#id">id</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/media.md#type">type</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/media.md#format">format?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/media.md#title">title</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/media.md#popularity">popularity</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/media.md#description">description?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/media.md#images">images?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/media.md#trailer">trailer?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/media.md#externalLinks">externalLinks?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/media.md#relations">relations?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/media.md#characters">characters?</a> <br><br></kbd></br>
    </dd>
  </dl>
]
    </dd>
  </dl>

}

<kbd><br> [characters?](docs/schema.md#characters) <br><br></kbd>: {
  <dl>
    <dd>
      <kbd><br> <a href="docs/schema-properties-characters.md#conflicts">conflicts?</a> <br><br></kbd>: [ <i><code>"[pack-id:character-id]"</code></i> ]</br>
<kbd><br> <a href="docs/schema-properties-characters.md#new">new?</a> <br><br></kbd>: [
  <dl>
    <dd>
      <kbd><br> <a href="docs/character.md#id">id</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/character.md#name">name</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/character.md#description">description?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/character.md#popularity">popularity?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/character.md#images">images?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/character.md#gender">gender?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/character.md#age">age?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/character.md#externalLinks">externalLinks?</a> <br><br></kbd></br>
      <kbd><br> <a href="docs/character.md#media">media?</a> <br><br></kbd></br>
    </dd>
  </dl>
]
    </dd>
  </dl>

}

</dd>
</dl>

}
