
# CodeWriter-WinUI
Win2D-based code editor for WinUI 3.

At this stage, this is only a proof of concept. 
I tried to port https://github.com/PavelTorgashov/FastColoredTextBox line by line which was a huge pain so I had to stop. The codebase is just too huge and hard to read.

I took some inspiration and created my own Win2d-based control. Feel free to contibute! Would be nice to have a fast full-featured text editor for WinAppSDK / MAUI!

## Screenshot of the TestApp
Stuff that works:
- Text selection & beam placement (inputs: PointerPress & Up/Down/Left/Right keys)
- Basic text editing (char insertion, back key, delete key)
- Basic copy & paste logic
- Scrolling (vertical & horizontal)
- Text and FontSize are two-way bindable DependencyProperties
- Proof-of-Concept syntax highlighting shown with a ConTeXt example file (only line by line Regexing for now; tokenization comes in the future)
- Basic IntelliSense logig
- Actions (right-click menu & KeyboardAccelerators)

![Screenshot 2021-08-25 165128](https://user-images.githubusercontent.com/13318246/130813418-299abb0c-d33d-4041-98f5-ff81b06a47b1.png)
