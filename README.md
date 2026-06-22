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

## GeekBoy Styles
| Style Name | Italic Name | Weight | Width |
| --- | --- | --- | --- |
| ExtraLight Condensed | ExtraLight Condensed Italic | 200 | 80 |
| Light Condensed | Light Condensed Italic | 300 | 80 |
| Regular Condensed | Regular Condensed Italic | 400 | 80 |
| Medium Condensed | Medium Condensed Italic | 500 | 80 |
| SemiBold Condensed | SemiBold Condensed Italic | 600 | 80 |
| Bold Condensed | Bold Condensed Italic | 700 | 80 |
| ExtraBold Condensed | ExtraBold Condensed Italic | 800 | 80 |
| Black Condensed | Black Condensed Italic | 900 | 80 |
| ExtraLight | ExtraLight Italic | 200 | 100 |
| Light | Light Italic | 300 | 100 |
| Regular | Regular Italic | 400 | 100 |
| Medium | Medium Italic | 500 | 100 |
| SemiBold | SemiBold Italic | 600 | 100 |
| Bold | Bold Italic | 700 | 100 |
| ExtraBold | ExtraBold Italic | 800 | 100 |
| Black | Black Italic | 900 | 100 |
| ExtraLight Expanded | ExtraLight Expanded Italic | 200 | 120 |
| Light Expanded | Light Expanded Italic | 300 | 120 |
| Regular Expanded | Regular Expanded Italic | 400 | 120 |
| Medium Expanded | Medium Expanded Italic | 500 | 120 |
| SemiBold Expanded | SemiBold Expanded Italic | 600 | 120 |
| Bold Expanded | Bold Expanded Italic | 700 | 120 |
| ExtraBold Expanded | ExtraBold Expanded Italic | 800 | 120 |
| Black Expanded | Black Expanded Italic | 900 | 120 |

## GeekBoy Display Styles
| Style Name | Italic Name | Weight | Width |
| --- | --- | --- | --- |
| ExtraBold | ExtraBold Italic | 800 | 100 |


## License
GeekBoy is licensed under the [SIL Open Font License v1.1](http://scripts.sil.org/OFL).
