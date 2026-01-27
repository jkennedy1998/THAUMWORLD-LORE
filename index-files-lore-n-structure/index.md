# index-files-lore-n-structure
> how lore files are written for man and machine

this repo stores lore as single keyword folders with a single index.md file.
pages are written to be read non-linearly and searched by keyword.

---
## keyword and folder rules

keywords are the folder names.
multi word keywords use dashes without spaces. example: concept-capture

capitol letters can mark keywords inside body text. THAUM, CAST, DEAD ZONE, etc.

---
## the power of markdown

# a single "#" denotes the title of the folder this file lives in.
## two "##" denote a section title.
### three "###" denote a subsection title.

no use of any "#" denotes general text.
">" denotes a comment, example, or clarification.

---
## how to format lists

when making lists use the "-" as follows.
"-" with four spaces for each level can denote depth. use this rarely.

#### list title here
- list item 1
- list item 2
- list item 3
    - list item 3 a
    - list item 3 b

---
## visual clarity of quotes and parenthesis

spaces to pad the contents of quotes and parenthesis, as well as on colons.
dashes or hashes do not need padding between alike characters.

---
## special markings

"[ TAGNAME ]" denotes a TAG of the name, "TAGNAME".
":" means something has a relevant piece of information carried with it.
"( name )" is the formatted way of using parenthesis with spaces on each inner padding.

---
## status

use a status line to signal the current state of a page.
example: STATUS: canonical

---
## page templates

### model template
- overview
- definitions
- mechanism
- constraints
- failure modes
- observable consequences
- open questions
- related links
- STATUS: canonical

### concept template
- definition
- scope
- related models
- related places or people
- STATUS: canonical

### place template
- overview
- geography
- ecology or hazards
- culture and politics
- economy and tech
- history
- related links
- STATUS: canonical

### event template
- summary
- causes
- timeline beats
- outcomes
- participants
- competing accounts
- related links
- STATUS: canonical

### document template
- document header ( author, date, location, medium )
- text
- editor notes ( reliability, what it supports or contradicts )
- related links
- STATUS: canonical
