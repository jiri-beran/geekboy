# GeekBoy

[Download GeekBoy](http://github.com/jiri-beran/geekboy/releases/latest)

**GeekBoy** is a typeface family derived from the [Hubot Sans](http://github.com/github/hubot-sans) project and customized as a brand typeface for GeekBoy.

It retains the core structure and design principles of Hubot Sans, while introducing customized glyph designs, typographic refinements, and brand-specific display forms.

Original source: [https://github.com/github/hubot-sans](http://github.com/github/hubot-sans)

As its original source, GeekBoy is also a [variable font](https://web.dev/variable-fonts/). Variable fonts enable different variations of a typeface to be incorporated into one single file, and are [supported by all major browsers](https://caniuse.com/?search=variable%20fonts).

## Usage

 For web, we recommend using `GeekBoy.woff2`. Define the font with a `@font-face` rule, set its **weight** and **stretch** ranges, and use it:

 ```css
 @font-face {
   font-family: 'GeekBoy';
   src:
     url('GeekBoy.woff2') format('woff2 supports variations'),
     url('GeekBoy.woff2') format('woff2-variations');
   font-weight: 200 900;
   font-stretch: 75% 125%;
 }
 html {
   font-family: 'GeekBoy';
 }
 ```

 To reduce [CLS](https://web.dev/cls/), you can preload the font in the `head` of your document:

 ```html
 <link rel="preload" href="GeekBoy.woff2" as="font" type="font/woff2" crossorigin>
 ```

## Styles
| Style Name | Italic Name | Weight | Width |
| --- | --- | --- | --- |
| ExtraLight Narrow | ExtraLight Narrow Italic | 200 | 75 |
| Light Narrow | Light Narrow Italic | 300 | 75 |
| Regular Narrow | Regular Narrow Italic | 400 | 75 |
| Medium Narrow | Medium Narrow Italic | 500 | 75 |
| SemiBold Narrow | SemiBold Narrow Italic | 600 | 75 |
| Bold Narrow | Bold Narrow Italic | 700 | 75 |
| ExtraBold Narrow | ExtraBold Narrow Italic | 800 | 75 |
| Black Narrow | Black Narrow Italic | 900 | 75 |
| ExtraLight | ExtraLight Italic | 200 | 100 |
| Light | Light Italic | 300 | 100 |
| Regular | Regular Italic | 400 | 100 |
| Medium | Medium Italic | 500 | 100 |
| SemiBold | SemiBold Italic | 600 | 100 |
| Bold | Bold Italic | 700 | 100 |
| ExtraBold | ExtraBold Italic | 800 | 100 |
| Black | Black Italic | 900 | 100 |
| ExtraLight Wide | ExtraLight Wide Italic | 200 | 125 |
| Light Wide | Light Wide Italic | 300 | 125 |
| Regular Wide | Regular Wide Italic | 400 | 125 |
| Medium Wide | Medium Wide Italic | 500 | 125 |
| SemiBold Wide | SemiBold Wide Italic | 600 | 125 |
| Bold Wide | Bold Wide Italic | 700 | 125 |
| ExtraBold Wide | ExtraBold Wide Italic | 800 | 125 |
| Black Wide | Black Wide Italic | 900 | 125 |


## License
GeekBoy is licensed under the [SIL Open Font License v1.1](http://scripts.sil.org/OFL).
