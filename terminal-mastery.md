# Some ever-so valuable unix terminal commands for web development

...which I seem unable to commit to memory.

## Find and replace a string from files

	perl -pi -w -e 's/string_to_be_replaced/string_to_replace/g;' */*.php

Note: `*/*.php` will find and replace in all files in the folders contained within the current directory.
