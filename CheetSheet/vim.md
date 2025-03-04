# Basic

| Command | Description            |
| ------- | ---------------------- |
| `w`     | To start of next word  |
| `e`     | To end of current word |
| `$`     | To end of the line     |
| `0`     | To first of the line   |

# Horizontal Navigation


| Command        | Description                        |
| ---------- | ---------------------------------- |
| `%`        | move to matching bracket           |
| `f <char>` | move on to next matching character |
| `F <char>` | move on to prev matching character |
| `t <char>` | move up to next matching character |
| `T <char>` | move up to prev matching character |
| `;`        | next character                     |
| `,`        | prev character                     |

# Vertical Navigation

| Command       | Description            |
| --------- | ---------------------- |
| `{`       | beginning of paragraph |
| `}`       | end of paragraph       |
| `Ctrl+d`  | half down of the page  |
| `Ctrl+u`  | half up of the page    |
| `G`       | bottom of file         |
| `gg`      | top of file            |
| `:<line>` | go to line number      |

# Search

| Command         | Description                    |
| ----------- | ------------------------------ |
| `/ <chars>` | search chars forward           |
| `? <chars>` | search char backward           |
| `*`         | search word on cursor forward  |
| `#`         | search word on cursor backward |
| `n`         | go forward                     |
| `N`         | go backward                    |

# Insert Mode

| Command | Description                           |
| --- | ------------------------------------- |
| `i` | start insert before char              |
| `I` | start insert at the beginning of line |
| `a` | start insert after char               |
| `A` | start insert at the end of line       |
| `o` | start insert bellow line              |
| `O` | start insert above line               |

# Advanced

| Command       | Description                       |
| ------------- | --------------------------------- |
| `vi{`         | Select all inside of curly braces |
| `va{`         | Select all around of curly braces |
| `viw`         | Select word                       |
| `viW`         | Select word including space       |
| `C-g`         | Show location and file status     |
| `:!<command>` | Shell command                     |

# Undo

| Command | Description       |
| ------- | ----------------- |
| `u`     | Undo last command |
| `U`     | Fix a whole line  |
| `C-r`   | Redo command      |

# Comment
| Command | Mode   | Description                      |
| ------- | ------ | -------------------------------- |
| `gc`    | Normal | Comment/Uncomment                |
| `gc`    | Visual | Comment/Uncomment selected block |

# Custom remap
| Command | Mode   | Description                     |
| ------- | ------ | ------------------------------- |
| `sv`    | Normal | Split window vertically         |
| `sh`    | Normal | Split window horizontally       |
| `se`    | Normal | Make split equal size           |
| `sx`    | Normal | Close current split             |
| `to`    | Normal | Open new tab                    |
| `tx`    | Normal | Close current tab               |
| `tn`    | Normal | Go to next tab                  |
| `tp`    | Normal | Go to previous tab              |
| `tf`    | Normal | Open current buffer in next tab |

# Surround

| Command                | Mode   | Description                                |
| ---------------------- | ------ | ------------------------------------------ |
| `ys<motion><char>`     | Normal | Add surround `<char>`                      |
| `yS<char>`             | Normal | Add surround `<char>` with `\n`            |
| `yss<char>`            | Normal | Add surround `<char>` for line             |
| `cs<charFrom><charTo>` | Normal | Change surround `<charFrom>` to `<charTo>` |
| `ds<char>`             | Normal | Delete surround `<char>`                   |
| `S<char>`              | Visual | Add surround `<char>`                      |
