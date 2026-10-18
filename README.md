![Dark terminal panel reading ">>> import kritagya" beside a grey and blue K monogram](assets/hero.svg)

<h1 align="center">Kritagya Dubey</h1>

<p align="center">
  <b>Python developer.</b> I build small tools that fix everyday annoyances,<br>
  and send fixes upstream to the open-source projects I rely on.
</p>

---

I'm self-taught and I learn by shipping: break it, read the traceback, fix it,
repeat. Most of what I write starts as an irritation of my own — a downloads
folder that nobody has ever seen twice the same way, a rename that took far too
many clicks, a clipboard that forgets everything the moment I close it.

Everything here is MIT licensed. Where there is code there are tests, and a
README that says what it does **and what it doesn't**.

### Now

- **Building** — small Python tools, one annoyance at a time
- **Maintaining** — bug fixes upstream where the software I use has a gap
- **Exploring** — HTML and CSS next to Python, and Git beyond `push`/`pull`

### Selected work

| Project | What it is |
|---------|------------|
| [**EzSort**](https://github.com/kritagyadubey/EzSort) | Sorts a messy folder into categories — CLI and desktop app, zero dependencies, preview first, undo everything. |
| [**EzRename**](https://github.com/kritagyadubey/EzRename) | Batch-renames files with a live preview and one-click undo. GUI and CLI for Windows. |
| [**Easy Clipboard Manager**](https://github.com/kritagyadubey/Easy-Clipboard-Manager) | A local-first clipboard history for Windows. Search, snippets, global hotkey — nothing ever leaves your machine. |
| [**TreeMark**](https://github.com/kritagyadubey/TreeMark) | Prints any project as a tree: plain, Markdown or emoji. Standard library only. `pip install treemark` |
| [**awesome-tools**](https://github.com/kritagyadubey/awesome-tools) | A directory of 1,026 genuinely free, open-source and free-tier tools, with a searchable static web app. |
| [**AI Prompt Vault**](https://github.com/kritagyadubey/AI-Prompt-Vault) | 162 prompt enhancers across 14 categories. Copy, paste, refine. |

### How I work

- **Never surprise the user.** Preview before you act, and make every action
  undoable. A file mover that deletes something once never earns that trust
  back.
- **Ship the test with the fix.** A bug report is a test that hasn't been
  written down yet.
- **Write down the limits.** A README that only lists strengths is an
  advertisement, so the limitations get their own section.
- **Small surface, no dependencies** where I can manage it — a tool that
  installs in one line is a tool people actually try.

### Contributing upstream

I'd rather send the fix than file a complaint. Three have been merged, and
five more are waiting on review:

| Pull request | Status | Fix |
|--------------|--------|-----|
| [osmose-qa/osmose-backend#2839](https://github.com/osmose-qa/osmose-backend/pull/2839) | **Merged** | `TagRemove_Incompatibles` rejected `aeroway=jet_bridge` with `highway=footway`, a pairing used by about half of those objects |
| [osmose-qa/osmose-backend#2838](https://github.com/osmose-qa/osmose-backend/pull/2838) | **Merged** | The unexpected-symbol check flagged emoji in free-text tags like `description`, not just in names |
| [petercorke/bdsim#121](https://github.com/petercorke/bdsim/pull/121) | **Merged** | `oodebug` wrappers hid the real operator signatures from the generated API docs |
| [numpy/numpy-financial#167](https://github.com/numpy/numpy-financial/pull/167) | Open | `fv` sized its output buffer from `rate` alone, so an integer rate truncated the result and made `ipmt`/`ppmt` raise on a 0% loan |
| [arsenetar/dupeguru#1431](https://github.com/arsenetar/dupeguru/pull/1431) | Open | Scanning a directory loop (Windows junction / symlink) blew the recursion limit — now walked iteratively with cycle detection |
| [mgedmin/dozer#22](https://github.com/mgedmin/dozer/pull/22) | Open | Debug pages were served unauthenticated — added optional HTTP Basic auth with constant-time comparison |
| [PyCQA/docformatter#397](https://github.com/PyCQA/docformatter/pull/397) | Open | Splitting a multi-sentence summary stranded the rest of it under a stray blank line, glued to the description |
| [kuzmoyev/google-calendar-simple-api#212](https://github.com/kuzmoyev/google-calendar-simple-api/pull/212) | Open | A `timezone` passed alongside timezone-aware datetimes was written into the `TZID` label without converting them |

```python
# kritagya.py
projects = 6            # the six listed above
merged_upstream = 3     # pull requests other maintainers have accepted
open_upstream = 5       # waiting on review
status = "still learning"
```

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/monogram-dark.svg">
    <img src="assets/monogram-light.svg" width="34" alt="K monogram">
  </picture>
</p>

<p align="center">Still learning. If you're stuck on the same thing, <a href="https://github.com/kritagyadubey">say hi</a>.</p>
