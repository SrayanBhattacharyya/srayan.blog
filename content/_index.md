+++
title = "Paper Title"
[extra]
authors = [ # authors should be listed as an array in [extra] rather than via Zola's built-in support
    {name = "Author 1", star = true}, # prints a star next to the author name, often useful for 'equal contribution' or similar flags
    {name = "Author 2", url = "https://example.com/", star = true}, # url is optional
    {name = "Author 3"},
]
star = 'Equal contribution' # adds the text 'Equal contribution' with a star superscript to the title
venue = {name = "Example Conference", date = 2023-12-10, url = "https://example.org/"} # date of publication should be listed here, to distinguish it from the date the website itself was written and updated, which can be added via Zola's built-in support
buttons = [ # this theme supports any set of buttons, but and will by default include an SVG icon for the examples listed below
    {name="Paper", url = "https://example.com", no_icon = true}, # to disable drawing the icon, set no_icon to true
    {name="PDF", url = "https://example.com"},
    {name="Code", url = "https://example.com"},
    {name="Video", url = "https://example.com"},
    {name="Slides", url = "https://example.com"},
    {name="Poster", url = "https://example.com"},
    {name="Your custom button", url = "https://example.com"}, # to add an icon, add it as an include, and override the macro icons.html
]
katex = true # to enable math via katex - whether using server-side or client-side rendering - set katex to true
favicon = false # set to true to use favicon.ico as the page's favicon
large_card = false # set to true to generate a large-size Twitter card
+++

Your page's Markdown content goes here...
