"Embedded files Plus" (repository_areafilesplus) plugin allows to re-use the
files embedded in the current text area and provides a simple interface to
delete unnecessary files.

This plugin is designed for Moodle version 2.3 and below since they don't have
support for TinyMCE plugins. For Moodle 2.4 and above it is recommended to use
instead repository_areafiles and tinymce_managefiles.

To install: copy folder areafilesplus to <ROOTDIR>/repository/, login as admin
and run upgrade script.

To use: Open any form with textarea in HTML mode, insert an image using
filepicker as usual. Click "insert/edit image" again and in filepicker window
select repository "Embedded files". The list of all files used in this textarea
will appear and user can re-use any of them. The link "Manage" on top can be
used to delete unnecessary files. Note that other windows need to be refreshed
afterwards.

You can insert media and/or links to other files as well. Note that files in
filepicker are always filtered by the accepted file types (for example when
you add an image you will only see images even when other files present in area).