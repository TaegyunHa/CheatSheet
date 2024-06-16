# Basic

| Cmd | Description            |
| --- | ---------------------- |
| w   | To start of next word  |
| e   | To end of current word |
| $   | To end of the line     |
| 0   | To first of the line   |

# Horizontal Navigation


| Cmd        | Description                        |
| ---------- | ---------------------------------- |
| `%`        | move to matching bracket           |
| `f <char>` | move on to next matching character |
| `F <char>` | move on to prev matching character |
| `t <char>` | move up to next matching character |
| `T <char>` | move up to prev matching character |
| `;`        | next character                     |
| `,`        | prev character                     |

# Vertical Navigation

| Cmd       | Description            |
| --------- | ---------------------- |
| `{`       | beginning of paragraph |
| `}`       | end of paragraph       |
| `Ctrl+d`  | half down of the page  |
| `Ctrl+u`  | half up of the page    |
| `G`       | bottom of file         |
| `gg`      | top of file            |
| `:<line>` | go to line number      |

# Search

| Cmd         | Description                    |
| ----------- | ------------------------------ |
| `/ <chars>` | search chars forward           |
| `? <chars>` | search char backward           |
| `*`         | search word on cursor forward  |
| `#`         | search word on cursor backward |
| `n`         | go forward                     |
| `N`         | go backward                    |

# Insert Mode

| Cmd | Description                           |
| --- | ------------------------------------- |
| `i` | start insert before char              |
| `I` | start insert at the beginning of line |
| `a` | start insert after char               |
| `A` | start insert at the end of line       |
| `o` | start insert bellow line              |
| `O` | start insert above line               |

# Advanced

| Cmd       | Description                       |
| --------- | --------------------------------- |
| `vi{`     | Select all inside of curly braces |
| `va{`     | Select all around of curly braces |
| `viw`     | Select word                       |
| `viW`     | Select word including space       |
| `C-g`     | Show location and file status     |
| `:!<cmd>` | Shell command                     |

# Undo

| Cmd | Description       |
| --- | ----------------- |
| u   | Undo last command |
| U   | Fix a whole line  |
| C-r | Redo command      |
