[![Test](https://github.com/Sentero-esp12/Multi-Premoves-Mouse-Keyboard/actions/workflows/node.js.yml/badge.svg)](https://github.com/Sentero-esp12/Multi-Premoves-Mouse-Keyboard/actions/workflows/node.js.yml)

**Currently the extensions are not actively maintained and have bugs and may break at any point. I'm not playing ultra that much nowadays, so I'm not working on the extensions anymore, but hopefully someone could continue this work or, perhaps, if someone rich can sponsor me, I will continue working on them myself: [patreon post](https://www.patreon.com/posts/lichess-keyboard-53287800) (as a freelance job).**

**You can also contribute by coding or by hiring other coders, and I will merge your pull requests on GitHub**

**The extension might break sometimes, but I've found that the most stable cofiguration is the following (for kb only use)**:
- The option [How do you move pieces](https://lichess.org/account/preferences/game-behavior) should be set to `drag`. (if you then want to use the previous kb extension, it should be set to `clicks` or `both`)
- [Autoqueen](https://lichess.org/account/preferences/game-behavior) should be turned `on`
- Castling should be set to [Move king onto rook](https://lichess.org/account/preferences/game-behavior)
- [Piece animation](https://lichess.org/account/preferences/game-display) should be set to `None` 

Now click the extension's icon and use these settings (don't forget to click 'save'):
- Use keyboard: `on`
- Use mouse: `off`

Your page zoom might need to be set to 100% (haven't tested it thorougly)

Other settings should probably not affect stability.

 
# Multi Premoves For Mouse and Keyboard
Creating unlimited multiple premoves compatible with all Lichess styles of playing (keyboard, mouse, touchscreen)
 
# Important:
- This extension also includes keyboard.
- This extension is experiemental, but should have higher capacities than the previous KB extension. If you see a bug, open a new issue and describe it in detail. 
Also it's important to read the information below. 
- To access the settings, click the extension's icon (pin it if necessary)
- The option [How do you move pieces](https://lichess.org/account/preferences/game-behavior) should be set to either `drag` or `both`. Using `drag` should be more reliable. If you use kb only and have any problems with moves, try switching to 'drag' as well. 
- For now it only supports [autoqueen](https://lichess.org/account/preferences/game-behavior) (and possibly autoqueen on premoves as well). If you promote to something else it might break. 
- Castling should be set to [Move king onto rook](https://lichess.org/account/preferences/game-behavior)
- 'Piece animation' should be set to [None](https://lichess.org/account/preferences/game-display)
- Right mouse button is currently the default button to activate multi premoves. When it's pressed you can input multiple premoves. You can also enable the option "Always multipremove". Or you can click the red circle below the board (it will change to green when multipremove input is activated). You can change the key in the settings.
- Currently after resizing the window or changing the board size, the page should be reloaded. 
- If you use kb extension, disable the other kb extension and activate 'Use keyboard' in the settings. There you can set the keys, and now a key for a second queen is available (last promoted queen becomes the second queen for the extension. When there are more than two queen, the extension should move the last promoted queen when the key for a second queen is pressed or a random queen out of the rest available for a move). 
- Other options: auto berserk back, rematch, berserk, resign, back to the tournament buttons, second queen key for keyboard. 
