# bookreader_title

This program was written to create new BookReader files and title pages for the William K. Everson Collection website. It is project-specific and will not run correctly without template files, and it must be located in the same directory as the templates. 

Each of the functions will read the template file, and write the user-inputed information to a new file. If there are no changes to any lines within the template, the program will write the line as is. 

Each title will have 3 files created by the program: a BookReader HTML file, a BookReader JavaScript File, and a PHP title page. The title page will be written to the existing 'titles' directory, and the BookReader files will be written to a title-specific directory, generated by the program.

The functions in this program are makeHtmlFile, makeBR, makeTitle, user_input, and the main function.
