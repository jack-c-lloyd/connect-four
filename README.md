# Connect Four

## Introduction

This repository is based on the specification for **AQA AS and A-level Computer Science** (7516, 7517); it is written in **Python** (Option D) and adheres to the subject content for **AS Paper 1** (§3.1 to §3.4), meaning within the procedural-oriented programming paradigm.

## Preliminary Material

The **Skeleton Program** accompanying this **Preliminary Material** is based on the classic game of *"Connect 4"* by Hasbro.

**Note**: refer to the [official instructions](https://instructions.hasbro.com/en-us/instruction/connect-4-game-instructions).

A board consists of 7 columns and 6 rows, resulting in a total of 42 slots. Empty slots are represented by dotted circles, whereas discs are represented by white circles and black circles; both are encoded using Unicode characters.

**Figure 1** shows an example board.

> **Figure 1**
> 
> ```
>   1 2 3 4 5 6 7  
> |---------------|
> | ◌ ◌ ◌ ◌ ◌ ◌ ◌ |
> | ◌ ◌ ◌ ◌ ◌ ◌ ◌ |
> | ◌ ● ◌ ◌ ◌ ◌ ◌ |
> | ◌ ○ ◌ ◌ ◌ ◌ ◌ |
> | ◌ ○ ○ ● ◌ ◌ ◌ |
> | ○ ● ○ ● ● ◌ ◌ |
> |---------------|
> ```

**Figure 2** shows an example prompt.

> **Figure 2**
> 
> ```
> Jack, enter a slot: 0
> Slot 0 is invalid!
> Enter another slot: 3
> ```

### Testing

Text files have been included for testing purposes:

1. `horizontal.txt`
2. `vertical.txt`
3. `diagonal.txt`
4. `draw.txt`

#### Usage

```
cat test/draw.txt | python connect-four.py
```

**Note**: this is supported by Linux, macOS, and Windows (PowerShell).

### Suggestions

Suggestions for extensions include:

- AI opponent using [minimax](https://www.chessprogramming.org/Minimax) or [negamax](https://www.chessprogramming.org/Negamax).
- Client-server or peer-to-peer networking via [sockets](https://docs.python.org/3/library/socket.html).
- Documentation with [docstrings](https://peps.python.org/pep-0257/).
- Graphical user interface integration (e.g., [Tkinter](https://docs.python.org/3/library/tkinter.html)).
- Refactor into the [object-oriented programming](https://adacomputerscience.org/topics/object_oriented_programming) paradigm.
- Variations, such as ["Pop Out"](https://en.wikipedia.org/wiki/Connect_Four#PopOut) and ["Pop 10!"](https://en.wikipedia.org/wiki/Connect_Four#Pop_10).

## License

This software is available under the [MIT License](https://mit-license.org/).
