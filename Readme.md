# Status of Changes
* **2018-10-17:** Workshop Handout (docx) converted to Markdown. Content and other workshop files unchanged, to stay in sync with current Word and PDF documents.

# Doc to Markdown Conversion Process
* Install [Pandoc](https://pandoc.org/installing.html)
* Convert the Word document to Markdown using Pandoc
* Review the output file in a Markdown Editor (see below) for the following problems, and fix as needed:
  * Image paths, links, position around TEXT
  * Headers
  * Links (URLs, emails)
  * Numbering (may have restarted at text changes like blockquotes)
  * New lines (extra line breaks added, sometimes splitting up sentences)
  * Conversion of "Notes" to blockquotes (">")
  * Use of bold, italics
  * Indentation

## Markdown Editors
* Atom (already installed on SGC lab machines)
  * Tips:
    * Ctrl Shift M - Toggle Preview Mode
    * Packages menu - Settings View - Install Packages
      * markdown-toc - To add a Table of Contents - helps in verifying header levels against original Word documentation
      * markdown-scroll-sync - To sync location on Preview pane with cursor in Script pane
   * Packages menu - Settings View - Open - Editor - check boxes here to show line numbers, and invisible characters (space, tabs, new lines, etc)
* [stackedit.io](https://stackedit.io/app#)
