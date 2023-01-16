# python-docx-builder
Python script that builds a new .docx document replacing placeholders in template.docx

# How it works:
This script looks at the content of a template.docx document and replace all istance of the placeholers with the associated values that are stored in data.json.

The data.json file contains a list of keys and values (ex. "name": "Gino") and the placeholders in the tamplate.docx are rapresented has "key" (following the previous example the program will replace every istance of name with Gino).

My suggestion is to use keys that are non-obvious so that you don't accidentally substitute other words. For example if you have to change your name in the document don't just use "name" as a key but maybe "myname"

This program created a new document at the end called filled_document.docx and preserves template.docx
