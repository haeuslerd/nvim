# KEYBINDINGS
    :q to exiting
    :w to save
    :wq to save and exit
    :q! to exit without saving
    :colorscheme to change colorscheme
    i change to insert mode
    esc for exiting insert mode
    v in normal mode -> mark text for copying
    r in NERDTree to refresh directory
    :term to open terminal
    CTRL + W + W to switch between windows
    CTRL + W + V to split window vertically
    CTRL + W + S to split window horizontally
    CTRL + W + Q to close window
    SHIFT + <> for shifting forward/backwards
    / search for text, not case sensitive with corect set -> Press Enter -> n for forward search/ N for backwards search
    :s%/search_word/replace_word/g -> search and replace in entire file
    :s/search_word/replace_word -> replace in single line
    :buffers to show all buffers
    :bd [nr] to remove buffer from list
    :b [nr] to navigate to buffer
    :bn navigate to next buffer

## NORMAL MODE
    dd delete line/ d4 + arrow done deletes 4 lines
    dw delete word
    gg jump to top of file
    G jump to end of file

# HELP WITH PLUGINS

## PACKER
    :PackerInstall
    :PackerCompile (use whenever changes to plugins are made)
    :PackerUpdate
    :PackerClean
    :PackerStatus
    :PackerSync

    :checkhealth treesitter/telescope to check if everything is working

# NERDTree
## Bookmarks
    :Bookmark name to create a bookmark
    :Bookmark name to go to a bookmark
    :EditBookmarks to edit bookmarks

## Other
    cd change working directory
    u for navigate up directory
    mm for renaming files 
    m to open NERDTree menu -> ESC to close
    a to create new child node. Append / to create a new directory
    f show hidden directories
    ? show help

# UndotreeToggle
    :UndotreeToggle, use for undo/redo history

# Telescope
    \ff to find files
    \fg to for live search inside files
# HARPOON
    CTRL + m to mark file for HARPOON
    CTRL + e to show all files

# Mason LSP
    :Mason go to lsp settings

# ToggleTerm
    :ToggleTerm to open terminal
