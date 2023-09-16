# PDF-Renamer-with-Llama2

This notebook aims to provide a tool for extracting the title from PDFs with the idea of renaming them to their rightful name, especially scientific publications.

It employs the Llama 2 language model, which analyzes the text as an alternative to the lack of metadata or unique identifiers, from which it extracts the title.

To do this, the first 300 characters of the PDF are analyzed, although this value can be altered.

As a demonstration of its effectiveness, it is tested on 47 different scientific PDFs, manually labeled. 
As a result, the model succeeds most of the time, but not always. The demonstration is available for anyone who wants to verify the effectiveness of this method and decide whether to use it or not.
