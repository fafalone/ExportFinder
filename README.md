# ExportFinder
Search for a DLL exporting a given symbol

![image](https://github.com/user-attachments/assets/e612d638-158f-4176-a42e-0bb9dd8c798c)

This is kind of a niche tool but I needed it for my projects so thought someone else might too.

Handles both 32bit and 64bit DLLs from either 32 or 64 bit exe. Of interest is that this parses PE files manually, and reads all the entries in the `IMAGE_EXPORT_DIRECTORY`. So if you were ever curious about that kind of thing, this is a nice simple intro.

Requires Windows Vista or newer.
