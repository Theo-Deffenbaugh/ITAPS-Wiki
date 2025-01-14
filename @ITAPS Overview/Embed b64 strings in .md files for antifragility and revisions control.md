
Most program files are comprised of text and a link to a image file.  

This creates an opportunity for losing track of a pointer, and thus is a more optimized, but fragile structure.

See [[Anti-Fragile]].

The design choice in ITAPS apps is to embed images as b64 strings, most likely webp, see [[Why Webp]]

This also has the advantage to use git structure for revision control for entire file, including embedded graphics


