# Frequently Asked Questions
## I made a change to my page and saved/committed it, but I don't see the change when I refresh my browser
### Answer:
Changed may take anywhere from 1-5minutes to update. It's just the nature of github and webhosting
## I can't get my github flavour markdown tables to display properly with Jekyll themes... what gives?
#### Answer
One will need to edit the `_config.yml` file with a little magic:
```
markdown: kramdown
redcarpet:
  extensions:
    - no_intra_emphasis
    - fenced_code_blocks
    - autolink
    - tables
    - strikethrough
    - superscript
    - with_to_data
```
## I am using VS Code to write my resume in MarkDown, is there a spell checker?
VS Code is very powerful through the use of extensions. For example, [take your pick](https://marketplace.visualstudio.com/search?term=spellcheck&target=VSCode&category=All%20categories&sortBy=Relevance)