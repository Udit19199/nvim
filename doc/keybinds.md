# Kickstart Keybindings

## Global & Basic Keybindings (`init.lua`)

- `<leader>` is mapped to the `<Space>` key.
- `<Esc>` (Normal mode): Clears search highlights.
- `<leader>q` (Normal mode): Opens the diagnostic quickfix list.
- `<Esc><Esc>` (Terminal mode): Exits terminal mode.
- `<C-h>` (Normal mode): Moves focus to the left window.
- `<C-l>` (Normal mode): Moves focus to the right window.
- `<C-j>` (Normal mode): Moves focus to the lower window.
- `<C-k>` (Normal mode): Moves focus to the upper window.
- `<left>`, `<right>`, `<up>`, `<down>` (Normal mode): These are now disabled
  and will show a message encouraging you to use `h`, `j`, `k`, and `l`.

## Which-Key Groups (`init.lua`)

These are prefixes that group related keybindings:

- `<leader>s`: Group for **[S]earch** related actions.
- `<leader>t`: Group for **[T]oggle** related actions.
- `<leader>h` (Normal & Visual modes): Group for Git **[H]unk** actions.

## Telescope (Fuzzy Finder) (`init.lua`)

- `<leader>sh`: **[S]**earch **[H]**elp tags.
- `<leader>sk`: **[S]**earch **[K]**eymaps.
- `<leader>sf`: **[S]**earch **[F]**iles.
- `<leader>ss`: **[S]**earch **[S]**elect Telescope (lists available pickers).
- `<leader>sw`: **[S]**earch current **[W]**ord under cursor.
- `<leader>sg`: **[S]**earch by **[G]**rep (live grep).
- `<leader>sd`: **[S]**earch **[D]**iagnostics.
- `<leader>sr`: **[S]**earch **[R]**esume (reopens the last Telescope picker).
- `<leader>s.`: **[S]**earch Recent Files.
- `<leader><leader>`: Find existing buffers.
- `<leader>/`: Fuzzily search in the current buffer.
- `<leader>s/`: Search in open files.
- `<leader>sn`: **[S]**earch **[N]**eovim configuration files.

## LSP (Language Server Protocol) (`init.lua`)

These keybindings are active in buffers with an attached Language Server.

- `grn`: **[R]**e**[n]**ame the variable under the cursor.
- `gra` (Normal & Visual modes): Go to **[C]**ode **[A]**ction.
- `grr`: Go to **[R]**eferences.
- `gri`: Go to **[I]**mplementation.
- `grd`: Go to **[D]**efinition.
- `grD`: Go to **[D]**eclaration.
- `gO`: Open document symbols.
- `gW`: Open workspace symbols.
- `grt`: Go to **[T]**ype Definition.
- `<leader>th`: **[T]**oggle Inlay **[H]**ints.

## Formatting (`init.lua`)

- `<leader>f`: **[F]**ormat the current buffer using `conform.nvim`.

## Debugging (`debug.lua`)

- `<F1>`: Step Into.
- `<F2>`: Step Over.
- `<F3>`: Step Out.
- `<F5>`: Start/Continue debugger.
- `<F7>`: Toggle the debugger UI to see the last session result.
- `<leader>b`: Toggle Breakpoint.
- `<leader>B`: Set a conditional Breakpoint.

## GitSigns (`gitsigns.lua`)

- `]c` (Normal mode): Jump to the next git change (hunk).
- `[c` (Normal mode): Jump to the previous git change (hunk).
- `<leader>hs` (Normal mode): Stage hunk.
- `<leader>hs` (Visual mode): Stage selected lines.
- `<leader>hr` (Normal mode): Reset hunk.
- `<leader>hr` (Visual mode): Reset selected lines.
- `<leader>hS`: Stage the entire buffer.
- `<leader>hu`: Undo stage hunk.
- `<leader>hR`: Reset the entire buffer.
- `<leader>hp`: Preview hunk.
- `<leader>hb`: Blame line.
- `<leader>hd`: Diff against index (staged).
- `<leader>hD`: Diff against the last commit.
- `<leader>tb`: Toggle current line blame.
- `<leader>tD`: Toggle preview of deleted lines.

## Neo-tree (File Explorer) (`neo-tree.lua`)

- `\` (Normal mode): Reveal the current file in the Neo-tree file explorer.
- `\` (In Neo-tree window): Close the Neo-tree window.
