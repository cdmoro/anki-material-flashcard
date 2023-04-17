# Anki Material flashcard

| Light theme | Dark theme |
|---|---|
|<img width="350" alt="image" src="https://user-images.githubusercontent.com/28156761/232525097-8feb5fa1-7cfe-45d1-a2fe-b35d384e82d6.png">|<img width="350" alt="image" src="https://user-images.githubusercontent.com/28156761/232524999-ee31ce31-38e8-48b1-8140-21d7ac6d0ce8.png">|

## Demo

https://codepen.io/cdmoro/pen/ZEqbOLG

## Installation

1. Create a new card type on Anki (i.e. "Basic flashcard")
2. Copy the files into the right place (front, back and styles)
3. Select the desired variant (optional)
4. Voila!

## Test

### Window app

| Light | Dark |
|-------|------|
| ![image](https://user-images.githubusercontent.com/28156761/231449206-7033a9ac-42fc-437e-b7f5-cd7dbd23877c.png) | ![image](https://user-images.githubusercontent.com/28156761/231449051-20a70036-b354-4b43-bf71-9ae02b2ce488.png) |
| ![image](https://user-images.githubusercontent.com/28156761/231449277-118899c6-30f1-4bac-a0e2-4de5f3b6190b.png) | ![image](https://user-images.githubusercontent.com/28156761/231449098-0f853bd3-1c92-4649-a1bf-4d4664e53a99.png) |

## Variants

`Anki Material flashcard` comes with several variants: base (default), blue, white, purple, pink, teal, green, and orange. All the colors were taken from the material color specification. Checkout [the demo](https://codepen.io/cdmoro/pen/ZEqbOLG) to see the colors in action!

## Additional features

## Audio

Audio style is supported out of the box. And the best is that you don't need to create a separate field for the audio, you can put it in the same field as the answer, for example, `Water [audio:water.mp3]` and voila!  

![image](https://user-images.githubusercontent.com/28156761/231778757-df1fa800-fe4a-4f54-ada7-c4418c79aa62.png)

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

| Hidden (as hyperlink)  | Visible (as `span`) |
|---|---|
|![image](https://user-images.githubusercontent.com/28156761/231465574-2184ba37-eedb-4d49-a107-ec5b708e3a3e.png)| ![image](https://user-images.githubusercontent.com/28156761/231466551-fd5e2570-c6df-4fff-8a10-659f689df273.png) |

### Symbol class

If you are learning Chinese, Greek, and so, you can add the class `symbol` to the flashcards to get this more appeal style.

![image](https://user-images.githubusercontent.com/28156761/231778907-9e43709b-db40-4d59-8c9a-e48b1d82c5f1.png)

### Images

#### Back

<img width="528" alt="image" src="https://user-images.githubusercontent.com/28156761/232534607-6a12f63a-1d5a-4ebc-b301-2331d7c8e876.png">

### Header & Hint

<img width="528" alt="image" src="https://user-images.githubusercontent.com/28156761/232527065-f30e4253-ce40-45d4-bf15-a51f6463dee4.png">
<img width="528" alt="image" src="https://user-images.githubusercontent.com/28156761/232526942-af0c100c-b740-4bef-a235-4fdead0a2615.png">

### Emoji

<img width="528" alt="image" src="https://user-images.githubusercontent.com/28156761/232530297-f0520548-1104-4f4c-bca1-1d24a7939b1f.png">
<img width="528" alt="image" src="https://user-images.githubusercontent.com/28156761/232530112-fcc11f3c-9119-4d39-a6b9-e658c57898ef.png">

### Symbol

<img width="528" alt="image" src="https://user-images.githubusercontent.com/28156761/232530727-f5a84bf5-8904-4457-9b54-6ab204fc866e.png">
<img width="528" alt="image" src="https://user-images.githubusercontent.com/28156761/232530565-f7697639-5399-4765-94d5-9ff4a1d1df28.png">

## Examples

<img width="689" alt="image" src="https://user-images.githubusercontent.com/28156761/232532381-76df2928-2c62-4523-b7d0-7ba2b9832915.png">
<img width="689" alt="image" src="https://user-images.githubusercontent.com/28156761/232532530-dd7edc81-0334-4dc7-99db-aa08d6544958.png">

<img width="689" alt="image" src="https://user-images.githubusercontent.com/28156761/232532862-b31fb4fe-5d3d-470e-96f1-4cfc8ffb4746.png">
<img width="689" alt="image" src="https://user-images.githubusercontent.com/28156761/232532897-cba85ae2-8b87-40e7-9182-3d8fe57702e3.png">

## Credits

- Color palettes taken from https://colorhunt.co/palettes/dark
