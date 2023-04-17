# Anki Material flashcard

The goal of this project is to have a supercharged version of the basic Anki flashcards (front and back fields). You can have a very basic card but with a good looking style and then add features like images, emojis, hints, headers, subheader, text blocks, etc. Also, you have several variants to choose.

## Screenshots

| Light | Dark |
|---|---|
|<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232539633-d1965e42-1ab8-4017-9ce0-d244df5738ae.png">|<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232539720-e41fbf59-9b95-4975-b6e1-7e6798b5c257.png">|
|<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232539801-6ae3780b-83e9-4ee9-b7e3-edb51e857e98.png">|<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232539842-48e00aa7-c54a-40ac-ab98-00eaf1f16c09.png">|

## Demo

https://codepen.io/cdmoro/pen/ZEqbOLG

## Installation

1. Create a new card type on Anki (i.e. "Material basic")
2. Copy the files into the right place (front, back and styles)
3. Select the desired variant (optional)
4. Voila!

## Variants

`Anki Material flashcard` comes with several variants: base (default), blue, white, purple, pink, teal, green, and orange. All the colors were taken from the material color specification. Checkout [the demo](https://codepen.io/cdmoro/pen/ZEqbOLG) to see the colors in action!

## Features

## Audio

Audio style is supported out of the box. And the best is that you don't need to create a separate field for the audio, you can put it in the same field as the answer, for example, `Water [audio:water.mp3]` and voila!

### Hints

Hints are supported, by default the display property is set to block and the text is displayed in italics. Add a hint is pretty straight forward, as you can see in the following example:

``` html{5}
<div class="flashcard back base">
    {{FrontSide}}

    <hr id="answer">

    <div class="body">
        <div class="text-block">
           <div class="flex">{{Back}}</div>
          {{hint:Translation}}
        </div>
    </div>
</div>
```

### Symbol class

If you are learning Chinese, Greek, and so, you can add the class `symbol` to the flashcards to get this more appeal style. Bonus tip: if you add a subheader element below the answer you can get this result:

``` html
<div class="flashcard front base symbol">
  <div class="body">
    漢字
    <div class="subheader">[kaɲdʑi]</div>
  </div>
</div>
```

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232530727-f5a84bf5-8904-4457-9b54-6ab204fc866e.png">

### Images

#### Back

``` html
<div class="flashcard back base">
  {{FrontSide}}
  <hr id="answer">
  <div class="body">
    <img src="https://picsum.photos/id/154/600/600" />
    <div class="text-block">
      <div class="flex">
        {{Back}}
      </div>
      {{hint:Variants}}
    </div>
  </div>
</div>
```

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232611344-87dac281-3190-4600-96a3-952a9dc05584.png">

### Header

``` html
<div class="flashcard front base">
  <div class="body">
    <div class="header">Greek nouns</div>
    Νερό
  </div>
</div>
```

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232526942-af0c100c-b740-4bef-a235-4fdead0a2615.png">

### Emoji

``` html
<div class="flashcard front base">
  <div class="body">
    <div class="emoji">🥣</div><br>Το πρωινό
  </div>
</div>
```

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232530112-fcc11f3c-9119-4d39-a6b9-e658c57898ef.png">

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232543913-c2acddb4-b5e7-47b0-bf3f-101ad012d449.png">


## Examples

These examples were taken from imported decks and applied the Material flashcard.

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232532530-dd7edc81-0334-4dc7-99db-aa08d6544958.png">

<img width="400" alt="image" src="https://user-images.githubusercontent.com/28156761/232532897-cba85ae2-8b87-40e7-9182-3d8fe57702e3.png">

## Credits

- Color palettes taken from https://colorhunt.co/palettes/dark
