# notmuch
## Subcommands
```
notmuch show '*' # output all matching mails 
notmuch search '*' #output all matching threads
notmuch count '*'
notmuch address '*'
```
## Query Options
`man notmuch-search-terms`
options: body, from, to, tag, folder, date ...
boolean operators: and, or, not
wildcard operator: *
```
notmuch count tag:new
notmuch search folder:inbox and folder:sent
# date:since..until 
notmuch count date:4days..today
```
