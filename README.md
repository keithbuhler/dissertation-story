# Dissertation

A version control and backup repository for my dissertation, which I am writing in Markdown with Sublime Text 3. Everything is copyrighted until further notice. 

## How to write a dissertation

Writing a dissertation can be enjoyable. Brian Tracy says you eat an elephent one bite at a time. Start early, work steadily, do small bits at a time, and take breaks.  

You can read the story of how I approached this massive project [here.](http://keithbuhler.com/phd-how-to) Briefly, I began graduate school in 2012. Began a series of increasingly detailed proposals in 2014. Received approval for the dissertation proposal in 2015. Been writing since then. 

## Writing Tools

I began writing in Word, then in Scrivener, then in Sublime Text 3. I learned Markdown over the winter of 2015 and began writing all my papers and notes in Markdown. I coded some very simple PHP to change the color scheme and learned how to use Pandoc-citeproc to embed "citekeys" which are converted to lovely footnotes when exported. The manuscript is therefore mostly plain text with Markdown tags and citekeys. The "front matter" required a bit of Latex, which took about 3 hours to Google, copy/paste, customize, test, and troubleshoot. It's now done and pretty nearly perfect. 

I went ahead and created a repo for the Dissertation Template.

This repository includes the humble beginnings of a formatting instructions for philosophy dissertations that are clean and beautiful. The code elements are mostly Markdown, but include Latex, Bibtex, and CSL.



# A Template for Philosophy Dissertations

The humble beginnings of template code (Markdown, Latex, Bib, and CSL) you need to format your dissertation to be clean and beautiful. 

## How to use


### Pre-research
1. Look at the dissertation-sample.pdf. Looks nice, yes? 
2. Look at the dissertation-smaple.md. Looks a little messy, but that's the code!
4. Learn a tiny bit of baby LaTex. The little bit of and LaTex formatting I've included is almost exclusively for the front matter and Table of Contents. I also inserted (optional) epigraphs because epigraphs are cool. 

### Writing

4. Write your dissertation in Markdown. You can use Macdown, Dillinger, Mou, or Sublime Text 3. You can write chapter by chapter, and stitch it together in one big file at the end; or write one big file with "#" headings separating chapters. 
5. Replace all the content in the front matter from the "Sample Front Matter" with your title, advisors, dedication, etc. 
6. Copy/paste the "Sample Front Matter" into your dissertation file. 

### Footnotes

7. You can do footnotes with the simple Markdown method: 



            to place footnote number in the text.[^1] 

            Anywhere in the document put this: 

            [^1]: This is the content of footnote.

or you can use the pandoc-cite-proc with Sublime Text 3 and a big Bibtex file with all your citations.


## Export to PDF

8. You can PDF it in various ways.  With PDF Latex, Texts.io, Pandoc, or Sublime Text 3. 
9. To use Sublime Text 3 (2 or 3 really), create a "build system" and use my "Sample dissertation formatting.latex" file as your initial layout. Replace your last name where it says "YOUR NAME HERE" if you want your last name to appear on the header like the sample. Make sure Sublime knows where your bibliography file is located, where your "Sample CSL" file is located, and where the source dissertation.markdown file is located. 
10. Build, and you have a dissertation beautifully formatted!

