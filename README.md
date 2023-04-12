# Anki Basic Flashcard

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

## Additional features

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


## Variants

`Anki Basic Flashcard` comes with several styles

### Purple

Light

![image](https://user-images.githubusercontent.com/28156761/231300730-789006cb-6ba9-4f04-8b20-3b69f137d85d.png)

Dark

![image](https://user-images.githubusercontent.com/28156761/231300686-e0aec108-da6c-45b3-8d57-9833448a1bce.png)
