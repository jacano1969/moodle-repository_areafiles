"Embedded files" (repository_areafiles) plugin allows to re-use the files
embedded in the current text area.

By default it can be accessed by all users but admin is able to limit it.

To install: copy folder areafiles to <ROOTDIR>/repository/, login as admin and
run upgrade script.

To use: Open any form with textarea in HTML mode, insert an image using
filepicker as usual. Click "insert/edit image" again and in filepicker window
select repository "Embedded files". The list of all files used in this textarea
will appear and user can re-use any of them.

You can insert media and/or links to other files as well. Note that files in
filepicker are always filtered by the accepted file types (for example when
you add an image you will only see images even when other files present in area).