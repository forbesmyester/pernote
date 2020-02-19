# pernote

A script for searching and editing a personal wiki wrote in 100% BASH.

It integrates nicely with [fzf](https://github.com/junegunn/fzf) for quick selection and the date option supports options supported by `date -d` like 'next week' etc.

    pernote - Interact with personal wiki files
    
    Usage:

        pernote - WIKI_NAME ACTION OPTION

    Examples:

        pernote [WIKI_NAME] new/n - Create an entry
        pernote [WIKI_NAME] filename/f - Search for filename
        pernote [WIKI_NAME] date/d [DATE_STR] - Open note for a day
        pernote [WIKI_NAME] content/c - Search for content
        pernote [WIKI_NAME] tag/t - Search for tag
        pernote [WIKI_NAME] git/g - Interact with git
