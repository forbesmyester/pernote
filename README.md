# pwiki

A script for searching and editing a personal wiki wrote in 100% BASH.

It integrates nicely with [fzf](https://github.com/junegunn/fzf) for quick selection and the date option supports options supported by `date -d` like 'next week' etc.

    pwiki - Interact with personal wiki files
    
    Usage:

        ./pwiki - WIKI_NAME ACTION OPTION

    Examples:

        pwiki [WIKI_NAME] new/n - Create an entry
        pwiki [WIKI_NAME] filename/f - Search for filename
        pwiki [WIKI_NAME] date/d [DATE_STR] - Open note for a day
        pwiki [WIKI_NAME] content/c - Search for content
        pwiki [WIKI_NAME] tag/t - Search for tag
        pwiki [WIKI_NAME] git/g - Interact with git
