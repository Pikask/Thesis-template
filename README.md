A template for any thesis

Before running, make sure to update metainfo in classicthesis-config.tex in line 40-56.

Examples of figures, tables, marginfigures, margintext and equations are included in the script.

main.text is where everything is gathered and referenced from.

Abstract, acknowledgements, dedications and introduction is in the FronBackMatter folder and should be edited there.

FrontBackMatter/Acronyms is a long list of acronyms in the thesis. First time the acronym is used, it is written in full as defined in the file. After that it will only be used in short form, but have a hyperlink to the acronym page where the meaning can be found. All acronyms in the list will be shown - regardless wheather they are used or not.

FrontBackMatter/Bibliography.bib is where the bibliography is and follows bibtex syntax. Only books actually referenced in the thesis is shown in the bibolography in the end of the thesis. I recommend using \citetitle{} and \citeauthor{} the first time to give the reader context on the background material. \citep{} shows the citation number and creates a hyperlink to the bibliography at the end of the document.

ListOfFigures and ListOfTables will automatically be updated with hyperlinks from the list to the page of the figure.

Parts is the first devision of content. I've chosen to split parts into files to make everything more managable. The Parts themselves are in the Parts folder. Within each part one can specify chapters, sections, subsections and so on.

All images are placed in the Images folder and should be referenced to by Images/part1/subfolder/image.png. It makes it much more mangable to create subfolders at each part (and perhaps chapter) for your images

The Appendicies are in the Appendicies and are identical to Parts - I just wanted them seperate.


Have fun and feel free to write to me a bitch about the setup.
