# SF Symbols

- SF Symbols is a library of over 6,900 symbols designed to integrate with the San Francisco system font.
- There are four rendering modes:
    - Monochrome: applies one color to all layers.
    - Hierarchical: also applies one color, but varies the color’s opacity according to the hierarchy level.
    - Palette: uses two or more colors for the layers.
    - Multicolor: uses intrinsic colors in some symbols to enhance state, feedback, and meaning.
        - Red: error/destructive
        - Green: approve/success
        - Blue: active/selected
- Always keep accessibility and Dark Mode in mind.
- Gradients look better at larger sizes.
- Use variable color to communicate change (state/meaning); don’t use it to communicate depth or hierarchy (use opacity for that instead).
- An iOS tab bar usually prefers the fill variant, whereas a toolbar usually uses the outline variant.
- (SF Symbols animation)[!https://developer.apple.com/design/human-interface-guidelines/sf-symbols#Animations] help communicate ideas, feedback, and actions.
    - Some examples are: appear, disappear, bounce, scale, pulse, variable color, replace, magic replace, wigle, breathe, rotate, draw on/off 
- To create a custom symbol for your app, use (Sustom Symbol)[!https://developer.apple.com/documentation/UIKit/creating-custom-symbol-images-for-your-app]
