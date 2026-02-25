# Basic Commands

## Navigation and Exploration

### `pwd`

Displays the current directory you are in.

### `cd`

Moves between directories.

**Examples:**

Move using absolute path:

``` bash
  cd /user/desktop
```

Move using relative path (suppose you are in `../user`):

``` bash
  cd desktop
```

Move to parent directory:

```bash
  cd ..
```

Move to root directory:

```bash
  cd
```

### `ls`

Displays files and subdirectories in the current directory.

**Useful flags:**

- `ls -l` - List with detailed information
- `ls -a` - Show hidden files

### `less`

It open, and displays the file used as parameter

```bash
  less /example.txt
```

**Useful auxiliary commands:**

- To scroll up

```CTRL-b``` or the keyboard button ```Page Up```

- To scroll down

```CTRL-f``` or the keyboard button ```Page Down```

- To search in the file:

Use a`/` and the search term.

- To leave

Type `q`

---

## File and Directory Manipulation