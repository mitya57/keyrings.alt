1.3
===

#9: Moved base file backend functionality from 'keyrings.alt.file'
to 'keyrings.alt.base_file'. This allows the 'Windows' module to
no longer trigger a circular import with the 'file' module.

1.2
===

Updated project skeleton. Tests now run under tox. Tagged
commits are automatically released to PyPI.

#6: Added license file.

1.1.1
=====

Test cleanup.

Exclude tests during install.

1.1
===

FileBacked backends now have a ``repr`` that includes the file path.

1.0
===

Initial release based on Keyring 7.3.
