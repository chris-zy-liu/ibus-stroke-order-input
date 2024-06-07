# IBus-Stroke-Order-Input
Custom ibus input method based on the stroke order of Chinese characters, made to allow for typing both simplified and traditional Chinese using one keyboard input method.

# Functionality
Uses five keys to represent the five general stroke types of 楷書 (Regular Script)
- **f**（一，横）
- **j**（丨，豎）
- **g**（丿，撇）
- **h**（乀，捺）
- **n**（乚，鈎）

Commonly used keys close to home row are chosen for their easy of access.
Typing these keys in sequence of the stroke order will isolate the character being typed (eg. **fjnfffjghfjnffjj** for 輸).

# Comma short-hand
In order to reduce the about of keys needed to be typed to lock in each character, a system of reducing the number of key inputs is created. The comma key (,) is used to mark a "skip" in characters which require longer than six strokes to write. Three more strokes are needed after the comma to denote the last three strokes of the character (eg. **fjnfffj,fjj** or even **f,fjj** can be used to type 輸, though the candidate list may be extremely long).

# Special Cases
左點 and 右點 is typed using the g and h keys, respectively. 左豎鈎(as in 扌) is classified under the **j** key while 右豎鈎 (as in the third stroke for 民) is classified under the **n** key.

# Footnotes
This input method is by no means practical to use as an daily driver —— intelligent Pinyin can achieve much faster speeds and the Wubi input method can be used to type both simplified and traditional characters. However, I find this input method to be much easier to learn than Wubi and more enjoyable to type with than Pinyin because it mirrors the process of actually writing Chinese; IMHO, I find this to help the writing process because one is able to key in the exact character instead of the sound of the character.
