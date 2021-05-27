### Live Demo

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/emoji-game-output-v2.gif" alt="emoji-game-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>





#### App Functionality

The app has the following functionalities:

- The _Score_ and _Total Score_ for the current game is **0** initially.
- When an **Emoji** is clicked

  - If the clicked emoji is not the same as any of the previously clicked emojis
    then the _Score_ will be increased by **1**.
  - If all the emojis are clicked exactly once

    - The _Game status_ along with _Best score_ and _Play Again_ button will
      be displayed.
    - The _Best score_ will be equal to the _Top Score_

  - If the clicked emoji is the same as any of the previously clicked emojis

    - The _Game status_ along with _Current score_ and _Play Again_ button
      should be displayed as shown.

    - If the score achieved in the current game is higher than the previous
      scores then the _Top Score_ will be updated accordingly.

- When the _Play Again_ button is clicked, then we will be able to play the
  game again.

- The _Play Again_ button should reset the game and _Score_ value but not the
  _Top Score_ value.

- The list of emojis is passed to the `EmojiGame` component as a prop
  `emojisList` in the form of an array object.

- Each emoji object will have the following properties

  | Key       | Data Type |
  | --------- | --------- |
  | id        | Number    |
  | emojiName | String    |
  | emojiUrl  | String    |

- The value of the key `id` in the emoji object should be used as a key to the
  `EmojiCard` component.
- The value of the key `emojiName` in the emoji object should be used as a alt
  text to the `emoji` image.


