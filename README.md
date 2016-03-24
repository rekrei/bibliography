# Instructions

The idea is to keep our bibliographic citations somewhat organised through a git repository. Each addition should include updating the master document, as well as includeing a BibTex formatted citation in the repository. Citations should simply go into the citations directory, until such a point that it becomes unmanagable and we need to reorganise it.

For now, it seems the best way to manage our bilbiography is to copy a BibTex formatted citation into the master "bibliography.bib" file, which you can then import into any citation management system and use for your own writing.

## Summary

1. Copy a BibTex formatted citation to the end of bibliography.bib
2. Create a folder in the bibliography with month and year, first author's last name, journal abbreviation... so 201501_smith_science for example.
3. Create a tex file inside that folder with a section heading including the author's name and title of the article or presentation. Copy the abstract of the article into the body and save. 
4.  For every keyword you want to add in the index, include the command \index{yourKeyword} in the .tex file of the abstract (See [wiki](http://gitlab.itn-dch.net/fellows/biblio/wikis/home))
5. Include the newly created tex file in the main bibliography.tex file. Try and keep them in alphabetical order.
6. Add your changes and push to the repository.
