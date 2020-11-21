
# docs-as-code
Docs as code tutorial

## What is Markdown
Markdown is a lightweight text format that 
  * allows writers to focus more on writing 
  * without struggling much with formatting and style rules
  * and format the document using simple plain-text shortcodes
  
File extensions:
 * .md
 * .markdown 
 
It was created by John Gruber in 2004.

### MD Editor vs WYSIWYG editor
Unlike MS Word or other WYSIWYG editors where you click buttons, markdown lets you simply add syntax of the type of format that you want to use for word or sentence.

### Why to use Markdown
1. Can be used to create anything. For example, website, presentations, email messages, comments, and technical documentation.
1. MD files are easily portable to other applications.
1. No dependency on platform. Use on macOS, Windows, Linux, iOS, and Android operating systems. There are web-based applications also designed specially for MD.
1. Simple to get started. For example, open [Dilligner](https://dillinger.io/)

### How is Markdown file converted to HTML or PDF?
Only requirement is a Markdown application capable of processing the Markdown file. 
Markdown file - Markdown app - HTML
Markdown application uses a Markdown processor, also called as parser to convert markdown-formatted text into HTML output.

## Key Elements
1. Headings
2. Paragraphs 
3. Formatting: Italics and Bold
4. Lists
4. Links
5. Graphics (Images/Videos)
6. Blockquotes
7. Codes

### Headings
## This is header two
## This is header three
### This is header four
#### This is header five
##### This is header six
 

### Paragraphs
The course on Technical documentation tools introduces Markdown, the simple text format that renders output into multiple formats. Simply open a free version of any of the markdown editors and start documentation.

Even Github supports Markdown editor and the file name has .md as suffix.

### Formatting: Italics and Bold
To make a phrase italic in Markdown, you can surround words with an underscore (_ ). For example, _this_ word would become italic.
This will **really** get your point across.

### Lists
Unordered

Use * with space before the list item.

Ordered

Use number 1 with space before the numbered item. 

Nested list

-Press tab for alignment and then use * or number.



List with separate lines

-Simply add indentation and start the line from where list start and then indent by at least single space.



### Links
Links

-Inline link [Tech Writer’s Tribe](https://techwriterstribe.com/)

Make it bold or italics too


### Graphics (Images/Videos)
Links and images are almost same. You do not insert images, but provide the path to the image folder.

![Tech Writer’s Tribe logo](https://techwriterstribe.com/cropped-pivot-tribe-logo-final-02-jpg/)

Enhance images

Alt Text for Accessibility


### Tables
ables
You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

Training | Events
------------ | -------------
API doc | Markdown
DITA | GitHub
Agile | DDLC
Flare | Videos


### Blockquotes
Just use the sign greater than > before the quote

Within quotes, you can use other MD elements. For example, bold, italics and so on.

### Codes
`start`

```
{
    "status":"OK",
    "data":
        {
            "message": "Welcome, world!"
        }
}
```


## References
### Getting Started
 * https://www.markdownguide.org/getting-started/
 * Extended syntax: https://www.markdownguide.org/extended-syntax/
 * Basic Syntax: https://www.markdownguide.org/basic-syntax/

### Create our own website
If you’re looking for the simplest possible way to create a website with Markdown files, check out blot.im and smallvictori.es. After you sign up for one of these services, they create a Dropbox folder on your computer. Just drag and drop your Markdown files into the folder and — poof! — they’re on your website. It couldn’t be easier.

### Markdown document authoring applications
 * Mac: MacDown, iA Writer, or Marked
 * iOS / Android: iA Writer
 * Windows: ghostwriter or Markdown Monster
 * Linux: ReText or ghostwriter
 * Web: Dillinger or StackEdit
 * Others: VSC (Visual Source Code editor)

