# omnifocus-taskpaper-templates

This project is a collection of [Taskpaper](https://taskpaper.com) templates to be used with [OmniFocus](https://omnigroup.com/omnifocus/). 

Find an explanation of how these are used together in the [OmniFocus Taskpaper Reference by OmniGroup](https://support.omnigroup.com/omnifocus-taskpaper-reference/).

Users are strongly encouraged to load these templates into the [Drafts app](https://getdrafts.com) with Rosemary Orchard's [OF Taskpaper plugin](https://actions.getdrafts.com/g/1F6) by copying and pasting the text.

## Syntax Highlighting

A Drafts syntax definition (`OmniFocus TaskPaper.draftsSyntax`) is included in this repository to provide syntax highlighting when editing these templates in Drafts. To install it:

1. In Drafts, open **Settings → Syntax → Import** and select the `OmniFocus TaskPaper.draftsSyntax` file, or
2. Drag and drop the file onto the Drafts app window on macOS.

The syntax highlights:
- **Projects** — lines ending with `:`
- **Tasks** — lines beginning with `- `
- **Completed tasks** (`@done`) — rendered as dimmed comment text
- **OmniFocus attributes** — `@attribute` names and their `(values)` in distinct colors
- **URL deep links** — `omnifocus://`, `agenda://`, `dayone://`, `https://`, and other schemes
- **Template placeholders** — `«guillemet»`, `[[wiki-link]]`, and `[bracket]` forms

