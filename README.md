# Anki Material flashcard

| Light | Dark |
|---|---|
|<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232539633-d1965e42-1ab8-4017-9ce0-d244df5738ae.png">|<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232539720-e41fbf59-9b95-4975-b6e1-7e6798b5c257.png">|
|<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232539801-6ae3780b-83e9-4ee9-b7e3-edb51e857e98.png">|<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232539842-48e00aa7-c54a-40ac-ab98-00eaf1f16c09.png">|

## Demo

https://codepen.io/cdmoro/pen/ZEqbOLG

## Installation

1. Create a new card type on Anki (i.e. "Basic flashcard")
2. Copy the files into the right place (front, back and styles)
3. Select the desired variant (optional)
4. Voila!

## Variants

`Anki Material flashcard` comes with several variants: base (default), blue, white, purple, pink, teal, green, and orange. All the colors were taken from the material color specification. Checkout [the demo](https://codepen.io/cdmoro/pen/ZEqbOLG) to see the colors in action!

## Additional features

## Audio

Audio style is supported out of the box. And the best is that you don't need to create a separate field for the audio, you can put it in the same field as the answer, for example, `Water [audio:water.mp3]` and voila!

### Hints

Hints are supported, by default the display property is set to block and the text is displayed in italics. Add a hint is pretty straight forward, as you can see in the following example:

``` html{5}
<div class="flashcard back pink">
  <div class="front">{{Front}}</div>
  <div class="body">
    {{Back}}
    {{hint:Translation}}
  </div>
</div>
```

Result:

### Symbol class

If you are learning Chinese, Greek, and so, you can add the class `symbol` to the flashcards to get this more appeal style.

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232530727-f5a84bf5-8904-4457-9b54-6ab204fc866e.png">

### Images

#### Back

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232534607-6a12f63a-1d5a-4ebc-b301-2331d7c8e876.png">

### Header & Hint

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232526942-af0c100c-b740-4bef-a235-4fdead0a2615.png">

### Emoji

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232530112-fcc11f3c-9119-4d39-a6b9-e658c57898ef.png">

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232543913-c2acddb4-b5e7-47b0-bf3f-101ad012d449.png">


## Examples

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232532530-dd7edc81-0334-4dc7-99db-aa08d6544958.png">

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232532897-cba85ae2-8b87-40e7-9182-3d8fe57702e3.png">

## Credits

- Color palettes taken from https://colorhunt.co/palettes/dark
