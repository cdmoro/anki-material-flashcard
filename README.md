# Anki Material flashcard

![image](https://user-images.githubusercontent.com/28156761/231778289-13cb0574-403b-42f2-b9c9-0f6b5e9057b6.png)

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

## Credits

- Color palettes taken from https://colorhunt.co/palettes/dark
