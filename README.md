# links.rayanupadhyay.com

A terminal-style links page. It types out who I am, lists my links, and lets you type commands.

**Live:** [links.rayanupadhyay.com](https://links.rayanupadhyay.com)

## Commands

| Command | What it does |
| --- | --- |
| `help` | Show available commands |
| `ls` | List all links |
| `open <name>` | Open a link (or just type its name, like `github`) |
| `whoami` | Who made this |
| `date` | Today's date and time |
| `echo <text>` | Repeat something back |
| `clear` | Clear the screen |

There are a few hidden ones too. Have fun finding them.

## Editing links

All links live in the `CONFIG` object at the top of the script in `index.html`. Add, remove, or change entries there:

```js
{ slug: "github", url: "https://github.com/RayanUpadhyay", note: "code and projects" }
```

## Tech

One `index.html` file. Plain HTML, CSS, and JavaScript, no frameworks or build step. Hosted on Vercel.
